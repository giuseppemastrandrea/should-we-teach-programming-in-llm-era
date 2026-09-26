# Audit delle fonti — verifica rigorosa
### *Dovremmo ancora insegnare a programmare nell'era degli LLM?* · Come To Code 2026

Verifica condotta il **21 settembre 2026** risalendo, dove possibile, **al documento primario** (paper, PDF ufficiale, pagina del report) e non alle sintesi giornalistiche.
Metodo: per ogni numero ho cercato la frase letterale nella fonte originale. I PDF sono stati scaricati ed estratti in locale, non riassunti.

**Esito complessivo: 6 errori da correggere, 7 imprecisioni da riformulare, 4 claim da abbandonare, 21 confermati, e 6 numeri migliori trovati strada facendo.**
Nessun dato che invalidi la tesi del talk. Anzi: due delle correzioni la rafforzano.

---

> ⚠️ **Numerazione.** I riferimenti «Slide N» di questo documento sono quelli del **canovaccio
> originale**, non del deck Marp attuale. Corrispondenze principali: il 79% Anthropic è «Slide 5»
> qui e **slide 6** nel deck; Stanford è «Slide 8» qui e **slide 9**; Stack Overflow è «Slide 17»
> qui e **slide 19**. Per la mappa aggiornata slide per slide vedi `struttura-slide.md`.

# 🔴 ERRORI — da correggere prima delle slide

### 1. Slide 8 — "+6/+12% per gli sviluppatori più esperti" → **numero sbagliato e categoria sbagliata**

Il "+6–12%" non esiste nel paper. Mescola due cose diverse.

Dal testo primario (versione novembre 2025, p. 2):
> *"workers aged 22 to 25 have experienced a **6% decline** in employment from late 2022 to September 2025 in the most AI-exposed occupations, compared to a **6-9% increase** for older workers"*

Quindi: il 6–9% riguarda i **lavoratori più anziani nelle occupazioni esposte in generale**, non gli sviluppatori software. E il −20% riguarda **gli sviluppatori software specificamente**. Non si possono mettere sulla stessa slide come se fossero due linee dello stesso grafico.

**Correzione**: o due numeri sulla stessa categoria, o due numeri sulla stessa occupazione. Vedi la proposta di slide 8 riscritta più sotto.

---

### 2. Slide 8 — "−20% dalla fine del 2022" → **è "quasi il 20%" e rispetto al PICCO**

Dal testo primario (nov 2025, p. 9):
> *"By September 2025, employment for software developers aged 22-25 declined **nearly 20%** compared to **its peak in late 2022**."*

Due differenze che contano: **"nearly"** (quasi), e **"compared to its peak"** — è una misura picco-minimo, non inizio-fine. È una formulazione più drammatica e va detta com'è, non arrotondata per eccesso.

⚠️ **E soprattutto**: questo dato è della **versione novembre 2025, con dati fino a settembre 2025**. Nella **versione agosto 2026** — quella che citi come "update" — il caso degli sviluppatori software **non è più nel testo principale**: è finito nell'Online Appendix (Fig. B.3), senza una percentuale esplicita. Se dal palco dici "Stanford, agosto 2026, sviluppatori −20%", stai attribuendo alla versione nuova un numero che è nella vecchia.

**Correzione**: cita il dato con la sua data — *"nella versione di novembre 2025, con dati fino a settembre 2025"* — oppure usa i numeri della versione 2026 (vedi ⭐ più sotto).

---

### 3. Slide 5 — il 79% di Claude Code: **fonte e data sbagliate** → ⛔️ **SLIDE POI TAGLIATA (23 set 2026)**

Ho attribuito il dato all'*Anthropic Economic Index, gennaio 2026*. **Non c'è.** Ho verificato il report di gennaio 2026: parla solo di Claude.ai (52% augmentation / 45% automation, dati novembre 2025) e di API enterprise (tre quarti automation). Claude Code non compare.

Il 79% viene da un report diverso: **"Anthropic Economic Index: AI's Impact on Software Development"**, pubblicato il **28 aprile 2025**, su 500.000 interazioni di coding raccolte tra il **6 e il 13 aprile 2025**.
> *"79% of conversations on Claude Code were identified as 'automation'"* · Claude.ai: 49%
> Scomposizione: Directive 43,8% + Feedback Loop 35,8%

**Il problema vero non è l'attribuzione, è l'età**: è una fotografia di Claude Code a una settimana dal lancio, diciassette mesi prima del tuo talk. Dire "il default dell'agente è: fallo tu" appoggiandosi a dati di aprile 2025 è attaccabile da chiunque in sala usi Claude Code oggi.

