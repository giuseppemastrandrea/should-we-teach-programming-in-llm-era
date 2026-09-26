# Dovremmo ancora insegnare a programmare nell'era degli LLM?

Talk per **Come To Code 2026** - 26–27 settembre, Pignola (PZ).
Giuseppe Mastrandrea.

---

## Da dove partire

| Se devi… | Apri |
|---|---|
| **Provare il talk** | `talk/slides-carta.pdf` - 57 slide, fondo chiaro |
| **Modificare le slide** | `talk/slides.md`, poi leggi `talk/README.md` |
| **Ripassare i contenuti** | `ricerca/contesto.md` - il documento discorsivo, si legge dall'inizio alla fine |
| **Preparare i momenti interattivi** | `ricerca/esercizi-aula.md` - i cinque esercizi, con soluzioni e numeri |
| **Difendere un dato in Q&A** | `ricerca/audit-fonti.md` - cosa è verificato, cosa no, e perché |

---

## `talk/` - le slide

Sorgente **Marp**: un solo `slides.md`, un solo tema.

```
talk/
├── slides.md                 57 slide, note per chi parla incluse
├── assets/                   i ritratti dell'apertura (Jobs, Obama, Huang, Ng, Amodei, LaMoreaux)
├── themes/carta.css          fondo chiaro  ← l'unico tema
├── slides-carta.pdf          export
├── .marprc.yml               ⚠️ serve: abilita l'HTML inline. Non cancellarlo.
└── README.md                 export, trappole, struttura
```

```bash
cd talk
./node_modules/.bin/marp slides.md --pdf -o slides-carta.pdf
./node_modules/.bin/marp slides.md --preview      # anteprima dal vivo
```

**Le note per chi parla** sono nei commenti HTML dentro ogni slide: si vedono nella presenter view (`P` nell'anteprima) e nell'export PPTX. Le righe che iniziano con **ATTENZIONE** sono le trappole emerse dalla verifica delle fonti - tipo *«non dire 17 per cento, di' 17 punti»*. Rileggile prima di salire sul palco.

---

## `ricerca/` - il lavoro di fondo

| File | |
|---|---|
| `contesto.md` | Il documento principale: mercato del lavoro, tecnologia, ricerca sull'apprendimento, didattica, argomenti. Discorsivo, con i link alle fonti. |
| `struttura-slide.md` | **Il documento di lavoro sui contenuti**: per ogni slide layout, testi, visual, note. È lo specchio di `slides.md` e si modifica prima del Marp. |
| `canovaccio.md` | La scaletta ragionata slide per slide. ⚠️ Superata da `struttura-slide.md` per la numerazione. |
| `esercizi-aula.md` | I cinque esercizi. **Tutto il codice è stato eseguito**: i test verdi sono verdi davvero, l'exploit funziona, il centesimo balla. |
| `audit-fonti.md` | La verifica delle fonti: 6 errori corretti, 7 imprecisioni, 4 claim abbandonati, 21 confermati |
| `ricerca-iniziale.md` | La prima ricognizione, schematica. Superata da `contesto.md`, ma contiene la tabella dati-per-slide. |

Ogni file ha anche il `.pdf` accanto.

---

## `archivio/` - superato

`deck-html/` è la **prima versione delle slide**, scritta a mano in HTML prima di passare a Marp. Funziona ancora (un solo file, font incorporati, va senza rete) ma non è più quella mantenuta: le correzioni fatte dopo - numerazione delle parti, a capi, temi - ci sono solo nella versione Marp.

L'ho tenuta invece di cancellarla nel caso ti serva qualcosa da lì. Se non ti serve, si può buttare.

---

## Le due cose da sapere prima del 26

**I numeri sono verificati sulle fonti primarie** (21 settembre). Dove un dato non reggeva, è stato tolto - Apiiro, i numeri Randstad, il «+75%» di GitClear. Dove reggeva ma andava detto con precisione, la slide porta la fonte nel footer e la nota ti ricorda come pronunciarlo.

**Marp taglia in silenzio.** Se modifichi una slide e sfora, non te lo dice: esporta e basta. Dopo ogni modifica, riesporta il PDF e guardalo. Le due trappole che fanno perdere ore (attributi `style` rimossi, righe vuote dentro `<div>` e `<svg>`) sono spiegate in `talk/README.md`.
