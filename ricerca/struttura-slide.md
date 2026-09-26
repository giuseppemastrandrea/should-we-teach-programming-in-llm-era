# Struttura delle slide - documento di lavoro sui contenuti

Talk: **Dovremmo ancora insegnare a programmare nell'era degli LLM?**
Come To Code 2026 · Pignola (PZ) · Giuseppe Mastrandrea

Questo file è lo specchio testuale di `talk/slides.md`: serve a discutere i **contenuti**
senza guardare l'impaginazione. Si modifica qui, si decide, e solo dopo si tocca il Marp.

Per ogni slide: **layout**, **testi** (le parole che si vedono), **visual**, **nota per chi parla**.
I testi sono riportati per intero dove sono poche parole, sintetizzati dove sono lunghi.

> ### ✅ Stato · allineato
> **Il Marp è stato rigenerato il 25 settembre 2026: `talk/slides.md` ha ora 57 slide**, e
> `slides-carta.pdf` è aggiornato. **Il tema scuro è stato eliminato il 25 settembre** (spostato in `archivio/`): resta solo `carta`. Tutte le decisioni elencate in fondo
> sono **applicate**. La numerazione di questo documento e quella del deck **coincidono**, con due
> avvertenze sui numeri usati in chat durante la lavorazione:
>
> | In questo documento | Nel deck |
> |---|---|
> | slide 3 e 4 *(le citazioni)* | **3–9**, sette slide impilate che si accumulano |
> | 5–28 | 10–33 *(scalate di cinque)* |
> | «29-bis» *(enciclica)* | **35** |
> | «32-bis» *(la frase sulla generazione)* | **39** |
> | 33–50 | 40–57 |
>
> Le decisioni prese e i punti ancora aperti sono in fondo.



---

## Indice

| # | Slide | Parte |
|---|---|---|
| 1 | Titolo | - |
| 2 | Chi parla | - |
| 3 | Per vent'anni ci siamo detti una cosa sola | apertura |
| 4 | Poi, in diciotto mesi | apertura |
| 5 | Tutto e il contrario di tutto | apertura |
| ~~-~~ | ~~Oh shit, here we go again~~ · **TAGLIATA** *(era la 6)* | - |
| 6 | **PARTE 1 - Cosa dicono i dati** | stacco |
| 7 | Lo studio che conta · RIFINITA | 1 |
| 8 | **Le due metà dello studio** · NUOVA | 1 |
| 9 | **Cosa vuol dire «esposto»** · NUOVA | 1 |
| 10 | Il divario · RIFATTA | 1 |
| 11 | Non licenziati. Non svenduti. · RIFATTA | 1 |
| 12 | I limiti | 1 |
| 13 | Dove succede: sostituire o complementare | 1 |
| 14 | **Cosa hanno già escluso** · NUOVA | 1 |
| 15 | **E allora gli sviluppatori?** · NUOVA | 1 |
| 16 | **Il riassunto** · NUOVA · *slide-fotografia* | 1 |
| 17 | I ragazzi l'hanno già capito | 1 |
| 18 | IBM triplica le assunzioni entry-level | 1 |
| 19 | Nessuno ha tolto la scala | 1 |
| 20 | E in Italia? · RIFATTA DA ZERO | 1 |
| **21** | **Tre spiegazioni, nessuna rassicurante** · NUOVA | 1 |
| **22** | **PARTE 2 - Cosa fa davvero la macchina** · *Facciamo un punto* · RIFATTA | stacco |
| 23 | La sicurezza | 2 |
| 24 | Il combinato disposto | 2 |
| 25 | **PARTE 3 - Dove va a finire il mestiere** | stacco |
| 26 | Software 3.0 | 3 |
| 27 | Pavimento e soffitto | 3 |
| 28 | Le due frasi da portare a casa | 3 |
| 29 | **PARTE 4 - Cosa resta da insegnare** | stacco |
| ~~-~~ | ~~Cosa sta comprando davvero il mercato~~ · **TAGLIATA** *(era la 30)* | - |
| 30 | Bloom, rovesciato | 4 |
| 31 | La lista | 4 |
| 32 | **PARTE 5 - L'AI in aula: sì o no?** | stacco |
| 33 | 52 sviluppatori, 50% vs 67% | 5 |
| 34 | Sei modi di usarla. Due esiti. | 5 |
| 35 | ~1.000 studenti · PNAS | 5 |
| 36 | The Widening Gap | 5 |
| 37 | The Effortless Trap | 5 |
| 38 | **PARTE 6 - Cinque esercizi** | stacco |
| 39 | Esercizio 1 · Prompt Problem | 6 |
| 40 | Esercizio 2 · Explain in Plain English | 6 |
| 41 | Esercizio 3 · Trova la vulnerabilità | 6 |
| 42 | Non una. Tre. | 6 |
| 43 | Esercizio 4 · Il test di Naur | 6 |
| 44 | Il paradosso dei punti | 6 |
| 45 | Esercizio 5 · Code review al contrario | 6 |
| 46 | Un centesimo, tre volte | 6 |
| 47 | Cosa hanno in comune | 6 |
| 48 | Sì. Più di prima. | chiusura |
| 49 | Tre cose | chiusura |
| 50 | Grazie | chiusura |

---

# APERTURA · slide 1–5
*Obiettivo: far cadere l'autorità delle dichiarazioni e spostare il peso sui dati.*
*Quattro slide, non cinque: la 6 è stata tagliata e la 5 consegna direttamente alla Parte 1.*

## 1 - Titolo

**Layout** - Centrata, una colonna, niente numero di pagina.
**Testi**
- occhiello: `COME TO CODE 2026 · PIGNOLA`
- titolo: *Dovremmo ancora insegnare a programmare nell'era degli LLM?* (tre righe)
- filetto ambra
- `Giuseppe Mastrandrea`

**Visual** - Nessuno. Solo il filetto orizzontale sotto il titolo.
**Nota** - «Il titolo è una domanda vera, non retorica. Alla fine vi do la mia risposta, ma voglio che ci arriviate con i dati in mano.»

---

## 2 - Chi parla

**Layout** - Occhiello + titolo, poi tre righe impilate.
**Testi**
- occhiello: `CHI PARLA` · titolo: *Tre mestieri, un problema solo*
- **Sviluppatore.** *Il passato.*
- **Insegnante di informatica.** *Il presente.*
- **Formatore upskill e reskill per adulti.** *Il presente, quello scomodo.*

**Visual** - Nessuno.
**Nota** - Non è il CV: è stabilire da dove parli. Le tre persone che il problema riguarda contemporaneamente. Chiusura: «Non ho una risposta comoda. Ho dei dati.»

---

## 3 - Per vent'anni ci siamo detti una cosa sola