> **Aggiornamento 23 settembre 2026 — la slide è stata eliminata**, quindi la correzione qui sotto è superata.
> Non è stata una questione di attribuzione ma di **necessità**: la dicotomia automazione/complementarità
> è già il fatto n. 5 di Stanford, su dati di busta paga, e «gli strumenti hanno un default» lo dimostra
> meglio l'RCT dei sei pattern d'uso. Restavano solo i difetti: 17 mesi di ritardo, confronto non
> controllato fra utenze diverse, e **vendor research senza l'attenuante** che salva l'RCT (lì il
> risultato è contro l'interesse di chi pubblica; qui è una statistica d'uso neutra sui propri prodotti).
> Il ragionamento per esteso è in `struttura-slide.md`, alla lapide della slide 6.

**Correzione** *(superata, conservata per memoria)*: cita data e fonte corrette e **dillo tu prima che te lo dicano** — *"dati di aprile 2025, quindi vecchi; se qualcuno ha numeri più freschi me li dica, ma la direzione è quella"*. Oppure sposta il peso della slide sul contrasto Claude.ai 49% vs Claude Code 79%, che è un confronto **tra strumenti nello stesso momento** e quindi invecchia molto meglio.
📎 [anthropic.com/research/impact-software-development](https://anthropic.com/research/impact-software-development)

---

### 4. Slide 17 — "29% si fida, −11 punti rispetto al 2024" → **numero sbagliato**

Il 29% che avevo è in realtà **solo la fetta "somewhat trust" (29,6%)**, scambiata per il totale da una sintesi di terze parti.

Dati reali della Developer Survey 2025 (sezione *Accuracy of AI tools*):

| | 2025 |
|---|---|
| Highly trust | **3,1%** |
| Somewhat trust | 29,6% |
| **Totale trust** | **32,7%** *(SO arrotonda a 33%)* |
| Somewhat distrust | 26,1% |
| Highly distrust | 19,6% |
| **Totale distrust** | **45,7%** *(SO arrotonda a 46%)* |

E il **"−11 punti rispetto al 2024" non è verificabile** nel report 2025: i dati 2024 non ci sono nella pagina.

✅ **Buona notizia**: la frase di Stack Overflow è più forte di quella che avevo costruito io —
> *"More developers actively distrust the accuracy of AI tools (46%) than trust it (33%)."*

Usa questa, alla lettera. Niente delta col 2024.

---

### 5. Slide 17 — sviluppatori esperti: **2,6% / 20%** → sono **2,5% / 20,7%**

Piccolo, ma se metti una cifra decimale in slide dev'essere quella giusta.
> Esperti: **2,5%** highly trust · **20,7%** highly distrust

---

### 6. Atto 2 / doc di contesto — GitClear "+75% di codice committato rispetto al 2022" → **non verificato**

Non sono riuscito a risalire a questo numero in nessuna fonte GitClear primaria. Viene da una sintesi Dark Reading di un'analisi di ottobre 2025. Le metriche GitClear che **ho** verificato sono diverse — e, francamente, migliori:

> Blocchi di codice duplicato: **8×** nel 2024 · copy/paste dentro lo stesso commit **+41%** · duplicazione di blocchi **+81%** · costrutti che mascherano gli errori **+47%** · churn a due settimane **+15%** · refactoring (spostamento di righe) **−70%** · manutenzione del codice legacy **−74%** rispetto al 2022

**Correzione**: butta il +75% e usa queste. "Il refactoring è calato del 70% e la duplicazione è aumentata di otto volte" dice molto meglio la stessa cosa: non è che si scrive più codice, è che **si smette di sistemarlo**.

---

# 🟠 IMPRECISIONI — da riformulare

### 7. Anthropic RCT — "17% in meno" vs "17 punti percentuali"

Anthropic scrive davvero *"scored 17% lower"*, ma i punteggi grezzi sono **50% vs 67%**, cioè **17 punti percentuali**, che in termini relativi è un calo del **25%**. La loro formulazione è ambigua; ripeterla ti espone a una contestazione legittima dal pubblico.

**Il tuo canovaccio già dice "50% vs 67%", che è la forma corretta.** Basta che dal palco **non** dica "diciassette per cento in meno": di' *"diciassette punti"* o *"cinquanta contro sessantasette"*. Il *"quasi due voti"* è testuale di Anthropic e puoi usarlo.
✅ Confermati: n=52, "mostly junior", Cohen's d = 0,738, p = 0,01, ~2 minuti più veloci non significativi, i sei pattern d'uso.

---

### 8. METR — manca il dato che il pubblico chiederà: **n = 16**

Lo studio METR ha **16 sviluppatori** e 246 issue. Nei miei documenti non l'avevo mai scritto. Se presenti METR senza dire "sedici persone", il primo che lo sa lo dice dal fondo della sala.

Gli autori stessi elencano cosa lo studio **non** dimostra, tra cui: *"non affermiamo che i sistemi AI non accelerino molti o la maggior parte degli sviluppatori"* e *"studiamo solo lo sviluppo software"*.

**Riformulazione consigliata**: non usare METR come prova che l'AI rallenta. Usalo **solo** per il punto sulla percezione — *"sedici sviluppatori esperti, sui loro repository: si aspettavano +24%, hanno fatto −19%, e dopo erano ancora convinti di aver accelerato del 20%"* — che è robusto e non dipende dalla generalizzabilità.

---

### 9. Veracode — il 45% va contestualizzato, e il numero 2026 è diverso

- **Report 2025**: 45% dei campioni fallisce i test di sicurezza. Java **72%**, C# 45%, JavaScript 43%, Python 38%. XSS (CWE-80): i modelli falliscono nell'**86%** dei casi.
- **Aggiornamento primavera 2026**: i tassi oscillano **tra il 45% e il 55%** a seconda del taglio, senza miglioramento. Il report 2026 ragiona in **tassi di superamento** anziché di fallimento, quindi attenzione a non invertire i numeri leggendolo. XSS e log injection restano le categorie peggiori (pass rate ~13–15%).

**Riformulazione sicura**, che regge su entrambi i report:
> *"Circa la metà del codice generato non supera i test di sicurezza. E questo numero non è migliorato da un anno e mezzo, nonostante i modelli nuovi."*

Non dire "45% invariato": il numero 2026 non è esattamente 45%. Di' "circa la metà, invariato".

---

### 10. Iscrizioni CS — il "−3,6% autunno 2025" è di un'altra categoria

Fonte primaria (NSC, 11 agosto 2026):
- **Primavera 2026**: −8,4% istituzioni quadriennali · −9,3% *primarily associate-baccalaureate* · **−11,2% biennali**
- **Autunno 2025**: **−3,6%** riguarda le *primarily associate-baccalaureate*, **non** l'undergraduate quadriennale in generale · graduate **−14,0%**

Il "53.000 studenti persi" viene dal *Chronicle*, non da NSC: è secondario, anche se plausibile.

⭐ **Due dati primari molto migliori di quelli che avevi** — vedi sezione ⭐.

---

### 11. Prather "The Widening Gap" — è **n=21, qualitativo**, e l'abstract non quantifica voti/autoefficacia

Metodo: 21 sessioni di laboratorio con osservazione, interviste ed **eye-tracking**. 21 partecipanti.

La formulazione "gli studenti con voti e autoefficacia più alti usano l'AI per accelerare" veniva da una sintesi, non dall'abstract. Quello che il paper dice letteralmente è più utile per te:
> gli studenti in difficoltà mostravano *"cognitive dissonance about their problem-solving ability, thought they had performed better than they actually did, and ended with an **illusion of competence**"*

**Riformulazione**: presentalo come **studio qualitativo su 21 studenti** (non nascondere il numero: in uno studio con eye-tracking è normale) e usa **"illusione di competenza"** come parola chiave. È più precisa e più memorabile di "il divario si allarga".

---

### 12. Excelsior — il ">55% per Informatica" non è nel comunicato

Confermati dal comunicato Unioncamere (**26 novembre 2025**, dati **2025**): 670.000 laureati e 120.000 diplomati ITS cercati; **50,9%** laureati e **57,3%** diplomati ITS di difficile reperimento; mismatch complessivo **47%**.

Il dato *">55% per Ingegneria, Informatica, Matematica e Fisica"* **non compare nel comunicato**: veniva da una sintesi giornalistica. Potrebbe stare nel rapporto completo, ma non l'ho verificato.

**Correzione**: usa il 50,9% sui laureati (già fortissimo) e **non** attribuire il >55% a Excelsior finché non lo trovi nel PDF del rapporto. Nota anche che sono dati **2025**, non 2026.

---

### 13. Knowledge Markers — **non è uno studio con evidenza**

Il paper esiste (Christina Maria Mayr, 7 aprile 2026), ma dichiara esplicitamente di essere **design-oriented, "without claiming measured learning gains"**. Nel documento di contesto l'avevo messo tra gli "approcci concreti con evidenza sperimentale". Non lo è: è una **proposta di design curricolare**.

**Correzione**: presentalo come *"un inquadramento proposto"*, non come un risultato. La frase che puoi citare — *"working code is no longer a reliable indicator of understanding"* — è comunque ottima.

---

# 🟡 DA ABBANDONARE — non verificabili

### 14. Randstad "+303% pensiero critico" — ⚠️ **il più rischioso di tutti**

È il numero più grande della tua slide 24 e **non sono riuscito a confermarlo da nessuna fonte Randstad primaria**. Esiste solo su testate italiane (Quotidiano.net, Forme) che riportano la stessa sintesi.

Quello che ho trovato sul materiale Randstad: la ricerca *Age of Augmentation* esiste (35,8 milioni di annunci, 11 mercati, 2021–2026), ma i numeri che emergono sono **diversi**: *prompt engineering +403%*, promozioni *3,5× più veloci* (non "2,5 volte" come avevo scritto).

**Raccomandazione**: **non mettere +303% in slide** finché non scarichi il report Randstad e lo verifichi. È esattamente il tipo di numero che un giornalista trascrive male e che poi ti si ritorce contro. Se ti serve il punto "il mercato italiano compra pensiero critico", hai già gli Osservatori PoliMi (76% degli annunci high-skill chiede competenze AI) che è verificabile.

### 15. "Junior ~4% degli annunci vs senior ~18%" (Italia) — già segnalato, **confermata l'impossibilità di verificare**. Non usarlo.

### 16. "−67% annunci entry-level 2022–2026" e "54% delle aziende ha smesso di assumere junior" — già segnalati. Restano senza fonte primaria. Non usarli.

### 17. "62% dei programmi di computing riporta iscrizioni in calo" — attribuito a CRA da una fonte secondaria (Built In). Non l'ho verificato sul sito CRA. Sostituibile con i dati NSC, che sono primari.

---

# 🟢 CONFERMATI — puoi usarli così come sono

| Claim | Esito |
|---|---|
| **Stanford**: 22–25 in occupazioni esposte **19%** sotto il "kept pace", esperti nessun gap comparabile | ✅ letterale nell'abstract ago 2026 |
| **Stanford**: gap passato da **15% (lug 2025) a 19% (giu 2026)** | ✅ letterale |
| **Stanford**: aggiustamento *"primarily through reduced hiring rather than increased separations"* | ✅ letterale (fatto 4) |
| **Stanford**: cali dove l'AI **sostituisce**, occupazione piatta o in crescita dove **complementa** | ✅ letterale (fatto 5) |
| **Stanford**: conoscenza **codificata** vs **tacita** | ✅ letterale |
| **Stanford**: regge escludendo aziende tech e occupazioni informatiche | ✅ letterale |
| **Anthropic RCT**: n=52, 50% vs 67%, d=0,738, p=0,01, ~2 min, i sei pattern | ✅ tutti letterali |
| **Bastani/PNAS**: ~1.000 studenti, GPT Base **+48%**, GPT Tutor **+127%**, esame senza AI **−17% relativo** vs controllo, Tutor nessun danno | ✅ confermati |
| **Kazemitabaar**: 69 novizi 10–17 anni, 45 task, **1,15×** completion, **1,8×** punteggi, nessun calo sui task manuali, post-test a 1 settimana non significativo | ✅ tutti letterali |
| **Octoverse**: 36M nuovi dev, 180M totali, *"**Nearly** 80% of new developers use Copilot within their first week"* | ✅ (di' "quasi l'80%") |
| **Stack Overflow**: 84% adozione (da 76% nel 2024) · 66% "almost right but not quite" · 45,2% debugging più lento · 52% non usa agenti | ✅ |
| **Veracode 2025**: 45%, Java 72%, C# 45%, JS 43%, Python 38%, XSS 86% di fallimento | ✅ |
| **Handshake**: 70% pessimisti · 14% ottimisti · 61% media · 64% cita GenAI · 47% media · 42% usa GenAI ogni giorno · 24% media | ✅ tutti |
| **NSC**: primavera 2026 **−8,4%** quadriennali, **−11,2%** biennali, graduate **−14%** | ✅ |
| **Anthropic**: Claude Code **79%** automation vs Claude.ai **49%** | ✅ *(ma vedi errore #3 sulla data)* |
| **METR**: −19% reale, +24% atteso, +20% percepito a posteriori; follow-up 2026 inconcludente per effetti di selezione | ✅ *(ma dichiara n=16)* |
| ~~**Apiiro**~~ | ❌ **TAGLIATO dal talk.** I numeri esistono ed è ripreso da The Register e SiliconANGLE, ma è **vendor research**: Apiiro vende la piattaforma ASPM che trova esattamente questi problemi, non è peer-reviewed, ed è un post sul blog aziendale. Soprattutto: **non dichiarano come hanno classificato uno "sviluppatore assistito da AI"**, che è l'intero studio. Vedi §Il criterio di provenienza. |
| **Prompt Problems**: rappresentazione **visuale** apposta per impedire il copia-incolla | ✅ **letterale** (vedi ⭐) |
| **Effortless Trap** (arXiv 2606.26181, Brcic & Frljic, 24 giu 2026): esiste, framework a 6 passi confermato | ✅ *(ma vedi ⭐ sulla citazione)* |
| **Dagstuhl 25311 e 27062**: esistono, organizzatori e temi confermati | ✅ |
| **IBM**: triplica entry-level USA 2026, annuncio 12 feb 2026, citazione LaMoreaux verificata | ✅ |
| **Excelsior**: 670k laureati, 120k ITS, 50,9% e 57,3% | ✅ *(ma vedi #12)* |

---

# ⭐ MIGLIORAMENTI — numeri migliori trovati durante la verifica

### A. Stanford, versione agosto 2026: i numeri "in livelli", molto più chiari
> *"employment of 22–25-year-olds in the two most exposed quintiles fell about **11%** between November 2022 and June 2026, while employment of the same age group in the **three least-exposed quintiles grew about 10%**."*

**Questa è la slide 8 che ti serve.** Stessa fascia d'età (22–25), stesso periodo, stessa fonte, due numeri direttamente confrontabili, nessun modello statistico di mezzo — e sono i numeri che **gli autori stessi hanno scelto di mettere in evidenza nella versione più recente**, abbandonando le stime di regressione.

⚠️ Nota correlata: il **16%** che citavo era una stima di regressione con firm-level fixed effects della vintage settembre 2025, che gli autori hanno **esplicitamente de-enfatizzato**: *"Earlier versions of this study headlined regression estimates... We now emphasize the simpler descriptive divergence."* Non usare il 16%.

### B. NSC: il contrasto che vale più della percentuale
Le iscrizioni a informatica calano dell'**8,4%** **mentre le iscrizioni universitarie complessive crescono dell'1,3%**. NSC la chiama *"un'anomalia nelle tendenze di iscrizione più ampie"*.
E il dato che nessuno cita: la **persistenza al secondo semestre** degli studenti di informatica è la **più bassa tra i dieci corsi di laurea principali (85,0%)**. Non solo se ne iscrivono meno: quelli che si iscrivono mollano di più.

### ~~C. Apiiro~~ — verificata la fonte, poi **tagliata per provenienza**
⚠️ *Sezione conservata per memoria: i numeri sotto sono reali e correttamente riportati, ma **non vanno usati nel talk**. Apiiro è un vendor di application security (fondata 2018, 135M$ di VC) che vende il prodotto che individua i problemi descritti dalla sua stessa ricerca; lo studio è un post sul blog aziendale, senza peer review né metodologia pubblicata, e **non dichiara come sono stati classificati gli "sviluppatori assistiti da AI"** — che è la variabile su cui poggia tutto. In più The Register osserva che conta solo il tempo di generazione del codice, non quello per sistemarlo, il che sgonfia il "3–4× più veloci". Il criterio che ne è derivato — **"lo posso controllare o devo crederlo?"** — è in fondo al canovaccio.*

**I dati, per memoria:**
Apiiro, Deep Code Analysis su **oltre 7.000 sviluppatori** e **62.000 repository** in aziende Fortune 50, **dicembre 2024 – giugno 2025**:
- commit **3–4×** più frequenti
- security findings da ~1.000 a **oltre 10.000 al mese** in sei mesi
- **errori di sintassi −76%**, **logic bug −60%**
- **privilege escalation +322%**, **difetti di design architetturale +153%**

**Questa è una slide intera, ed è forse il dato più forte di tutto il talk**: l'AI elimina gli errori piccoli e moltiplica quelli grandi. È esattamente la tua tesi — sparisce ciò che un junior sbagliava, resta ciò che serve un senior per vederlo.
📎 [Apiiro](https://apiiro.com/blog/4x-velocity-10x-vulnerabilities-ai-coding-assistants-are-shipping-more-risks/)

### D. Prompt Problems: la citazione letterale che ti mancava
> *"The participants were given **visual representations of a coding problem, without any text that they could copy and paste into their prompt**"*

E i **tre comportamenti osservati** sui 36 studenti dello studio esplorativo, che sono la validazione empirica del tuo esercizio 1:
1. all'inizio molti danno **prompt vaghi**, senza abbastanza dettaglio per risolvere il problema
2. quando si bloccano, **aggiungono messaggi di chiarimento invece di ristrutturare il prompt originale**
3. (terzo trend nel paper)

Il punto 2 è oro: è lo stesso pattern del "debug iterativo" che nell'RCT di Anthropic sta sotto il 40%. **Due studi indipendenti, stesso comportamento disfunzionale.** Se lo dici, è il collegamento più forte del talk.

### E. Effortless Trap: la citazione vera
Avevo messo tra virgolette *"Effortlessness is a warning signal."* La frase reale del paper è:
> *"if letting AI in makes the task feel effortless, it is in the wrong place"*

Più lunga ma più utile, perché contiene già la soluzione (la *collocazione*). Usa questa tra virgolette, e "la facilità è un campanello d'allarme" come tua sintesi parlata.

### F. Stack Overflow: la frase migliore è la loro
> *"More developers actively distrust the accuracy of AI tools (46%) than trust it (33%)."*

### G. Il ponte metodologico Anthropic ↔ Stanford — **verificato sul PDF, 23 set 2026**

Verificato scaricando ed estraendo il paper (`Canaries_August2026.pdf`, 3,4 MB, 34.813 parole).
**Stanford non cita Anthropic di sfuggita: ne usa la classificazione come misura.**

Stanford impiega due misure di esposizione all'AI. La seconda è l'Anthropic Economic Index:
> *"Second, we utilize the **Anthropic Economic Index** (Handa et al., 2025)… A key feature of the
> Anthropic index is its classification of queries as either **"automative" (substituting for labor)**
> or **"augmentative" (complementing labor)**; we leverage this distinction to test heterogeneous effects."*

E la **nota 40** chiude il cerchio:
> *"Handa et al. (2025) use Claude to classify conversations into six categories. **Directive and Feedback
> Loop conversations are considered Automative**; Task Iteration, Learning, and Validation are considered
> Augmentative."*

Directive + Feedback Loop sono **esattamente** le due categorie che formano il 79% di Claude Code
(43,8% + 35,8% = 79,6%). Lo stesso righello che classifica una conversazione classifica le occupazioni.

**In più** (tabella A.6): *Software Developers, Systems Software* è la **7ª occupazione più grande del
quintile 5**, quello a massima esposizione — *Computer Programmers* è al 34° posto dello stesso quintile.
Gli sviluppatori non sono un esempio portato da te: sono dentro il gruppo che perde l'11%.

**I limiti del ponte, da rispettare:**
- ❌ **Mai dire «Stanford ha usato il 79%».** Quel numero è per-prodotto e viene da un altro report.
  Ciò che passa da un lavoro all'altro è la **tassonomia**, non la misura.
- I risultati principali usano la release **marzo 2025** dell'indice (solo consumer); le release
  successive (set 2025, gen 2026, apr 2026) sono in appendice, sezione F.2.
- Il **−11%** è sui due quintili più esposti *nel loro insieme*, non sugli sviluppatori: per quelli
  il campione CPS è troppo piccolo — gli autori scrivono *"between 23 and 48 young software developers
  aged between 22 and 25 per month"*.
- Gli autori hanno **cambiato terminologia**: oggi scrivono «automation» e «complementary usage»,
  perché *labor-augmenting* in teoria della crescita significa un'altra cosa. Tengono le etichette
  di Anthropic solo in tabelle e figure.

**Uso previsto: Q&A, non slide.** Se ti chiedono come fa Stanford a sapere dove l'AI sostituisce,
questa è la risposta che chiude la questione.
📎 [digitaleconomy.stanford.edu/publications/canaries-in-the-coal-mine/](https://digitaleconomy.stanford.edu/publications/canaries-in-the-coal-mine/)

---

# ⚠️ Le cautele che gli autori di Stanford dichiarano e che tu non stai dicendo

La slide 6 dice *"Niente aneddoti. Buste paga."* È vero, ma gli autori sono più prudenti di così, **nell'abstract**:

> *"We interpret these facts as early, **descriptive indicators** — canaries in the coal mine — **rather than causal estimates**."*

E dichiarano tre limiti espliciti:
1. le occupazioni più e meno esposte mostrano **trend divergenti già prima di ChatGPT**, specie attorno al COVID
2. le stime **si attenuano controllando per il livello di istruzione** (che può essere una spiegazione alternativa *oppure* il canale stesso attraverso cui l'AI agisce — lo dicono loro)
3. la divergenza è **più marcata nel campione ADP che nei benchmark delle indagini nazionali**

**Consiglio non richiesto ma sentito**: dedica **quindici secondi** a questo, subito dopo la slide 8. Non ti indebolisce — ti rende l'unico speaker della giornata che cita i limiti dei propri dati. E se in sala c'è un economista, sei coperto. Una riga tipo: *"Gli autori stessi dicono che sono indicatori descrittivi, non stime causali, e che l'effetto si attenua se controlli per il titolo di studio. Li prendo per quello che sono: canarini."*

---

# 🇮🇹 VERIFICA DEL BLOCCO ITALIANO — 24 settembre 2026

Domanda di partenza: **cosa è successo agli sviluppatori software nel mercato del lavoro italiano
dall'arrivo dell'AI generativa in poi?**

## La risposta: non si vede

Non esiste in Italia nulla di paragonabile allo studio Stanford — nessun dato amministrativo per
professione ed età ad alta frequenza. E le due fonti italiane davvero autorevoli **non mostrano il
quadro americano**.

### ✅ AlmaLaurea — la fonte migliore, verificata sui PDF

Consorzio interuniversitario, indagine annuale, metodologia e modelli pubblicati con errori standard.
Ho scaricato **due edizioni** ed estratto **gli stessi coefficienti** dallo stesso modello, per avere un
confronto nel tempo a cavallo dell'adozione dell'AI generativa.

| Laureati in **informatica e tecnologie ICT** | Rapporto 2024 *(laureati 2023)* | Rapporto 2026 *(laureati 2025)* |
|---|---|---|
| occupati a 1 anno, *odds ratio* vs politico-sociale | **4,743** *(coeff. 1,557 · e.s. 0,107)* | **4,855** *(coeff. 1,580 · e.s. 0,115)* |
| premio retributivo mensile netto | **+184 €** | **+222,49 €** *(e.s. 15,57)* |

Occupabilità **stabile** (la differenza è dentro gli errori standard), premio salariale **in crescita**.
Contesto: l'occupazione dei laureati a un anno è salita a **81,2%** (primo livello) e **80,8%** (secondo),
+2,6 e +2,2 punti sulla rilevazione precedente.

⚠️ **Limite da dichiarare**: è un confronto **fra gruppi disciplinari**, non in valore assoluto nel tempo.
Dice «informatica va meglio di scienze politiche», non «va meglio di come andava». Se tutti i gruppi
fossero peggiorati insieme non lo vedremmo — ma l'occupazione complessiva è salita, quindi un crollo
generale nascosto non c'è.
📎 Rapporto 2026 · [almalaurea.it](https://www.almalaurea.it/document-download/sintesi-rapporto-almalaurea-2026-sugli-esiti-occupazionali-della-laurea)

### ✅ Excelsior–Unioncamere — primaria, ma misura un'altra cosa

*Tecnici programmatori* (cod. 3.1.2.1.0): **21.010** entrate previste 2025, **65%** di difficoltà di
reperimento (mancanza di candidati 73,8%, preparazione inadeguata 21,9%), 48% giovani.
*Analisti e progettisti di software*: fra le professioni più introvabili, difficoltà attorno al **70%**.

⚠️ Sono **intenzioni di assunzione dichiarate dalle imprese**, non assunzioni avvenute. Strumento
diverso da ADP, e più debole. Ma dice il contrario del racconto americano: il problema dichiarato non è
che i programmatori non servono, è che non si trovano.

---

## 🔴 Numeri italiani da correggere nel deck

### I. Il «78% delle organizzazioni fatica ad assumere» — **non esiste**
La cifra reale è **75%**, e viene da un **Osservatorio diverso** da quello a cui era attribuita:
> *«nel 2025 il **75%** delle organizzazioni italiane ha difficoltà ad assumere nuovo personale»*
> — Osservatorio **HR Innovation Practice**, PoliMi

E la qualificazione **«AI, big data, cybersecurity» non è nella fonte**: il testo dice solo *«circa la metà
del campione ha difficoltà soprattutto a trovare candidati con competenze tecniche adeguate»*.
Tre errori in un numero: cifra, attribuzione, contenuto.

### II. Il «76% degli annunci high-skill chiede competenze AI» — vero, ma senza denominatore è fuorviante
Testuale, Osservatorio **Artificial Intelligence** PoliMi, comunicato **febbraio 2026**, 17+ milioni di
annunci analizzati con Lightcast, periodo 2019–2025:
> *«Le più impattate sono le professioni **white-collar ad alta qualificazione**: il 76% degli annunci di
> lavoro per queste figure richiede anche competenze AI. Ma l'AI è presente anche nel **27% degli annunci
> per Chief Human Resources Officer** e nel **12% di quelli per Chief Marketing Officer**.»*

**Il problema è il denominatore.** Lo stesso comunicato dice che le posizioni che chiedono competenze AI
sono **44.000 su 3,2 milioni — l'1,4% del mercato**. I due numeri tornano solo perché «white-collar ad
alta qualificazione» è una categoria strettissima. Detto senza denominatore, la sala capisce «tre buoni
lavori su quattro ormai chiedono l'AI», che è falso — e l'1,37% è pubblicato dallo stesso Osservatorio.
**Se usi il 76%, usa anche il 27% CHRO e il 12% CMO**, che lo rendono onesto.

---

## 🟡 Da non usare: la stampa italiana di settore è contaminata

| Claim | Perché no |
|---|---|
| «−35% posizioni junior tech in UE nel 2024» | attribuito a *«LinkedIn, Indeed ed Eures»* insieme — tre piattaforme in blocco è il marchio di un dato riciclato senza fonte |
| «−72% annunci per software engineer nei primi 5 mesi 2026» | nessuna fonte, ordine di grandezza non credibile |
| Randstad, «oltre il 50% dei profili IT difficile da reperire» | stessa famiglia del +303% già tagliato |
| **LinkedIn «Barometro del primo impiego»**: entry-level −18,8%, manager −20,4%, senior −21,2%, Gen Z −2,5% | I numeri sono confermati da Forbes e Sole 24 Ore, **ma la metodologia dichiarata è «analizza milioni di dati»** — nessun periodo, campione o metodo. Dato di piattaforma non verificabile, e **non contiene nulla sugli sviluppatori**. Al massimo a voce, dichiarando che la metodologia non è pubblicata. |

### 🔴 E soprattutto: «Stanford rileva che dal 2022 l'occupazione tra gli sviluppatori software è scesa di circa il 20%»

**È falso, e gira sulla stampa italiana di settore.** Il ~20% (−0,193) è la stima per il **quintile più
esposto**, non per gli sviluppatori — e gli autori mostrano **apposta** che il risultato regge togliendo
le occupazioni informatiche (*«not specific to technology roles»*, §3 Robustness). È esattamente
l'errore che abbiamo eliminato dal deck, riprodotto da altri.

**Opportunità**: se qualcuno in sala te lo cita, hai la risposta pronta ed è un ottimo momento.

---

# Riepilogo operativo

**Da fare prima di impaginare** (in ordine di urgenza):
1. 🔴 Riscrivere la **slide 8** con i numeri in livelli della versione 2026 (11% vs 10%)
2. 🔴 Correggere **slide 17**: 46% diffida / 33% si fida; esperti 2,5% / 20,7%
3. 🔴 Correggere fonte e data del **79%** in slide 5 (aprile 2025, report sul software development)
4. 🟡 **Togliere +303% Randstad** dalla slide 24, o verificarlo sul report originale
5. 🟠 Dire **n=16** quando citi METR, e **n=21 qualitativo** quando citi Prather
6. 🟠 Dire "**17 punti**", non "17%", sull'RCT Anthropic
7. ❌ **Non** usare Apiiro (vendor research senza metodologia pubblicata) — l'ancora dell'Atto 2 resta **Veracode**, che è un benchmark riproducibile
8. ⚠️ Aggiungere i **quindici secondi di cautela** su Stanford
9. 🇮🇹 **Blocco italiano rifatto** (24 set): 78% inesistente → 75% altro Osservatorio; 76% solo col denominatore; slide 17 ricostruita su AlmaLaurea. Vedi §Verifica del blocco italiano.
10. ⛔️ **Tagliata la slide del 79% Anthropic** (23 set 2026) — vedi #3 e §G. Il legame metodologico con Stanford resta come **risposta per il Q&A**.

**Verificato ma non modificato**: tutti i numeri degli esercizi in `esercizi-aula.md` li ho prodotti ed eseguiti io in questa sessione — i test verdi, l'exploit XSS, la log injection, il paradosso dei punti fedeltà (63,44 € → 68,20 €) e le divergenze da un centesimo sono riproducibili e non dipendono da fonti esterne.
