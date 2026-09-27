# Slide Marp - istruzioni

**Sorgente**: `slides.md` · **Temi**: `themes/` · **Config**: `.marprc.yml`

---

## ⚠️ La cosa da sapere prima di tutto

Marp, di default, **accetta i tag HTML ma cancella gli attributi `style`** (li considera un vettore XSS).
Questo deck usa stili inline per le card, le griglie e i grafici: senza HTML abilitato le slide si aprono, ma **perdono tutti i riquadri, le colonne e gli sfondi** - sembrano solo testo sbagliato, e non c'è nessun errore a dirtelo.

Il file **`.marprc.yml`** in questa cartella risolve il problema per la riga di comando:

```yaml
html: true
allowLocalFiles: true
```

Finché esporti **da dentro questa cartella**, funziona da solo. Se copi `slides.md` altrove, portati dietro anche `.marprc.yml`.

### Per l'anteprima in VS Code

Serve l'estensione **Marp for VS Code**, più questa impostazione - altrimenti l'anteprima mostra lo stesso problema:

```json
"markdown.marp.enableHtml": true
```

*(Preferenze → cerca "marp html" → spunta la casella.)*

---

## I due temi

Un solo `slides.md`, un solo tema: **`carta`**, fondo chiaro - pensato per sala illuminata, schermi grandi, stampa e PDF da condividere.

```yaml
theme: carta
```

> Il tema scuro `inchiostro` è stato **eliminato il 25 settembre 2026**, file compreso.

**Non ci sono colori scritti a mano nelle slide.** Anche i grafici SVG usano classi (`.s-fall`, `.f-accent`…) definite nel tema. Se aggiungi un elemento SVG, dagli una classe invece di un `fill="#..."`.

---

## Esportare

Marp è installato in locale (`node_modules`), quindi si usa il binario diretto - più veloce di `npx`:

```bash
# PDF
./node_modules/.bin/marp slides.md --pdf -o slides-carta.pdf

# HTML navigabile da tastiera
./node_modules/.bin/marp slides.md --html -o slides.html

# PowerPoint, se gli organizzatori lo chiedono (porta con sé le note)
./node_modules/.bin/marp slides.md --pptx -o slides.pptx

# Anteprima dal vivo mentre modifichi
./node_modules/.bin/marp slides.md --preview
```

### Se un export sembra bloccato

L'export apre un Chromium headless. Se interrompi il comando a metà, **il Chromium resta vivo**: qualche tentativo interrotto e te ne ritrovi decine che affamano la macchina, e gli export successivi rallentano fino a sembrare bloccati.

```bash
pgrep -f Chromium | wc -l     # quanti ce ne sono
pkill -9 -f Chromium          # falli fuori tutti
```

⚠️ Non usare `pkill -f marp`: il pattern matcha anche la riga di comando della shell da cui lo lanci, e ti ammazza il terminale.

---

## Le note per chi parla

Sono nei commenti HTML dentro ogni slide, quelli così:

```markdown
<!--
"Frase da dire ad alta voce."
ATTENZIONE: precisazione da non sbagliare.
-->
```