**Layout** - Griglia a due colonne: anno (mono, ambra, allineato a destra) | citazione + attribuzione.
**Testi** - Tre citazioni verificate sulle fonti primarie:
- **1995 · Steve Jobs** - «Everybody should learn how to program a computer, **because it teaches you how to think**.»
- **2013 · Barack Obama** (lancio dell'Hour of Code) - «**Don't just play on your phone - program it.**»
- **2024 · Jensen Huang** (World Governments Summit) - «It's almost exactly the opposite. It is our job to create computing technology such that **nobody has to program**.»

**Visual** - Nessuna immagine: la colonna delle date *è* la grafica. L'effetto è cronologico.
**Nota** - Le prime due sono la stessa idea a 18 anni di distanza. La terza è uno schiaffo: Huang non dice «è cambiato qualcosa», dice «è esattamente il contrario».
**Footer** - Jobs 1995 (Triumph of the Nerds) · Obama 2013 (Hour of Code) · Huang 2024 (WGS)

---

## 4 - Poi, in diciotto mesi

**Layout** - Identico alla 3 (ripetizione voluta), ma quattro righe.
**Testi**
- **2025 · Andrew Ng** (Snowflake Build) - «The bar to coding is **now lower than it ever has been**.»
- **2025 · Dario Amodei** (Council on Foreign Relations) - «In three to six months, AI is writing **90% of the code**.»
- **2025 · Jensen Huang su Amodei** (VivaTech) - «I pretty much **disagree with almost everything** he says.»
- **2026 · Nickle LaMoreaux, CHRO IBM** - «Le aziende che avranno più successo sono quelle che **hanno raddoppiato sulle assunzioni entry-level**.»

**Visual** - Nessuno.
**Nota** - Ritmo veloce. Il comico arriva alla terza (Huang contraddice Amodei) e alla quarta (IBM contraddice tutti). Opzionale: «Ng e Amodei dicono la stessa cosa a due mesi di distanza e ne traggono conclusioni opposte.»

---

## 5 - Tutto e il contrario di tutto

**Layout** - Slide-manifesto, centrata, solo titolo su due righe.
**Testi** - *Tutto e il contrario di tutto.*
**Visual** - Nessuno. Vuoto intenzionale.
**Nota** - «In trent'anni il pendolo ha fatto un giro completo e mezzo. E queste sono le persone che decidono dove va l'industria. Io devo decidere cosa scrivo nel programma di settembre. Quindi smetto di guardare le dichiarazioni e guardo i dati.»
↳ Da qui si passa **direttamente** alla card della Parte 1: la promessa («guardo i dati») viene mantenuta subito, senza la slide tagliata di mezzo.

---

## ~~6 - Oh shit, here we go again~~ · **TAGLIATA**

*Mostrava Claude.ai 49% vs Claude Code 79% di «automazione» (Anthropic, «AI's Impact on Software
Development», 28 apr 2025) sotto i cartelli «quello che potremmo fare» / «quello che facciamo».*

**Perché è stata tagliata** - cinque motivi, in ordine di peso:

1. **Non serve.** La dicotomia automazione/complementarità è il **fatto n. 5 di Stanford** (slide 13),
   detto su dati di busta paga. Non ha bisogno di essere anticipata da un dato sui prodotti.
2. **Conclusione non sostenuta.** Il 79% misura *com'è fatta una conversazione*: modello esegue
   invece di collaborare. Sotto ci stava scritto «Sostituirle / Non assumerli più», che è un fatto di
   mercato del lavoro. Il ponte fra i due livelli non esiste.
3. **Ridondante con la slide 34.** «Gli strumenti hanno un default» lo dimostra molto meglio l'RCT
   con i sei pattern d'uso, che per giunta misura l'effetto sull'**apprendimento**.
4. **Vecchia e non controllata.** Aprile 2025, Claude Code a una settimana dal lancio - 17 mesi prima
   del talk. E non è un confronto controllato: utenti e compiti diversi. Quasi tautologico, per giunta:
   uno strumento progettato per agire risulta usato per agire.
5. **Vendor research senza l'attenuante.** L'RCT alla slide 33 regge perché il risultato è *contro*
   l'interesse di chi lo pubblica. Il 79% è una statistica d'uso neutra sui propri prodotti: quella
   difesa non lo copre. Apiiro è stato tagliato per un criterio più severo di questo.

**Cosa è stato ricollocato**
- *«Oh shit, here we go again»* → titolo della **slide 19** (la scala coi pioli), dove il fatto è dimostrato.
- Le parole *automazione / complementarità* → le introduce la **slide 13** stessa.
- Il collegamento metodologico Anthropic↔Stanford → **munizione per il Q&A**, non una slide. Vedi slide 13.

---

# PARTE 1 · slide 6–21 - Cosa dicono i dati
*Obiettivo: dimostrare che il primo piolo della scala si è staccato, con dati amministrativi e non con aneddoti.*

## 6 - Stacco di parte

**Layout** - Card di sezione. **Testi** - `PARTE 1` / *Cosa dicono i dati*
**Visual** - Nessuno. **Nota** - «Niente aneddoti. Buste paga.»

---

## 7 - Lo studio che conta · **RIFINITA**

**Layout** - Occhiello, titolo, riga autori, blocco metodo.
**Testi**
- `LO STUDIO CHE CONTA` · *Canaries in the Coal Mine?* · sottotitolo: **Six Facts about the Recent Employment Effects of Artificial Intelligence**
- Brynjolfsson · Chandar · Chen - Stanford Digital Economy Lab · agosto 2026
- blocco metodo: `BUSTE PAGA ADP · 3,5–5 MILIONI DI LAVORATORI AL MESE · FINO A GIUGNO 2026`
  **«Per sapere chi lavora non lo chiedono a nessuno: lo leggono nei cedolini.»**
- tre parole in fila, dalle parole degli autori: **tempestività** · **granularità sul singolo lavoratore** · **verificabilità amministrativa**

**Visual** - Nessuno: è il bollino di qualità del dato che arriva dopo.
**Nota** - «La letteratura su questo tema fatica a tenere insieme tre cose: essere tempestiva, scendere al singolo lavoratore, ed essere verificabile. Questo studio le tiene tutte e tre, e per questo conta più degli altri.»
Poi il perché profondo: **una busta paga non nasce per misurare, nasce per pagare qualcuno.** Un questionario si può sbagliare a compilare, si può non rispondere, si può ricordare male. Un cedolino no: se ci sei, sei stato pagato.
⚠️ **Non dire «non è un sondaggio» e basta.** Vale per **come contano le persone**, non per come classificano l'esposizione - quella è un giudizio prodotto da un modello (vedi slide 8). Se lo dici senza distinguere, ti si può smontare la slide con una domanda.
⚠️ **Il prezzo del sottoprodotto:** ADP non è l'economia americana. Il campione *«overrepresents the manufacturing and wholesale sectors»*, ed è la ragione per cui gli effetti sono più marcati che nei benchmark nazionali (torna alla slide 12). Lo scambio da dire in aula: **precisione e velocità in cambio di rappresentatività**; un sondaggio nazionale fa il contrario.

---

## 8 - Le due metà dello studio · **NUOVA** *(sostituisce l'imbuto)*

> Questa slide risponde alla domanda che si fa chiunque segua davvero: **le buste paga dove entrano?**

**Layout** - Due colonne che convergono su un blocco centrale. Sinistra = l'esito, destra = il raggruppamento, in mezzo la giuntura.

**Testi**
- occhiello: `DUE METÀ, UNA GIUNTURA`

**Colonna sinistra - `DALLE BUSTE PAGA: L'ESITO`**
- **Chi è occupato, mese per mese.** Occupazione = *worker-firm match*: comparire nella busta paga di quell'azienda quel mese. *(Meno dello 0,1% ha due impieghi full-time nel campione.)*
- **L'età** - anno di nascita *(la data esatta non la vedono, per privacy)*
- **La retribuzione base annua** *(serve al fatto n. 6)*
- il campione: **26 milioni** di lavoratori nelle imprese servite da ADP → **3,5–5 milioni al mese** nell'analisi · solo **full-time**, retribuzioni positive, under 70 · **panel bilanciato**: solo imprese presenti ogni mese da gen 2021 a giu 2026, così le variazioni non sono ADP che guadagna o perde clienti

**Blocco centrale - `LA GIUNTURA: IL CODICE SOC`**
- la busta paga dà *job title → SOC* · la misura di esposizione dà *SOC → punteggio*
- **oltre 7.000 job title** standardizzati mappati su SOC 2010 dalla tassonomia interna ADP
- ⚠️ il titolo **manca per circa il 30%** del campione: lo riempiono col codice precedente (o successivo) **dello stesso lavoratore**. Gli autori dichiarano che *«the descriptive facts are largely insensitive to the imputation»*

**Colonna destra - `DA FUORI: IL RAGGRUPPAMENTO`**
- **Nessuna busta paga qui.** L'esposizione è un giudizio su **com'è fatto il mestiere**, prodotto da un modello su descrizioni di compiti.
- **O*NET valutato da GPT-4** (Eloundou et al. 2024, misura β) e **quota di query a Claude** (Anthropic Economic Index) → punteggio per professione → **quintili** *(→ slide 9)*

**Visual** - **Schema a Y rovesciata**: due colonne che scendono e si incontrano su un badge centrale `SOC 2010`. A sinistra l'icona di un cedolino, a destra quella di un documento di testo. Sotto la giuntura, una freccia sola verso il basso: *«ora si possono confrontare».*
**Nota** - «La cosa difficile da misurare - se una persona è occupata - la prendono dalle buste paga, e lì non si discute. La cosa opinabile - se un mestiere è esposto all'AI - la misurano in **due modi indipendenti**, e poi rifanno tutto con altre **cinque** misure alternative. Il risultato tiene in tutti i casi.»
↳ Detta così, la slide **anticipa e disinnesca** l'obiezione invece di subirla. Non nascondi il fianco molle: mostri che gli autori l'hanno coperto.

**Footer** - *Canaries in the Coal Mine?*, ago 2026 - Sezione 2 e Data Appendix

---

## 9 - Cosa vuol dire «esposto» · **NUOVA**

**Layout** - Barra a cinque segmenti in alto (Q1→Q5, gradiente, Q5 acceso); sotto due colonne di professioni vere affiancate; in fondo una riga di avvertenza.
**Testi**
- occhiello: `NON SONO LE PERSONE. SONO I MESTIERI.`
- **Nei quintili ci vanno le professioni** - codici SOC. Si assegna a ogni professione un punteggio di esposizione, si ordina, si taglia in cinque.

| `QUINTILE 1 · MINIMA ESPOSIZIONE` | `QUINTILE 5 · MASSIMA ESPOSIZIONE` |
|---|---|
| Facchini e movimentatori merci | **Chief Executives** |
| Addetti alle pulizie domestiche | Addetti al servizio clienti |
| Operatori di muletti e trattori | Manager, tutti gli altri |
| Addetti a macchine confezionatrici | Contabili |
| Manutentori del verde | Specialisti risorse umane |
| Operatori di presse metallo/plastica | Rappresentanti commerciali |
| Bidelli e addetti alle pulizie | **Sviluppatori software, sistemi** |
| Assistenti domiciliari | Manager sistemi informativi |

- riga finale, in ambra: **«Esposizione non è adozione. Nessuno ha misurato chi usa l'AI: hanno misurato di cosa è fatto il lavoro.»**

**Visual** - Le due colonne **sono** il visual: a sinistra mani e corpo, a destra scrivanie. *Software Developers* marcato nella colonna di destra; nella barra in alto il quinto segmento acceso.
**Nota** - «Guardate la colonna di destra e ditemi se vi sembra la lista dei lavori che stanno per sparire. Il primo è l'amministratore delegato.» (pausa) «Non è una classifica di chi è sacrificabile. È una classifica di **quanto il tuo lavoro assomiglia a del testo**.»
↳ Semina qui la faglia che raccoglierai alla **13**: non passa fra lavori alti e bassi, ma fra conoscenza codificata e conoscenza tacita.

**Come si ottiene il punteggio - due misure indipendenti:**
1. **Eloundou et al. 2024, il «β su GPT-4»** - regge i risultati principali. Valutano **compito per compito** il database O*NET, stimando quanto ogni task sia aggredibile da un LLM, con GPT-4 validato da umani; poi aggregano i task fino alla professione (SOC 2018).
2. **Anthropic Economic Index** - quante query reali a Claude riguardano i compiti di quella professione, **divise per quante persone ci lavorano**: così una professione non risulta esposta solo perché è grande. Da qui ricavano anche i due tagli separati, «automative» e «augmentative».

⚠️ **Precisione obbligatoria:**
- Le tabelle A.2–A.6 elencano le professioni **per numero di occupati in ADP**, non per esposizione. *«Software Developers è la 7ª»* = 7ª **per occupati** dentro il quintile 5, **non** 7ª più esposta.
- Sul taglio «automation» dell'indice Anthropic i quintili **non sono cinque**: oltre il 20% delle professioni sopra la soglia di query ha quota di automazione pari a 0, quindi Q1 e Q2 vengono fusi e restano **quattro livelli**.
- Le professioni i cui task stanno tutti sotto la soglia minima di query sono una **categoria a parte, codificata 0** - non sono nei quintili.
- ❓ **Da verificare se vuoi spiegarlo a fondo:** cosa distingua il **β** dalle altre misure di Eloundou non è scritto in questo paper - lo chiama solo *«susceptibility of O*NET tasks to LLM automation»*. Serve andare sul paper di Eloundou et al. 2024.

**Footer** - Eloundou et al. 2024 (GPT-4 β) · Anthropic Economic Index (Handa et al. 2025) · Tab. A.2–A.6

---

## 10 - Il divario · **RIFATTA** *(via il grafico a forbice)*

**Layout** - Una colonna, molto bianco. Numero enorme in alto, frase sotto, filetto, riga di controllo in fondo.
**Testi**
- occhiello: `FATTO N. 2 DI SEI`
- il numero, grande quanto può stare: **19%**
- sotto: «È quanto **manca** ai ventidue-venticinquenni nei mestieri più esposti all'AI, rispetto a dove sarebbero **se avessero tenuto il passo dei coetanei nei mestieri meno esposti**.»
- dopo il filetto: «Negli stessi mestieri, chi ha **esperienza**: nessun divario.»

**Visual** - **Nessuno.** Il numero è il visual.
🗑️ **Eliminato il grafico a forbice.** Due rette dritte disegnavano una traiettoria che non è stata misurata - il paper dà due estremi e un confronto controfattuale, non un percorso. Tanto che la slide portava una didascalia che smentiva il proprio grafico. In più la forbice non mostrava né il controfattuale né il controllo sull'età, cioè le due cose che rendono il fatto interessante.
**Nota** - «Attenzione a come è costruito questo numero, perché è più sottile di come lo racconteranno i giornali. **Non vuol dire che il 19% dei giovani ha perso il lavoro.** Vuol dire che non sono arrivati: mancano all'appello rispetto a dove li avrebbe portati il semplice tenere il passo dei loro coetanei.»
(pausa) «E la riga sotto è quella che rende la cosa interessante davvero: **negli stessi identici mestieri, chi ha esperienza non ha nessun divario.** Quindi non è un settore che va male. È l'ingresso che si è ristretto.»
⚠️ **−11% / +10% e 19% sono lo stesso fatto detto in due modi** - i primi sono i livelli, il secondo il divario relativo. Non sommarli, non citarli insieme senza spiegare. La stima di regressione per il quintile più esposto è **−0,193**, coerente col 19%. Non usare il vecchio «16%».
**Footer** - *Canaries in the Coal Mine?*, ago 2026 - fatto n. 2

---

## 11 - Non licenziati. Non svenduti. · **RIFATTA** *(era «Fatto n. 4»)*

**Layout** - Due negazioni affiancate, grandi, con una riga di spiegazione ciascuna. Sotto, separata da un filetto, la conclusione.
**Testi**
- occhiello: `FATTI N. 4 E N. 6`
- **NON LICENZIATI** - «Il divario passa per la **riduzione delle assunzioni**, non per un aumento dei licenziamenti.»
- **NON SVENDUTI** - «L'aggiustamento avviene sull'**occupazione**, non sulla retribuzione. La paga d'ingresso dei giovani non mostra relazione evidente con l'esposizione.»
- dopo il filetto, in ambra: **«Il mercato si è aggiustato sulla quantità, non sul prezzo.»**

**Visual** - Nessuno. Le due negazioni in grande *sono* il visual: due porte chiuse, tipograficamente.
**Nota** - «Nessuno vi ha licenziato. Semplicemente la porta non si è aperta. Ed è per questo che non fa notizia: un licenziamento è un evento, una mancata assunzione è un **non-evento**. Non c'è niente da fotografare.»
(pausa, poi la seconda) «E non è nemmeno che i giovani costino meno. Se il mercato si fosse aggiustato sul **prezzo**, i ragazzi entrerebbero lo stesso, pagati meno. Non è andata così: **entrano di meno, e chi entra è pagato come prima.**»
↳ **Questa è la scala coi pioli detta in linguaggio economico**, sette slide prima di mostrarla: la differenza fra «il piolo si è abbassato» e «il piolo non c'è più». Alla slide 19 il pubblico l'ha già capito e tu devi solo dargli l'immagine.
⚠️ La retribuzione osservata è solo la **base**: esclude bonus, straordinari, provvigioni, mance ed **equity** - voci che il paper dice essere *«largest in precisely the most exposed, high-income occupations»*. Un aggiustamento sul prezzo potrebbe esserci e non essere visto. Dillo tu.
⚠️ Fra chi resta nella stessa azienda la paga base è cresciuta un po' più lentamente nei mestieri esposti, ma **non specificamente per i giovani**, e sono differenze piccole rispetto ai venti punti di divario occupazionale.
**Footer** - *Canaries in the Coal Mine?*, ago 2026 - fatti n. 4 e n. 6

---

## 12 - I limiti, detti da me prima che me li diciate voi

**Layout** - Citazione in alto, tre colonnine sotto. *(invariata)*
**Testi** - «We interpret these facts as **early, descriptive indicators** - canaries in the coal mine - **rather than causal estimates**.» + le tre avvertenze (pre-trend attorno al COVID · l'effetto si attenua controllando per il titolo di studio · il campione ADP è più marcato dei benchmark nazionali)
**Visual** - Nessuno.
**Nota** - Quindici secondi, non saltarla. Fa da cerniera: finisce l'allarme, comincia la sfumatura. «Non vi sto dicendo che l'AI ha causato questo. Vi sto dicendo che il canarino ha smesso di cantare.»

---

## 13 - Dove succede: sostituire o complementare

**Layout** - Due pannelli affiancati in alto, due colonne di testo sotto. *(invariata)*
**Testi** - **DOVE L'AI SOSTITUISCE** → occupazione giovanile **in calo** | **DOVE L'AI COMPLEMENTA** → **piatta o in crescita**, soprattutto fra gli esperti · `CONOSCENZA CODIFICATA` **sostituibile** | `CONOSCENZA TACITA` **resiste**
**Visual** - Le due card contrapposte.
**Nota** - Fatto n. 5, quello che non fa clickbait. «La stessa tecnologia, usata in due modi, produce disoccupazione o produttività. E la differenza la fa come la usi - cioè qualcosa che si può insegnare.»
↳ Questa slide **introduce da sola** la coppia *automazione / complementarità*: non c'è più la semina della slide tagliata.
📌 **Q&A, non da dire a slide.** Come fa Stanford a sapere dove l'AI sostituisce? Usa l'**Anthropic Economic Index** e la sua classificazione automative/augmentative - nota 40: *«Directive and Feedback Loop conversations are considered Automative.»*
⚠️ **Non** dire «Stanford ha usato il 79%»: il ponte è la tassonomia, non quel numero.

---

## 14 - Cosa hanno già escluso · **NUOVA**

**Layout** - Tre barre orizzontali a confronto in alto; sotto, una riga di voci secondarie.
**Testi**
- occhiello: `PRIMA CHE LO PENSIATE VOI`
- titolo: *«Non è il post-COVID del tech.»*
- tre barre, stima del divario per i 22–25enni nel quintile più esposto:
  - campione pieno → **−0,193**
  - **tolte le occupazioni informatiche** (SOC 15-1xxx) → **−0,190**
  - **tolte le aziende tech** (NAICS 51 e 5415) → **−0,166**
- riga sotto: regge anche controllando per **esposizione ai tassi d'interesse**, per **telelavoro**, e su **cinque misure alternative** di esposizione all'AI
- citazione in piccolo: *«These results indicate that our findings are **not specific to technology roles**.»*

**Visual** - **Tre barre praticamente identiche.** È tutto il senso della slide: si vede a colpo d'occhio che togliendo il tech non cambia niente.
**Nota** - «L'obiezione ovvia è: ma questo è solo il rimbalzo del tech dopo il COVID, le aziende avevano assunto troppo nel 2021 e hanno frenato. Gli autori ci hanno pensato. Hanno rifatto tutto togliendo le occupazioni informatiche: da diciannove virgola tre a diciannove virgola zero. Poi togliendo proprio le aziende tech: sedici e sei. Regge.»
↳ **Funzione nel talk:** toglie alla sala l'alibi «è roba nostra, è il ciclo del settore». E prepara il passaggio successivo, perché sposta la domanda da *«quanto soffre il tech?»* a *«cosa succede al lavoro d'ingresso in generale?»*.
**Footer** - *Canaries in the Coal Mine?*, Online Appendix Tab. C.1 e Fig. C.4–C.5

---

## 15 - E allora gli sviluppatori? · **NUOVA**

**Layout** - Due blocchi: sopra la collocazione nei quintili, sotto l'anomalia salariale.
**Testi**
- occhiello: `DOVE SIAMO NOI, IN QUESTA STORIA`
- blocco 1 - cinque blocchetti in fila, il quinto acceso: *Software Developers, Systems Software* è la **7ª occupazione più grande del quintile 5**, il più esposto. *Computer Programmers*: 34ª. **Non siamo un esempio: siamo dentro il campione.**
- blocco 2 - **L'anomalia**: la retribuzione dei 22–25enni sviluppatori è cresciuta **più in fretta** che per i colleghi più anziani dopo ChatGPT.
- la spiegazione degli autori, citata: *«rising relative pay may partly reflect **composition effects if firms primarily contracted hiring of lower-paid engineers**»*

**Visual** - La fila di cinque quintili con il quinto evidenziato; accanto, due frecce divergenti: **assunzioni ↓ / paga d'ingresso ↑**.
**Nota** - «Sembra una buona notizia e non lo è. I giovani sviluppatori che entrano sono pagati relativamente meglio. Perché? L'ipotesi degli autori è che le aziende abbiano smesso di assumere quelli **sotto** - i meno pagati, cioè i meno esperti. Chi entra oggi entra più in alto.»
(pausa) «Questo non è un grafico sulle retribuzioni. È la scala coi pioli, misurata in euro.»
⚠️ **Quattro cautele, tutte da dire.**
**La più seria:** è un dato di **retribuzione base**, e il paper avverte che la base *«excludes bonuses, overtime pay, commissions, equity, and tips - components that are largest in **precisely the most exposed, high-income occupations**, and through which compensation adjustment could occur unobserved»*. Per gli sviluppatori l'equity è una fetta enorme del pacchetto: la parte dove l'aggiustamento sarebbe più probabile è proprio quella che **non vedono**. Di' «di stipendio base», sempre. È una **nota a piè di pagina** del paper, non un risultato principale. Gli autori la chiamano *«an idiosyncratic pattern for software developers»* - aggregando per quintili l'effetto non c'è. E propongono **due** spiegazioni: la composizione *oppure* uno shock negativo di offerta. Dillo come ipotesi, non come fatto.
**Footer** - *Canaries in the Coal Mine?*, ago 2026 - nota 22 e Online Appendix Fig. G.1–G.2

---

## 16 - Il riassunto · **NUOVA**

> Atterraggio del blocco Stanford. **È la slide che il pubblico fotografa**: deve reggere da sola, fuori contesto, sul telefono di qualcuno la sera.

**Layout** - Una colonna a piena larghezza. Cinque blocchi di prosa, uno per frase, separati da spazio generoso - non elenco puntato, non numerato: testo disteso, come una dichiarazione. Corpo più piccolo del resto del deck, ma non piccolo.
**Testi** - occhiello: `IN CINQUE RIGHE`

> Ci sono mestieri più esposti all'AI - misurati su **com'è fatto il lavoro**, non su chi usa l'AI.
>
> In quei mestieri l'occupazione dei **ventidue-venticinquenni è indietro del 19%** rispetto ai coetanei nei mestieri meno esposti, e il meccanismo sono le **mancate assunzioni**, non i licenziamenti.
>
> Le retribuzioni non si sono mosse: l'aggiustamento è sulla **quantità**, non sul **prezzo**.
>
> Per i lavoratori **esperti** non c'è un divario comparabile - anzi, dove l'AI complementa, l'occupazione tiene o cresce, soprattutto per loro.
>
> Gli **sviluppatori** stanno dentro il quintile più esposto, e per loro c'è un'anomalia in più: la paga dei ventidue-venticinquenni è cresciuta più in fretta, forse perché hanno smesso di assumere i meno pagati.

**Visual** - Nessuno, e deliberatamente: il testo è il contenuto. Unico accento grafico, i grassetti, che servono a far navigare l'occhio di chi la rilegge in una foto.
**Nota** - **Questa è la slide da fotografare, e va gestita come tale.** Non leggerla tutta ad alta voce: il pubblico non può ascoltare e leggere insieme. Dì una frase sola - «se di tutto questo blocco vi resta una slide, è questa» - e poi **stai zitto sei o sette secondi**. Lascia che tirino fuori il telefono. Poi riprendi.
Se vuoi dire qualcosa mentre scattano, la frase giusta è la terza: «guardate la riga di mezzo. **Non li hanno pagati meno. Non li hanno presi.**»
↳ **Transizione a voce**, non sulla slide - così resta pulita per la foto. Qui non si passa più all'Italia (spostata alla 20): si passa alle **persone**. Proposta: «Questi sono numeri su buste paga. Le due slide che seguono sono su chi quelle buste paga le aspettava.» ⏳ *da confermare*
⚠️ **È la slide più densa del deck**, di parecchio. Al primo render va guardata con attenzione: se sfora, si riduce il corpo, **non si tagliano le frasi** - la completezza è il motivo per cui esiste.
⚠️ Su «sviluppatori» non allargare: il paper **non li isola**. La formulazione «stanno dentro il quintile più esposto» è precisa e va tenuta com'è.
**Footer** - *Canaries in the Coal Mine?*, Brynjolfsson · Chandar · Chen, Stanford Digital Economy Lab, ago 2026

---

## 17 - I ragazzi l'hanno già capito

**Layout** - Due numeroni affiancati in alto, blocco metodo sotto.
**Testi**
- **70%** dei laureandi in informatica è **pessimista** sulla propria carriera; il 64% dei pessimisti indica la GenAI.
- **42%** la usa **ogni giorno** (media degli altri laureandi: 24%).
- metodo: iscrizioni a informatica primavera 2026 **−8,4%** atenei quadriennali, **−11,2%** biennali; iscrizioni totali **+1,3%**; persistenza al secondo semestre la più bassa fra i dieci corsi principali.

**Visual** - Nessuno; i due numeri grandi reggono la slide.
**Nota** - «Sono contemporaneamente i più spaventati dall'AI e quelli che la usano di più. Provate a immaginare di studiare così. Io non devo immaginarlo: ce li ho in aula.»
⚠️ Sondaggio Handshake sui propri utenti, campione non dichiarato: attribuire con precisione.

---

## 18 - IBM triplica le assunzioni entry-level

**Layout** - Occhiello + titolo, citazione, blocco metodo.
**Testi**
- `FEBBRAIO 2026 · IL CONTRO-TREND` · *IBM triplica le assunzioni entry-level*
- citazione LaMoreaux: «Le aziende che tra tre-cinque anni avranno più successo sono quelle che **hanno raddoppiato sulle assunzioni entry-level** in questo periodo.»
- blocco: «Non hanno solo assunto di più. Hanno riscritto il ruolo. Meno coding di routine → più contatto col cliente e **validazione degli output dell'AI**. Il senior fa evaluation, pattern recognition, e insegna ai giovani a esercitare il giudizio.»

**Visual** - Nessuno.
**Nota** - La motivazione è cinica nel modo giusto: chi taglia i junior oggi tra tre anni non ha i mid-level e deve comprarseli dai concorrenti.
⚠️ È una dichiarazione, non un dato: «hanno detto che». Nessuna cifra assoluta diffusa.

---

## 19 - Nessuno ha tolto la scala

**Layout** - Due colonne: disegno a sinistra, titolo grande a destra.
**Testi** - occhiello: `OH SHIT, HERE WE GO AGAIN` *(ereditato dalla slide tagliata: qui il fatto è dimostrato e la battuta è meritata)* · *Nessuno ha tolto la scala.* / *Hanno tolto i primi pioli.* (seconda riga in rosso)
**Visual** - **Scala a pioli disegnata.** Due montanti verticali; i quattro pioli alti sono pieni, i tre più bassi sono tratteggiati e sbiaditi, con l'etichetta «i primi pioli». Pallino verde in cima, pallino rosso in fondo.
**Nota** - Punto di svolta del talk, rallentare. «La seniority non si compra e non si scarica: si costruisce facendo il lavoro da junior. Il CRUD noioso, il bug stupido cercato per tre ore, la code review in cui ti massacrano. Erano i pioli.» E: «Non è un problema dei giovani. È un problema di chi tra dieci anni avrà bisogno di qualcuno che sappia guardare 50.000 righe generate e dire "no, qui c'è qualcosa che non va".»
↳ **Transizione all'Italia**, a voce, dopo la pausa: «Questi però sono dati americani. E qui?» - arrivata qui dalla 16 quando il blocco italiano è stato spostato in fondo alla parte.
> ⚠️ **Aperta:** sul tema chiaro il disegno risulta piccolo rispetto al titolo accanto. Opzioni: ingrandirlo, o slide a piena larghezza col titolo sopra.
> ⚠️ **La nota dice «punto di svolta, rallentare»** - resta vero, ma la 19 **non chiude più la parte**: dopo ci sono l'Italia e il passaggio. Non calcare come se fosse l'ultima parola.

---

## 20 - E in Italia? · **RIFATTA DA ZERO**

**Layout** - Titolo, tabella a tre colonne (misura · laureati 2023 · laureati 2025), sotto una riga separata per Excelsior.
**Testi**
- occhiello: `LA DOMANDA OVVIA`
- titolo: *E in Italia?* **Non si vede.**
- tabella - **laureati in informatica e tecnologie ICT**, stesso modello di regressione in due edizioni AlmaLaurea:

| | laureati **2023** | laureati **2025** |
|---|---|---|
| probabilità di essere occupati a 1 anno *(odds ratio)* | 4,74 | **4,86** |
| premio retributivo mensile netto | +184 € | **+222 €** |

*A parità di ogni altra condizione, rispetto al gruppo politico-sociale e comunicazione.*

- riga sotto, separata: **Excelsior** - *tecnici programmatori*: **65%** di difficoltà di reperimento. *Analisti e progettisti di software*: fra le professioni più introvabili d'Italia.

**Visual** - La tabella è il visual. Due frecce a destra: **→ stabile** sull'occupabilità, **↑ in salita** sulla retribuzione. Nessun grafico.
**Nota** - «Vi ho appena mostrato dieci minuti di dati americani, quindi la domanda ovvia è: e qui? **E qui non si vede.** Non un calo attenuato: nessun calo.»
«Ho preso lo stesso identico modello di regressione in due edizioni di AlmaLaurea - laureati del 2023 e laureati del 2025, cioè esattamente a cavallo dell'arrivo dell'AI generativa. L'occupabilità è ferma, semmai su di un soffio. Il premio di stipendio è **salito di quaranta euro al mese**.»
«E dall'altro lato Excelsior dice che i programmatori non si trovano: due terzi delle posizioni sono difficili da coprire.»
⚠️ **Cosa NON dice questo dato.** È un confronto **fra gruppi disciplinari**, non nel tempo assoluto: dice che informatica va meglio di scienze politiche, non che va meglio di come andava. Se tutti i gruppi fossero peggiorati insieme questa misura non lo vedrebbe - ma l'occupazione complessiva dei laureati a un anno è **salita** (81,2%), quindi un crollo generale nascosto non c'è.
⚠️ AlmaLaurea rileva **a un anno dal titolo**, una volta l'anno, sui laureati degli atenei consorziati. Excelsior misura **intenzioni dichiarate dalle imprese**, non assunzioni avvenute. Dillo tu.
**Footer** - AlmaLaurea, Rapporti 2026 e 2024 (XXVIII e XXVI Indagine) · Excelsior–Unioncamere, banca dati professioni

---

## 21 - Tre spiegazioni, nessuna rassicurante · **NUOVA**

**Layout** - Tre blocchi numerati, brevi. Sotto, separata da un filetto, la frase di chiusura, grande.
**Testi**
- occhiello: `PERCHÉ NON SI VEDE`

1. **Siamo indietro.** L'adozione dell'AI nelle aziende italiane è più lenta. L'effetto deve ancora arrivare.
2. **Il nostro mercato è diverso.** Partiamo da una carenza di informatici così profonda che l'AI la attenua invece di creare disoccupazione.
3. **Non lo stiamo misurando.** Non abbiamo nulla di paragonabile ad ADP: nessun dato amministrativo per professione ed età ad alta frequenza.

- dopo il filetto, in ambra: **«Il canarino americano lo sentiamo cantare. Il nostro non sappiamo nemmeno se è nella miniera.»**

**Visual** - Nessuno. Tre numeri e una frase.
**Nota** - «Le spiegazioni possibili sono tre, e non ve ne scelgo una perché non lo so - e non lo sa nessuno.» Dille tutte e tre alla stessa velocità: se ne calchi una sola sembra che tu abbia una tesi.
Poi la chiusura, piano: la terza riguarda te che insegni e loro che assumono. **Non è una buona notizia che non si veda: è che non abbiamo lo strumento per guardare.**
↳ **È l'unico momento del talk in cui dici «non lo so» con i dati in mano.** Dopo dieci minuti di rigore, è il punto in cui la sala decide che sei credibile. Non sprecarlo scusandoti: dillo come un risultato, perché lo è.
⚠️ Non trasformarlo in ottimismo («in Italia siamo salvi») né in allarmismo («arriverà anche qui»). La frase onesta è: *non lo sappiamo, ed ecco perché.*

**🔑 IL PASSAGGIO - accorciato il 24 settembre.** Da dire subito dopo il canarino, senza pausa:
> «Non so dirvi se arriverà anche qui, e chi ve lo dice sta tirando a indovinare. Ma **la domanda non finisce qui.**»

↳ **Perché è corto.** Il blocco sul mercato del lavoro stabilisce l'urgenza, **non la tesi** - e senza una cerniera la sala esce pensando «e quindi? in Italia non succede niente». Basta però una frase: il ponte vero lo costruisce la **22**, che mette in fila cosa sappiamo e cosa no. Due transizioni di fila erano una di troppo.

---

# PARTE 2 · slide 22–24 - Cosa fa davvero la macchina
*Obiettivo: mostrare che il collo di bottiglia si è spostato dalla produzione alla verifica.*
*Il titolo raccoglie la seconda spiegazione della 21 - «l'AI attenua la carenza di informatici» - e ne fa una domanda.*
*Nella spina dorsale del talk: Parte 1 = **quanto**, Parte 2 = **cosa**, Parte 3 = **dove**, Parti 4–6 = **come**.*

## 22 - Facciamo un punto · **RIFATTA** *(era la card di stacco)*

> Non c'è card di sezione: **questa slide è lo stacco**. È l'unica parte che rompe lo schema, e lo rompe dove il talk cambia marcia.

**Layout** - Piena larghezza, tre fasce orizzontali impilate in ordine di certezza calante. Occhiello `PARTE 2` in alto a sinistra.
**Testi** - titolo: *Facciamo un punto.*

**QUELLO CHE SAPPIAMO**
- Ci sono mestieri più esposti - misurati su **com'è fatto il lavoro**.
- Lì i **22-25enni non vengono assunti**. Non licenziati, non pagati meno.
- Sui lavoratori **esperti** non succede.

**QUELLO CHE NON SAPPIAMO**
- In Italia non si vede. E non sappiamo se perché non succede o perché **non stiamo guardando**.

**QUELLO CHE NON ABBIAMO NEMMENO GUARDATO**
- Tutto questo misura un **effetto**. Nessuno di questi numeri dice **cosa la macchina faccia davvero al lavoro.**

**Visual** - Le tre fasce sono il visual. Filetto colorato a sinistra: verde pieno, ambra, rosso; la terza è l'unica aperta sul fondo, con una freccia che scende dentro la parte. Deve leggersi in tre secondi che la certezza scende mentre si scende.
**Nota** - «Prima di andare avanti mettiamo in fila quello che ho in mano.» Le prime tre righe **veloci**: è un atterraggio, non una lezione. Se senti la sala che rilegge, hai sbagliato ritmo.
Poi il pezzo che vale la slide, lento: «Vi ho dato una correlazione con un meccanismo plausibile. Ma il meccanismo non l'ho mai guardato in faccia - me lo sono fatto raccontare da un codice di classificazione e da un modello che stima l'esposizione leggendo le mansioni. **Adesso lo guardiamo.**»
↳ **Perché apre la parte.** Non afferma niente di nuovo: ricapitola e lascia un buco. La Parte 2 diventa un debito che paghi, non un argomento nuovo.
⚠️ **Non deve diventare la 16.** Quella riassume lo studio e si fotografa; questa fa il bilancio della parte. La colonna «sappiamo» resta a **tre righe** anche se viene voglia di aggiungerne.
⚠️ «Il codice è gratis» **non è più un titolo**: resta una mezza frase concessa dentro la parte - alla 24 i 36 milioni di nuovi sviluppatori lo dimostrano da soli.
📌 **Q&A:** se qualcuno contesta la causalità, il limite l'hai ammesso tu dal palco.

---

## 23 - La sicurezza

**Layout** - Due colonne: numerone a sinistra, metodo + quattro card + due righe a destra.
**Testi**
- **~50%** del codice generato **non supera i test di sicurezza**
- metodo: `100+ MODELLI · 80 TASK STANDARDIZZATI · 4 LINGUAGGI` - «Rimisurato a ogni ciclo. Chiunque può rifarlo.»
- per linguaggio: JAVA **72%** · C# **45%** · JS **43%** · PYTHON **38%**
- **XSS:** i modelli falliscono nell'**86%** dei casi rilevanti
- **Invariato da un anno e mezzo.**

**Visual** - Quattro card compatte con il tasso per linguaggio.
**Nota** - «Il punto non è il numero in sé, è che non si muove: i modelli sono migliorati in tutto, tranne che qui.»
Poi **il limite, detto da te prima che te lo chiedano**: «Attenzione a cosa misura: è l'output grezzo del modello, non il codice che va in produzione dopo una review. **Questo è quello che la macchina produce da sola. Quanto ne arriva in produzione dipende da chi c'è in mezzo.**»
↳ Quella frase è il ponte verso la 24 e verso l'atterraggio della parte: se il filtro è chi c'è in mezzo, il collo di bottiglia è la **verifica**.
⚠️ Dire «circa la metà, invariato». Veracode 2025 dà 45%; l'aggiornamento 2026 ragiona in tassi di superamento, valori fra 45% e 55%: non sovrapponibili.
⚠️ I quattro numeri per linguaggio (72 / 45 / 43 / 38) vengono **solo dal report 2025**: l'aggiornamento 2026 non li ripubblica nella stessa forma.
**Footer** - `Veracode GenAI Code Security Report 2025 · aggiornamento primavera 2026 · veracode.com/blog/genai-code-security-report`
📎 [report 2025](https://www.veracode.com/blog/genai-code-security-report/) · [primavera 2026](https://www.veracode.com/blog/spring-2026-genai-code-security/) - ✅ applicato al Marp il 25 settembre

---

## 24 - Il combinato disposto

**Layout** - Tre affermazioni impilate, poi la conclusione separata da un filetto.
**Testi**
- **36 milioni** di nuovi sviluppatori su GitHub in un anno. Quasi l'**80%** usa Copilot **entro la prima settimana**.
- **Circa la metà** del codice generato non supera i test di sicurezza - e non migliora da un anno e mezzo.
- Più sviluppatori **diffidano** dell'accuratezza degli strumenti AI (**46%**) di quanti se ne **fidano** (**33%**). E fra gli **esperti** lo scetticismo è più netto: si fida molto il **2,5%**, diffida molto il **20,7%**.
- conclusione (in ambra, serif): **«Produrre non è più il collo di bottiglia. Verificare sì.»**

**Visual** - Nessuno. La conclusione è la grafica.
**Nota** - Sui tre fatti: «Non i nostalgici: quelli che lo usano meglio. Il 2,5% degli esperti si fida molto, il 20,7% diffida molto.» Poi la conclusione, lenta: è **l'atterraggio della parte**, e consegna alla Parte 3 - se il collo di bottiglia è la verifica, il mestiere si sposta lì.
⚠️ **Chiusura cambiata il 24 settembre.** Prima era «stiamo formando una generazione che si fida di più proprio dello strumento di cui gli esperti si fidano di meno - senza darle gli strumenti per verificarlo». È una frase sull'**insegnare**, non sul mercato: anticipava la tesi e lasciava la parte senza dire cosa aveva dimostrato. **Spostata all'apertura della Parte 5**, dove il tema è quello.
⚠️ «Il codice è gratis» non si afferma: i 36 milioni di nuovi sviluppatori lo dimostrano da soli. Al massimo una mezza frase di passaggio.
⚠️ **Errore corretto il 25 settembre.** La riga diceva «gli sviluppatori **esperti** sono quelli che se ne fidano meno: diffida il 46%, si fida il 33%». Il **46/33 è tutta la popolazione** della Developer Survey, non gli esperti; il dato sugli esperti è **2,5% / 20,7%** (si fida molto / diffida molto). Erano due misure diverse fuse in una frase. La formulazione ora usata è quella di Stack Overflow alla lettera: *«More developers actively distrust the accuracy of AI tools (46%) than trust it (33%)»*.
⚠️ Niente delta col 2024: i dati 2024 non sono nel report 2025.
📎 Octoverse 2025 · Veracode 2025 · [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) - sezione *Accuracy of AI tools*

---

# PARTE 3 · slide 25–28 - Dove va a finire il mestiere
*Obiettivo: dare una cornice concettuale (non nostalgica) a cosa resta di umano.*

## 25 - Stacco di parte
**Layout** - Card di sezione. **Testi** - `PARTE 3` / *Dove va a finire il mestiere*

---

## 26 - Software 3.0

**Layout** - Tre righe da tabella, poi una citazione.
**Testi**
- `SOFTWARE 1.0` → scrivi **codice** · `SOFTWARE 2.0` → alleni **pesi** · `SOFTWARE 3.0` → scrivi **contesto** *(prompt, esempi, tool, memoria, istruzioni)*
- citazione Karpathy: «Programming shifts from writing code to **writing context**.»

**Visual** - Nessuno; la progressione 1.0 → 3.0 è la grafica.
**Nota** - «Quello che ci resta è dire con precisione a una macchina cosa vogliamo. Che è, se ci pensate, la definizione di programmare che avevamo prima che esistessero i linguaggi di programmazione.»
**Attribuzione** - La tassonomia è **di Karpathy**, non tua: *Software 2.0* è un suo post del **2017**, *Software 3.0* è suo dal 2025 e ripreso al **Sequoia Ascent, maggio 2026** («From Vibe Coding to Agentic Engineering»). Tua è solo la messa in fila a tre righe. Dillo a voce - «la tassonomia è sua» - costa due secondi e ti copre.
**Footer** - `Andrej Karpathy · From Vibe Coding to Agentic Engineering · Sequoia Ascent, mag 2026 · karpathy.bearblog.dev/sequoia-ascent-2026`
📎 [note di Karpathy](https://karpathy.bearblog.dev/sequoia-ascent-2026/) · [trascrizione](https://singjupost.com/andrej-karpathy-from-vibe-coding-to-agentic-engineering-w-stephanie-zhan-transcript/)

---

## 27 - Pavimento e soffitto

**Layout** - Due colonne: schema a sinistra, due paragrafi a destra.
**Testi**
- **Vibe coding** alza il pavimento. *Chiunque può costruire software. Basta descrivere.*
- **Agentic engineering** alza il soffitto. *Specifiche, review, test, permessi, confini.*

**Visual** - **Schema pavimento/soffitto.** Due linee orizzontali, ciascuna con una freccia che spinge verso l'alto: in basso il pavimento (ambra, «vibe coding»), in alto il soffitto (verde, «agentic engineering»). Fra le due, una barra verticale con la didascalia «lo spazio fra i due si chiama ancora **ingegneria del software**».
**Nota** - «La distinzione più utile che ho trovato in tre anni. E non sono in competizione: il pavimento che si alza è una bellissima notizia.» Poi: «Il mio lavoro, e forse il vostro, è portare la gente dal pavimento al soffitto.»
⚠️ Non fare il nostalgico: qui deve passare che alzare il pavimento è una buona notizia.

---

## 28 - Le due frasi da portare a casa

**Layout** - Due citazioni impilate, molto respiro.
**Testi**
- **Karpathy 2026** - «Puoi delegare la memorizzazione delle API. Le decisioni sulla **forma del sistema** - identità, confini di sicurezza, integrità dei dati - restano umane.»
- **Naur 1985** - «Il programma non è il codice: è la **teoria** che i programmatori hanno in testa su come il codice rispecchia il mondo. Il codice senza la teoria è morto.»

**Visual** - Nessuno.
**Nota** - Quarantun anni di distanza. «Il codice generato da un LLM è codice senza teoria. A meno che qualcuno la costruisca leggendolo. E quel qualcuno deve saper leggere.» Battuta opzionale: «Nel 1985 Naur non aveva in mente Claude. Aveva in mente il vostro collega che si è licenziato a marzo.»

---

# PARTE 4 · slide 29–31 - Cosa resta da insegnare
*Obiettivo: da qui si smette di descrivere il problema e si risponde.*

## 29 - Stacco di parte
**Layout** - Card di sezione. **Testi** - `PARTE 4` / *Cosa resta da insegnare*

---

## 29-bis - «Programmi pensati per un'altra epoca» · **NUOVA** ⏳ *numero da assegnare*

**Layout** - Citazione a piena pagina, molto respiro. Attribuzione piccola sotto, a destra.
**Testi**
> «Molti sistemi formativi faticano ad aggiornarsi al ritmo dei cambiamenti [...]. Lo sviluppo delle tecnologie informatiche e dell'IA rende rapidamente inadeguati **programmi di studio pensati per un'altra epoca**, mentre l'organizzazione della scuola, gli spazi, **i metodi di valutazione** e la stessa figura dell'insegnante chiedono di essere ripensati [...].»

- *Leone XIV, «Magnifica Humanitas», §145*

**Visual** - Nessuno. La citazione è la slide.
**Nota** - **Rivendica la mossa, non nasconderla:** «È l'unica dichiarazione che cito in tutto il talk. Non viene dalla Silicon Valley e non ha niente da vendermi.» Poi il gancio: «"I metodi di valutazione". È esattamente il punto - noi valutiamo ancora con *scrivi una funzione che…*.»
⚠️ **Tensione da gestire, non da ignorare.** Le slide 3–5 demoliscono l'argomento d'autorità (Jobs, Obama, Huang, Amodei). Qui ne usi uno. Funziona **solo** se lo dichiari: la differenza è il conflitto d'interessi, non il prestigio.
⚠️ È un'esortazione, non un dato. Non presentarla come prova: è la cornice del problema, la prova l'hai già data nelle Parti 1–2.
**Footer** - `Leone XIV, Magnifica Humanitas, 15 maggio 2026 · §145`
📎 [testo ufficiale, vatican.va](https://www.vatican.va/content/leo-xiv/it/encyclicals/documents/20260515-magnifica-humanitas.html) - ✅ verificato verbatim il 25 settembre 2026. Prima enciclica di Leone XIV, firmata il 15 maggio 2026; il §145 sta sotto «Centralità della scuola», sezione «Un'alleanza educativa per l'era digitale».

---

## ~~Cosa sta comprando davvero il mercato~~ · **TAGLIATA** *(era la 30)*

*Mostrava tre numeri sul mercato del lavoro italiano - 76% / 78% / 50,9% - in apertura della Parte 4.*

**Perché è stata tagliata:**
1. **Due numeri su tre non reggevano.** Il **78%** non esiste (è 75%, di un altro Osservatorio, e senza la qualificazione «AI, big data, cybersecurity»); il **76%** è vero ma senza denominatore fa capire l'opposto del vero - gli annunci con competenze AI sono l'1,4% del mercato.
2. **Ripeteva la Parte 1.** Le prove sul mercato del lavoro erano già state date venti minuti prima. Riproporle all'inizio della Parte 4 era il doppione che avevamo segnato.
3. **La Parte 4 non ne ha bisogno.** «Cosa resta da insegnare» è un argomento didattico: ci arriva meglio partendo direttamente da *Bloom, rovesciato*.

**Cosa resta:** il 50,9% di Excelsior era l'unico numero solido, ed è già citato altrove. Se un giorno servisse il 76%, va detto **insieme** al 27% CHRO e al 12% CMO dello stesso comunicato, che lo rendono onesto.

---

## 30 - Bloom, rovesciato

**Layout** - Due pannelli affiancati, PRIMA / ADESSO.
**Testi**
- **PRIMA**: *Creare* era la cima (difficile, costoso) - *Ricordare* e *capire* erano la base
- **ADESSO**: **Creare è gratis** - **Valutare e analizzare** sono il collo di bottiglia

**Visual** - Le due card contrapposte.
**Nota** - «Abbiamo costruito trent'anni di curricula che salgono dal basso: prima la sintassi, poi scrivi, poi - se c'è tempo, e non c'è mai - leggi e progetti. Quel percorso ha senso solo se scrivere è la parte difficile. Non lo è più.» E subito dopo: «Non significa "non insegniamo più a scrivere". Significa che scrivere non è più il traguardo: è il mezzo per costruire la capacità di giudicare.»
> 💡 **Possibile visual:** la piramide di Bloom capovolta - oggi è l'unica slide concettuale forte senza supporto grafico.

---

## 31 - La lista

**Layout** - Tabella a due colonne: la competenza a sinistra, il livello di Bloom a destra, allineato e in corpo piccolo. La colonna di destra riprende i colori della 30.
**Testi**

| | competenza | livello di Bloom |
|---|---|---|
| 1 | **Leggere** codice che non hai scritto | **Ricordare → Comprendere** |
| 2 | **Specificare** senza ambiguità | **Creare** |
| 3 | **Decomporre** un problema | **Analizzare** |
| 4 | **Debuggare** ciò che non hai scritto | **Applicare → Analizzare** |
| 5 | **Valutare** un output sicuro di sé anche quando sbaglia | **Valutare** |
| 6 | **Sapere quando fermarti** e non delegare | **Valutare** · *metacognizione* |

*Tutti e sei i livelli della tassonomia compaiono.* Le due frecce non sono un dettaglio: dicono che la competenza **attraversa** i livelli bassi, non li salta.

↳ **La colonna non è decorazione: è la dimostrazione della 30.** Le sei voci stanno tutte nella metà alta della tassonomia - comprendere, analizzare, valutare, creare.
↳ **Ricordare e applicare stanno dentro la lista, non fuori.** Non si legge codice senza ricordare cosa fa un'idiomatica; non si debugga senza applicare un metodo - riprodurre, isolare, bisezionare. Quello che è cambiato non è che servano meno: è che **hanno smesso di essere il traguardo e sono tornati a essere la strada**. La frase: «**Ci passate ancora attraverso tutti e sei. Solo che prima ci fermavamo ai primi due.**»
⚠️ Coerente con la 47 (*non li sai fare se non hai mai scritto codice*) e con la nota della 30 (*scrivere non è più il traguardo, è il mezzo*). Non dire mai «ricordare e applicare non servono più».
⚠️ **Il punto 2 va spiegato o crea confusione.** La 30 dice «creare è gratis», qui *specificare* è **Creare**. Non è una contraddizione, è la tesi: **creare il codice è gratis, creare la specifica no.** Se non lo dici, qualcuno in sala ci inciampa.
⚠️ Due voci su Analizzare e due su Valutare: è voluto, non un difetto della lista. Non riequilibrare per estetica.

**Visual** - Nessuno.
**Nota** - «Questa lista non è nuova. È LA lista: quello che abbiamo sempre detto di voler insegnare e che poi valutavamo con "scrivi una funzione che…". La differenza è che adesso non possiamo più fingere.»

↳ Sulla sesta voce - *sapere quando fermarti* - il §140 dell'enciclica dice la stessa cosa, ma **non va in slide**: si cita **a voce alla 37**, dove il tema è quello. Vedi lì.

---

# PARTE 5 · slide 32–37 - L'AI in aula: sì o no?
*Obiettivo: smontare la domanda binaria e sostituirla con «AI progettata come».*

## 32 - Stacco di parte
**Layout** - Card di sezione. **Testi** - `PARTE 5` / *L'AI in aula: sì o no?* - **Nota:** «Domanda sbagliata. Ve lo dimostro con tre studi.»
⚠️ La card resta **pulita**: la frase che apre la parte sta sulla slide dopo.

---

## 32-bis - La frase che apre la parte · **NUOVA** ⏳ *numero da assegnare*

> Arriva dalla **24**, dove chiudeva la Parte 2. È una frase sull'**insegnare**, non sul mercato: lì anticipava la tesi, qui la pone come problema da risolvere.

**Layout** - Piena pagina, una frase sola, molto respiro. Stesso trattamento che aveva sulla 24: ambra, serif, misura stretta.
**Testi**
> «Stiamo formando una generazione che si fida di più proprio dello strumento di cui gli **esperti** si fidano di **meno** - senza darle gli strumenti per **verificarlo**.»

**Visual** - Nessuno. La frase è la slide.
**Nota** - È il problema che la parte va a risolvere, non ancora la risposta. Dilla lentamente, poi: «"Senza darle gli strumenti per verificarlo" - quella è la parte che dipende da noi. E la domanda che si fa di solito, *AI in aula sì o no*, non ci arriva nemmeno vicino.»
↳ Aggancia all'indietro: i tre fatti della 24 (36 milioni di nuovi sviluppatori, metà del codice che non passa, gli esperti che diffidano) sono già in sala da venti minuti. Qui non li ripeti, li **usi**.
↳ Apre in avanti: i tre studi delle slide successive dicono cosa succede quando gli strumenti per verificare non glieli dai.

---

## 33 - 52 sviluppatori, 50% contro 67%

**Layout** - Titolo-metodo lungo, due card grandi affiancate, blocco metodo sotto.
**Testi**
- titolo: `52 SVILUPPATORI · LIBRERIA NUOVA · METÀ CON AI, METÀ A MANO · QUIZ SUBITO DOPO`
- **50%** con l'AI (rosso) | **67%** a mano (verde)
- metodo: 17 punti percentuali · «quasi due voti di differenza» · Cohen's d = 0,738 · p = 0,01. Gap più grande **sulle domande di debugging**. Velocità: +2 minuti con l'AI, non significativo.

**Visual** - Le due card col numerone.
**Nota** - «Hanno risparmiato due minuti e hanno capito due voti in meno. E lo pubblica l'azienda che vende l'agente di coding.»
⚠️ Non dire «17 per cento in meno»: sono **17 punti percentuali**. Dire «diciassette punti» o «cinquanta contro sessantasette».

---

## 34 - Sei modi di usarla. Due esiti.

**Layout** - Due pannelli affiancati con tre voci ciascuno, più una riga di chiusura centrata.
**Testi**
- **SOTTO IL 40%**: Delega totale («fammelo tu») · Reliance progressiva (inizi chiedendo, finisci delegando) · Debug iterativo («aggiusta» invece di «spiega»)
- **SOPRA IL 65%**: Genera, poi chiedi spiegazioni · Codice e spiegazione insieme · Conceptual inquiry (solo domande concettuali, errori risolti da solo)
- chiusura: «Il gruppo *conceptual inquiry* era anche il secondo più veloce in assoluto.»

**Visual** - Le due colonne rosso/verde.
**Nota** - «Questo distrugge l'alibi del trade-off. Chi usa l'AI per CAPIRE va veloce E impara. Chi la usa per DELEGARE va uguale e non impara niente.» Poi: «La domanda non è più AI sì o no. È: quale di queste sei colonne stiamo insegnando? Perché se non insegniamo niente, il default è la colonna rossa.»
🙋 **Momento interattivo:** «Alzate la mano: in quale di queste sei vi riconoscete stamattina?»

---

## 35 - ~1.000 studenti · PNAS 2025

**Layout** - Tabella a tre colonne: gruppo | durante la pratica | all'esame senza AI.
**Testi**
- **GPT Base** (ChatGPT normale): **+48%** durante la pratica → **−17%** all'esame, rispetto a chi non l'ha mai avuto
- **GPT Tutor** (stesso modello, dà hint non risposte): **+127%** durante la pratica → **nessun danno** all'esame

**Visual** - La tabella stessa; il contrasto verde/rosso sulla prima riga.
**Nota** - «Stesso identico GPT-4. Cambia solo come è stato IMPACCHETTATO. Con i guardrail raddoppi l'apprendimento; senza, chi lo usa finisce SOTTO chi non l'ha mai avuto.» Chiusura: «Ecco perché "AI sì o no" è la domanda sbagliata. La domanda è: AI progettata come. E quella è una decisione didattica, non tecnologica.»

---

## 36 - The Widening Gap

**Layout** - Titolo-metodo, titolo grande, due colonne, poi una frase-manifesto.
**Testi**
- `STUDIO QUALITATIVO · 21 STUDENTI · OSSERVAZIONE, INTERVISTE, EYE-TRACKING` · *The Widening Gap*
- Chi **accelerava** usava la GenAI per scrivere codice che sapeva già di voler scrivere, e ignorava i suggerimenti sbagliati.
- Chi **arrancava** ha visto le proprie difficoltà metacognitive **aggravarsi**, e ne sono emerse di nuove.
- in grande, ambra: **Illusione di competenza**

**Visual** - Nessuno.
**Nota** - Abbassare la voce: è la parte personale. «Io lavoro con adulti in riqualificazione. Gente di 40 anni che cambia vita. Quelli sono, quasi per definizione, il gruppo a bassa autoefficacia. Sono esattamente quelli che l'AI SEMBRA aiutare e sta lasciando indietro.»
⚠️ Dire che sono 21 e che è qualitativo con eye-tracking: toglie l'obiezione prima che arrivi.

---

## 37 - The Effortless Trap

**Layout** - Centrata. Citazione grande, sotto una citazione piccola.
**Testi**
- «If letting AI in makes the task feel effortless, **it is in the wrong place.**» - *The Effortless Trap*, Brcic & Frljic, giugno 2026
- «Lo sforzo cognitivo - e persino il **restare dolorosamente bloccati** - è probabilmente importante per la padronanza.» - Anthropic, 2026

**Visual** - Nessuno.
**Nota** - «Se i vostri studenti non sono mai bloccati, non state insegnando: state intrattenendo. E questo vale anche per voi, quando imparate una libreria nuova alle undici di sera con l'agente aperto.»

**Da citare a voce, non in slide** - *Magnifica Humanitas*, §140. Tre citazioni sulla stessa slide erano troppe, ma detta funziona: arriva da una tradizione completamente diversa e dice esattamente la stessa cosa.
> «Educare all'uso dell'IA implica [...] educare a **decidere quando e per cosa non usarla**. La velocità e la facilità con cui si ottiene una risposta o una sintesi rischiano di **spegnere il desiderio di porre domande** [...]. Dobbiamo educarci a **digiunare dall'IA**.»

↳ Chiude il cerchio con la **sesta voce della 31** e con l'enciclica citata in apertura di Parte 4. Se lì hai già rivendicato la mossa («l'unica dichiarazione che cito, e non viene dalla Silicon Valley»), qui basta dire «lo stesso documento di prima».
📎 ✅ verificata verbatim su vatican.va, 25 settembre 2026.

---

# PARTE 6 · slide 38–47 - Cinque esercizi
*Obiettivo: far provare in sala, senza farli fare. Formato fisso: mostri → conti fino a dieci in silenzio → «be'? sapreste farlo?».*

## 38 - Stacco di parte · **RIFINITA**
**Layout** - Card di sezione.
**Testi** - `PARTE 6` · occhiello **`COME SI INSEGNANO`** / *Cinque esercizi che nel 2019 erano stupidi.* / **Nel 2026 sono il programma.**
**Nota** - Prima il raccordo: «Le sei competenze della lista **non si insegnano spiegandole**. Adesso vi faccio vedere come si allenano.» Poi la consegna: «Non vi chiedo di farli: vi chiedo di chiedervi se SAPRESTE farli. E se sapreste VALUTARE qualcuno che li fa.»
↳ **L'occhiello fa il lavoro di raccordo** che prima mancava: la parte passa dalla lista (31) alla pratica. La battuta resta, ma non è più la prima cosa che si legge.

---

## 39 - Esercizio 1 · Prompt Problem

**Layout** - Titolo, blocco di codice, domanda evidenziata.
**Testi**
- `ESERCIZIO 1 · PROMPT PROBLEM - ALLENA: SPECIFICARE`
- cinque casi input → output, di cui tre con `???`: `[1,2,2,3,3,3] → [1,2,3]`, `[5,5] → [5]`, `["b","a","b"] → ???`, `[] → ???`, `[3,1,3] → ???`
- domanda: «Scrivete il prompt. Un tentativo solo. Deve passare tutti i test.»

**Visual** - Il blocco input→output *è* il visual: problema dato in forma visuale apposta, così non si può copiaincollare.
**Nota** - «Chi ha scritto "rimuovi i duplicati" ha già sbagliato TRE casi su CINQUE. E il modello non ve lo dirà: vi darà `sorted(set(xs))`, pulito, con la docstring, che passa i due test che avevate in mente.» Le quattro ambiguità: **ordine** (ordinato o di prima apparizione?), **tipo**, **lista vuota**, **mutazione**.

---

## 40 - Esercizio 2 · Explain in Plain English

**Layout** - Titolo, codice Python, domanda.
**Testi**
- `ESERCIZIO 2 · EXPLAIN IN PLAIN ENGLISH - ALLENA: COMPRENDERE`
- funzione `h(xs)` di sei righe (è Kadane, ma non lo si dice)
- domanda: «In UNA frase: cosa fa? Non riga per riga - cosa *fa*.»

**Visual** - Solo il codice.
**Nota** - Distinguere i due livelli: **multistrutturale** («tiene due variabili, per ogni elemento…») = riassunto; **relazionale** («somma massima di una sottosequenza contigua») = comprensione. Poi il bug verificato: `h([-3,-1,-7])` → **0**, dovrebbe essere **−1**. Twist finale: «la vostra frase diventa il prompt. Se il modello rigenera codice equivalente, avevate capito.»

---

## 41 - Esercizio 3 · Trova la vulnerabilità

**Layout** - Titolo, codice Flask, poi due elementi affiancati: finto terminale a sinistra, domanda a destra.
**Testi**
- `ESERCIZIO 3 · TROVA LA VULNERABILITÀ - ALLENA: VALUTARE CRITICAMENTE`
- endpoint `/cerca` che logga `q`, costruisce HTML in f-string e lo restituisce
- terminale: `$ pytest -q` / `3 passed in 3.34s`
- domanda: «I test sono verdi. È in produzione. Chi la vede?»

**Visual** - **Mockup di terminale** coi test verdi accanto alla domanda: il contrasto fra "verde" e "bucato" è tutto il senso della slide.
**Nota** - Contare le mani dopo la domanda.

---

## 42 - Non una. Tre.

**Layout** - Tre voci numerate, poi un riquadro di log.
**Testi**
1. **XSS riflessa** su `{q}` nell'`h1`
2. **XSS stored** su `{a['titolo']}` - se i titoli arrivano dal DB. *Questa non la vede quasi nessuno.*
3. **Log injection**: con un `%0A` forgi una riga di log falsa

**Visual** - **Riquadro di log** con due righe: una vera e, sotto in rosso, quella forgiata - `2026-09-26 10:00:00 INFO utente admin: login riuscito da 10.0.0.1 ← FALSA`.
**Nota** - «Quasi tutti hanno visto la prima. La seconda la vede molta meno gente. La terza praticamente nessuno.» Pausa. «Ma la domanda vera è: L'AVRESTE VISTA SE NON AVESTE MAI SCRITTO CODICE A MANO? XSS e log injection sono le due categorie in cui i modelli vanno peggio.»

---

## 43 - Esercizio 4 · Il test di Naur

**Layout** - Titolo, blocco di codice lungo (sei passaggi commentati), domanda.
**Testi**
- `ESERCIZIO 4 · IL TEST DI NAUR - ALLENA: COSTRUIRE LA TEORIA`
- `calcola_totale(ordine)`: subtotale → promo % → punti fedeltà → coupon → spedizione sopra soglia → IVA
- domanda: «Il marketing chiede: la soglia spedizione deve valere sul carrello *prima* degli sconti, e i punti non devono maturare sull'IVA. **Dove mettete le mani?**»

**Visual** - Solo il codice, volutamente pulito e ben commentato: deve *sembrare* a posto.
**Nota** - Lasciar leggere.

---

## 44 - Il paradosso dei punti

**Layout** - Titolo-scenario, due righe di conto, frase-conclusione grande, nota piccola.
**Testi**
- `CARRELLO: 2 × 32,50 € · PROMO −20% · NESSUN COUPON`
- Senza usare i punti → **63,44 €**
- Usando 300 punti (= 3,00 € di sconto) → **68,20 €** (in rosso)
- conclusione: «Spendere 3,00 € di punti fa *aumentare* il totale di 4,76 €.»
- nota: i punti fanno scendere il subtotale da 52,00 a 49,00 - sotto la soglia dei 50 € - e scatta la spedizione a 6,90 più IVA.

**Visual** - Il confronto fra i due totali.
**Nota** - «Questo codice funziona. Passa i test. Ha i commenti. Ed è un disastro - ma NON POTETE SAPERLO LEGGENDOLO, perché il codice non vi dice se questa è una decisione di business o un incidente.» E: «Non vi ho chiesto "trova il bug". Vi ho chiesto DOVE METTETE LE MANI. Chi ha in testa la teoria risponde in dieci secondi. Chi non ce l'ha o si legge tutto adesso - costruire la teoria in ritardo costa il triplo - oppure dice all'agente "rigenera tutto". Ma se rigenerate tutto, al giro dopo siete di nuovo esattamente qui.»

---

## 45 - Esercizio 5 · Code review al contrario

**Layout** - Titolo, riga di contesto, due pannelli di codice affiancati, domanda.
**Testi**
- `ESERCIZIO 5 · CODE REVIEW AL CONTRARIO - ALLENA: DECIDERE E MOTIVARE`
- contesto: «Issue: *Il totale del carrello a volte è sbagliato di un centesimo.* Due PR. Entrambe verdi. Entrambe generate.»
- **PR #1** (+2 −1): `round(t - t * sconto_pct / 100, 2)`
- **PR #2** (+9 −3): `Decimal` + `quantize(ROUND_HALF_UP)`
- domanda: «Quale approvate? E cosa scrivete nel commento?»

**Visual** - I due diff affiancati, con il conteggio delle righe in alto: PR #1 sembra la scelta ovvia.
**Nota** - «PR #1 è più corta, più leggibile, passa i test, e IL BUG RICOMPARIRÀ TRA SEI MESI. PR #2 è più lunga, più brutta, e ha ragione.» Poi: «Questo è letteralmente il lavoro di un junior in IBM nel 2026: genera cinque soluzioni, dimmi quale è giusta E PERCHÉ. Il "e perché" è tutto il mestiere.» E la conseguenza sulla valutazione: «se il codice funzionante non dimostra più niente, si torna a far parlare le persone. Colloquio, spiegazione, review dal vivo, "difendi questa PR". Meno scalabile. Più vero.»
🙋 Se qualcuno obietta che anche PR #2 è discutibile - e succederà - è il momento migliore del talk: dargli ragione e dire «questa conversazione che stiamo facendo adesso È la competenza. Non c'è nel diff, non c'è nel prompt, non c'è nei test.»

---

## 46 - Un centesimo, tre volte

**Layout** - Tabella a quattro colonne: carrello | sconto | PR #1 | PR #2. Sotto, due righe di REPL.
**Testi** - Tre carrelli con la divergenza di un centesimo (95,09 vs 95,08 · 48,23 vs 48,22 · 34,76 vs 34,75), poi `>>> round(2.675, 2)` → `2.67  # non 2.68: banker's rounding, non half-up`
**Visual** - La tabella; i valori PR #1 in rosso, PR #2 in verde.
**Nota** - Mostrare i numeri e chiudere.
**Footer** - Divergenze trovate su 400.000 carrelli generati casualmente

---

## 47 - Cosa hanno in comune

**Layout** - Cinque righe esercizio → competenza, poi conclusione separata da un filetto.
**Testi**
| 1 · Prompt Problem | **Specificare** |
| 2 · Explain in Plain English | **Comprendere** |
| 3 · Trova la vulnerabilità | **Valutare criticamente** |
| 4 · Il test di Naur | **Costruire la teoria** |
| 5 · Code review al contrario | **Decidere e motivare** |

conclusione: «In nessuno dei cinque il compito è **scrivere codice**. **In tutti e cinque, non li sai fare se non hai mai scritto codice.**»

**Visual** - Nessuno.
**Nota** - Chiusura dell'atto e praticamente la tesi del talk. Non aggiungere niente.

---

# CHIUSURA · slide 48–50

## 48 - Sì. Più di prima.

**Layout** - La domanda del titolo come occhiello, la risposta in grande, un paragrafo sotto.
**Testi**
- occhiello: `DOVREMMO ANCORA INSEGNARE A PROGRAMMARE NELL'ERA DEGLI LLM?`
- risposta: *Sì. Più di prima.*
- «Ma non per **produrre** codice - quello è gratis. Per costruire la **teoria** che rende il codice vivo, e la capacità di **giudicare** una macchina che sbaglia con sicurezza.»

**Visual** - Nessuno.
**Nota** - «È una competenza tacita. Si costruisce con la fatica. E - per citare l'unica frase che vi chiedo di ricordare - NON SI PUÒ DELEGARE.»

---

## 49 - Tre cose

**Layout** - Occhiello + titolo, tre voci numerate.
**Testi**
1. **Automazione o aumento**: la stessa tecnologia, due esiti opposti. Chi insegna decide quale.
2. **La facilità è un segnale d'allarme**, non un obiettivo. Per gli studenti e per voi.
3. **I pioli bassi non si automatizzano impunemente.** Qualcuno deve restare a costruirli.

**Visual** - Nessuno.
**Nota** - Se avanzano 20 secondi: «Se lavorate in un'azienda che ha smesso di assumere junior, fate vedere ai vostri responsabili la slide di IBM. Non è buonismo, è pianificazione.»

---

## 50 - Grazie

**Layout** - Centrata, senza numero di pagina.
**Testi** - *Grazie* · filetto · `Giuseppe Mastrandrea` · «Tutte le fonti, con i numeri verificati uno per uno - compresi gli studi che mi danno torto.» · in ambra, mono: `Train you must. Not with a saber - with knowledge.`
**Visual** - Nessuno.
> ⚠️ **Manca:** non c'è un modo concreto per arrivare alle fonti. Serve un QR o un indirizzo breve, altrimenti la promessa resta a vuoto.

---

# Punti aperti raccolti

| # | Questione |
|---|---|
| 19 | La scala coi pioli è piccola rispetto al titolo accanto (sul tema chiaro si nota di più) |
| 30 | «Bloom rovesciato» è concettualmente centrale ma non ha un visual |
| 50 | Manca il riferimento concreto alle fonti (QR / link breve) |
| - | **Bilancio dei visual:** 9 slide su 50 hanno una grafica vera; la parte 4 (slide 29–31) ne è completamente priva |
| 9 | Cosa distingua il **β** dalle altre misure di Eloundou non è nel paper di Stanford: va verificato su Eloundou et al. 2024, se vuoi spiegarlo in aula |
| - | **Durata:** 50 slide + 5 momenti in sala. Da verificare contro il tempo assegnato |

---

# Decisioni prese - da applicare al Marp

Ordinate per **slide di destinazione**, non per data. Tutte prese il **23 settembre 2026**.

| Slide | Cosa cambia |
|---|---|
| ~~-~~ | **Tagliata** la slide del 49% / 79% Anthropic *(era la 6 nel PDF)*. Motivi per esteso alla lapide, sopra. |
| **7** | Non dice più «non è un sondaggio» senza distinguere: la frase vale per **come contano le persone**, non per come classificano l'esposizione. Aggiunto il prezzo del sottoprodotto - ADP non è l'economia americana. |
| **8** | **Nuova** · *Le due metà dello studio* - buste paga = esito, esposizione = giudizio esterno, giuntura sul codice SOC. Assorbe i numeri del campione. |
| **9** | **Nuova** · *Cosa vuol dire «esposto»* - nei quintili ci vanno le professioni; due misure; **esposizione ≠ adozione**; le due liste Q1/Q5. |
| **10** | **Rifatta senza grafico** - via la forbice, che disegnava una traiettoria mai misurata. Restano il **19%** come controfattuale e il controllo sugli esperti. |
| **11** | **Rifatta** · *Non licenziati. Non svenduti.* - fatti 4 e 6 insieme, chiude su **quantità, non prezzo**. Anticipa la scala coi pioli di nove slide. |
| **13** | Introduce da sé *automazione / complementarità*. Il legame metodologico con l'Anthropic Economic Index resta **fuori dalle slide**, come risposta pronta per il Q&A. |
| **14** | **Nuova** · *Cosa hanno già escluso* - robustezza: non è il post-COVID del tech. Tre barre, −0,193 → −0,190 → −0,166. |
| **15** | **Nuova** · *E allora gli sviluppatori?* - quintile 5 e anomalia salariale, con la cautela sull'**equity**. |
| **16** | **Nuova** · *Il riassunto* - cinque frasi distese, **slide-fotografia**. |
| **17–21** | **Riordinate il 24 settembre:** il blocco italiano (20, 21) è stato spostato in **fondo alla Parte 1**, dopo la scala. La transizione «e qui?» passa dalla 16 alla **19**. Alla 21 è stato aggiunto il **passaggio di consegne** verso il resto del talk. |
| **20** | **Rifatta da zero** · *E in Italia? Non si vede* - confronto AlmaLaurea laureati 2023 vs 2025 + Excelsior. Spariscono il 76% e il 78%. |
| **21** | **Nuova** · *Tre spiegazioni, nessuna rassicurante* - chiude su «il canarino americano lo sentiamo cantare». |
| ~~**30**~~ | **Tagliata** · *Cosa sta comprando davvero il mercato* - due numeri su tre non reggevano e ripeteva la Parte 1. |
| **19** | Prende l'occhiello **«Oh shit, here we go again»**, ereditato dalla slide tagliata. |

| **22** | **Rifatta** · *Facciamo un punto* - la card di stacco diventa il bilancio della Parte 1 in tre fasce, e il buco («non abbiamo guardato **cosa** faccia la macchina») apre la parte. La Parte 2 si chiama ora *Cosa fa davvero la macchina*. |
| **21** | **Passaggio accorciato** a una frase: il ponte lo fa la 22. |
| **23** | Aggiunto **il limite del benchmark detto da lui** - misura l'output grezzo, non il codice che passa una review. È il ponte verso la verifica. |
| **24** | **Corretta la riga sulla fiducia**: il 46/33 è la popolazione totale, non gli esperti (2,5% / 20,7%). Due misure che erano state fuse. |
| **24** | **Chiusura sostituita** con *«Produrre non è più il collo di bottiglia. Verificare sì.»* - atterraggio della Parte 2. La vecchia frase sulla «generazione che si fida» va all'**apertura della Parte 5**. |
| **26** | Attribuzione esplicita a Karpathy (2.0 = 2017, 3.0 = Sequoia Ascent 2026) e link nel footer. Anche *pavimento/soffitto* alla 27 è suo. |
| **29-bis** | **Nuova** · citazione §145 di *Magnifica Humanitas* in apertura di Parte 4 - «programmi pensati per un'altra epoca», «i metodi di valutazione». Da rivendicare come unica citazione d'autorità del talk. ⏳ numero da assegnare. |
| **31** | **Colonna Bloom** accanto alle sei voci, con **tutti e sei i livelli rappresentati**: le competenze 1 e 4 attraversano *ricordare* e *applicare* invece di saltarli. «Ci passate ancora attraverso tutti e sei. Solo che prima ci fermavamo ai primi due.» |
| **38** | **Occhiello `COME SI INSEGNANO`** sulla card: raccorda la lista della 31 agli esercizi. La battuta «nel 2019 erano stupidi» resta. |
| **37** | Riceve il **§140** («digiunare dall'IA») **citato a voce, non in slide**: alla 37 c'erano già due citazioni. Chiude il cerchio con la sesta voce della 31. |
| **32-bis** | **Nuova** · riceve la frase spostata dalla 24 - «una generazione che si fida di più dello strumento di cui gli esperti si fidano di meno». Slide a sé **subito dopo la card**, che resta pulita. ⏳ numero da assegnare. |

**✅ Applicate tutte al Marp il 25 settembre 2026.** Il deck è a **57 slide**; i PDF chiaro e scuro sono rigenerati.
Controllate in render le slide più dense - il riassunto, il punto della Parte 2, la lista con la colonna Bloom, l'Italia: nessuna sfora.

**Aggiunto nello stesso render, non previsto dal brief:** l'apertura è stata rifatta come **sequenza impilata di sette slide** (una citazione per volta, le precedenti restano visibili sotto, sbiadite), con le foto in `talk/assets/`. Sostituisce le due slide-elenco 3 e 4.