Le vedi nella **presenter view** di Marp (`P` nell'anteprima VS Code) e finiscono nelle note dell'export **PPTX**. Nel PDF non compaiono: se vuoi le note stampate, esporta in PPTX e stampa da lì.

Le righe che iniziano con **ATTENZIONE** sono le trappole emerse dalla verifica delle fonti - tipo *"non dire 17 per cento, di' 17 punti"*. Rileggile prima di salire sul palco.

---

## Struttura

46 slide, sette parti:

| | Slide | |
|---|---|---|
| **Apertura** | 1–6 | Il pendolo delle dichiarazioni, e il paradosso automazione/aumento |
| **Parte 1** | 7–16 | I dati: Stanford, Italia, i pioli mancanti |
| **Parte 2** | 17–19 | Veracode e il combinato disposto |
| **Parte 3** | 20–23 | Karpathy, pavimento e soffitto, Naur |
| **Parte 4** | 24–27 | Cosa resta da insegnare |
| **Parte 5** | 28–33 | Gli studi sull'apprendimento |
| **Parte 6** | 34–43 | I cinque esercizi |
| **Chiusura** | 44–46 | La risposta, tre cose, grazie |

Ogni slide con un dato porta la **fonte nel footer**. È voluto: dopo la verifica delle fonti, il pubblico deve sempre vedere da dove viene il numero senza che tu debba dirlo.

---

## Modificare

- `---` su una riga da sola separa le slide
- `<!-- _class: lead -->` centra la slide · `<!-- _class: card -->` è lo stacco di parte
- `<!-- _footer: '...' -->` cambia la fonte di quella slide
- I colori stanno tutti nelle variabili CSS in cima al file: `--a` ambra, `--fall` rosso, `--rise` verde, `--bg` fondo, `--t` testo

**Dopo ogni modifica, riesporta e guarda il PDF.** Marp non avvisa quando una slide sfora: taglia e basta, in silenzio. È così che sono venuti fuori i tre problemi di questo deck.

---

## ⚠️ Due trappole di Marp che fanno perdere ore

Entrambe **non danno nessun errore**. L'export riesce, il PDF si apre, e le slide sono sbagliate.

### 1. Gli attributi `style` vengono cancellati se l'HTML non è abilitato

Sintomo: le card, le colonne e i riquadri spariscono. Il testo c'è tutto, ma impilato e senza sfondi - e siccome le **classi** CSS continuano a funzionare (font e colori restano giusti), sembra "quasi a posto" invece che rotto.

Causa: Marp considera `style=` un vettore XSS e lo rimuove, pur lasciando passare i tag.
Rimedio: il `.marprc.yml` di questa cartella. Non cancellarlo.

### 2. Una riga vuota dentro un blocco HTML lo spezza in due

Questa è la più insidiosa. Markdown chiude il blocco HTML **alla prima riga vuota**: tutto quello che viene dopo esce dal `<div>` o dall'`<svg>` e viene reinterpretato come testo normale.

```html
<svg viewBox="0 0 980 330">
  <line x1="150" y1="150" x2="760" y2="222" stroke="#D9644A"/>
                                    ← QUESTA RIGA VUOTA ROMPE TUTTO
  <text x="780" y="216">−11%</text>  ← finisce fuori dall'SVG, come paragrafo
</svg>
```

Nel grafico di Stanford era successo esattamente questo: le due linee si disegnavano, ma le etichette «−11%» e «+10%» cadevano sotto il grafico come testo, sfondando la slide.

**Regola:** dentro `<div>` e `<svg>`, mai righe vuote. Se ti serve respiro visivo nel sorgente, usa un commento:

```html
  <!-- etichette -->
```

---

## Gli altri file del progetto

Stanno tutti in **`../ricerca/`**:

| File | Cosa contiene |
|---|---|
| `canovaccio.md` | La scaletta ragionata: cosa dire, cosa mostrare, cosa tagliare |
| `esercizi-aula.md` | I cinque esercizi con codice, soluzioni e numeri verificati |
| `contesto.md` | Il documento discorsivo con tutte le evidenze |
| `audit-fonti.md` | Il registro della verifica: cosa è stato corretto e perché |
| `ricerca-iniziale.md` | La prima ricognizione schematica, con la tabella dati-per-slide |

---

## Rigenerare il PDF

```bash
cd talk
./node_modules/.bin/marp slides.md --pdf -o slides-carta.pdf --no-stdin
# poi, per comprimerlo da ~22 MB a ~3 MB senza perdita visibile:
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.5 -dPDFSETTINGS=/printer \
   -dDetectDuplicateImages=true -dNOPAUSE -dQUIET -dBATCH \
   -sOutputFile=slides-compresso.pdf slides-carta.pdf && mv slides-compresso.pdf slides-carta.pdf
```

## Materiali di terzi

Il deck cita e riproduce materiale altrui a scopo didattico: figure dai paper
citati, ritratti sotto licenza Creative Commons (la foto di Leone XIV è
CC BY-SA 4.0 di Edgar Beltrán, The Pillar; quella di Andrej Karpathy è
CC BY 3.0 di Gladwin Analytics), un'icona da pngall e un breve estratto video.
Ogni slide porta la fonte nel footer.
