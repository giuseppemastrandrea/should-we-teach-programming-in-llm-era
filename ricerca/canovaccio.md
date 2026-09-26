# Dovremmo ancora insegnare a programmare nell'era degli LLM?
## Canovaccio slide — Come To Code 2026

**Evento**: Come To Code 2026 — 26–27 settembre 2026, Pignola (PZ), Basilicata
**Organizzatore**: PLUG APS · Claim: *"The tech awakening has begun"* / *"Train you must. Not with a saber — with knowledge"*
**Speaker**: Giuseppe Mastrandrea
**Titolo in programma**: *Dovremmo ancora insegnare a programmare nell'era degli LLM?*

**Durata ipotizzata**: 45 minuti · **41 slide** (erano 45), di cui 6–8 minuti di interazione con la sala
**Fonti che la sala deve tracciare: 11** (erano 20 — vedi "Cosa ho tolto e perché" in fondo)
Se lo slot è di 30 minuti: tieni dell'Atto 2 le sole slide 16 e 17, e porta gli esercizi a due (Prompt Problem + Vulnerabilità).

> ✅ **Tutti i numeri di questo canovaccio sono stati verificati sulle fonti primarie il 21 settembre 2026.** Il dettaglio della verifica — cosa è stato corretto, cosa abbandonato e perché — è in `audit-fonti.md`. Dove una cifra è fragile, la slide lo dice.

**Legenda**: 🖼️ = cosa si vede · 🗣️ = cosa dici · 📎 = fonte da mettere in piccolo o nelle note

---

# ATTO 0 — IL PENDOLO (5 slide, ~5 min)

### Slide 1 — Cover
🖼️ Titolo del talk. Sotto, in piccolo: nome, Come To Code 2026.
🗣️ Niente. Si legge da sola. Eventualmente: "il titolo è una domanda vera, non retorica. Alla fine vi do la mia risposta, ma voglio che ci arriviate con i dati in mano."

---

### Slide 2 — About me
🖼️ Una foto. Tre righe, non di più:
- **Sviluppatore** (il passato)
- **Insegnante di informatica** (il presente)
- **Formatore upskill/reskill per adulti** (il presente, quello scomodo)

🗣️ Il punto di questa slide non è il CV, è **stabilire da dove parli**: "sono le tre persone che questo problema riguarda contemporaneamente. Quello che scriveva codice e ora lo fa scrivere. Quello che deve decidere cosa mettere nel programma di quest'anno. E quello che ha davanti persone di 40 anni che si stanno riqualificando e mi chiedono se stanno buttando via un anno di vita."
👉 Chiudi con: *"Non ho una risposta comoda. Ho dei dati."*

---

### Slide 3 — Il pendolo *(la slide che ti ha chiesto la pancia)*
🖼️ Costruzione a comparsa, una coppia alla volta, con **frecce** che collegano. Foto piccola e circolare + citazione a fianco.

✅ **Citazioni verificate — usale così come sono scritte qui.**

| # | Chi | Citazione | Quando / dove |
|---|---|---|---|
| 1 | **Steve Jobs** | *"Everybody in this country should learn how to program a computer, should learn a computer language, **because it teaches you how to think**. So I view computer science as a liberal art."* | 1995, intervista di Robert X. Cringely per *Triumph of the Nerds* (PBS) |
| 2 | **Barack Obama** | *"**Don't just buy a new video game — make one. Don't just download the latest app — help design it. Don't just play on your phone — program it.**"* *(e poco prima: "Learning these skills isn't just important for your future — it's important for America's future")* | 9 dic 2013, messaggio video per il lancio dell'**Hour of Code** (Computer Science Education Week) |
| 3 | **Jensen Huang** | *"Over the course of the last 10 years, 15 years, almost everybody would tell you that it is vital that your children learn computer science, that everybody should learn how to program. **And in fact, it's almost exactly the opposite.** It is our job to create computing technology such that **nobody has to program**, and that the programming language is human."* | 12 feb 2024, World Governments Summit, Dubai |
| 4 | **Andrew Ng** | *"The bar to coding is now lower than it ever has been."* + *"People that code — be it CEOs and marketers, recruiters, not just software engineers — will really get more done than ones that don't."* | nov 2025, Snowflake Build |
| 5 | **Dario Amodei** | *"I think we'll be there in **three to six months**, where AI is writing **90% of the code**. And then in twelve months, we may be in a world where AI is writing **essentially all** of the code."* | 10 mar 2025, Council on Foreign Relations |
| 6 | **Jensen Huang** (di nuovo) | *"I pretty much **disagree with almost everything** he says."* | 11 giu 2025, conferenza stampa VivaTech, Parigi |
| 7 | **Nickle LaMoreaux**, CHRO IBM | *"The companies three to five years from now that are going to be the most successful are those companies that **doubled down on entry-level hiring** in this environment."* | 12 feb 2026, conferenza a New York |

🗣️ Ritmo veloce, quasi elenco. L'effetto comico arriva da solo alla **6** (Huang che contraddice Amodei) e alla **7** (IBM che contraddice tutti).
📎 [Jobs 1995](https://www.codetoday.co.uk/post/2018/07/25/steve-jobs-1995-everybody-should-learn-to-program-a-computer-because-it-teaches-you-how) · [Obama 2013](https://obamawhitehouse.archives.gov/blog/2013/12/09/don-t-just-play-your-phone-program-it) · [Huang 2024](https://www.tomshardware.com/tech-industry/artificial-intelligence/jensen-huang-advises-against-learning-to-code-leave-it-up-to-ai) · [Ng 2025](https://www.entrepreneur.com/business-news/google-brain-founder-you-should-learn-how-to-vibe-code/499473) · [Amodei 2025](https://finance.yahoo.com/news/anthropic-ceo-says-ai-could-193020957.html) · [Huang su Amodei](https://fortune.com/2025/06/11/nvidia-jensen-huang-disagress-anthropic-ceo-dario-amodei-ai-jobs) · [IBM](https://www.cio.com/article/4134276/ibm-looks-beyond-short-term-ai-gains-tripling-entry-level-hiring.html)

⚠️ **Due correzioni rispetto alla prima bozza, importanti:**
- **Amodei**: la citazione completa è *"90% in 3–6 mesi"*, non "entro il 2026". E **nello stesso intervento** ha aggiunto: *"Il programmatore deve comunque specificare quali sono le condizioni di ciò che stai facendo, qual è l'app complessiva che stai cercando di fare, quali sono le decisioni di design"* — cioè ha detto **la tesi del tuo talk**. Se la usi come citazione bonus, è un colpo notevole: non è un avversario, è un testimone.
- **LaMoreaux**: la frase *"we are tripling our entry-level hiring, and yes, that is for software developers…"* circola molto ma l'ho trovata **solo su blog secondari**. Non metterla tra virgolette. Usa quella verificata sopra, e il **fatto** (IBM triplica le assunzioni entry-level USA nel 2026, annunciato il 12 febbraio) come testo separato.
- **Ng**: la frase *"more people should learn to code, not fewer"* che avevo proposto è una parafrasi in circolazione. Le due sopra sono quelle reali.

🎯 **Obama: perché è la riga che ti conviene di più.** Non è solo una citazione in più, è **un innesco narrativo**. Quel video del 9 dicembre 2013 lancia l'**Hour of Code**. E nell'ottobre 2025 Code.org trasforma l'Hour of Code in **Hour of AI**. Hai un arco perfetto da richiamare più avanti:
> *"Nel 2013 il Presidente degli Stati Uniti registra un video per dire ai ragazzi 'non limitarti a giocare col telefono, programmalo'. Nel 2025 l'organizzazione che aveva creato quell'iniziativa la ribattezza **Hour of AI**."*
Hadi Partovi però precisa che il coding **resta al centro** e che l'obiettivo non è mai stato produrre software engineer, ma cittadini che capiscono come funzionano le cose. Cioè: **non è una resa, è uno spostamento** — ed è esattamente la tesi del tuo talk. 📎 [THE Journal](https://thejournal.com/articles/2025/10/02/codeorg-reinvents-hour-of-code-as-hour-of-ai.aspx)
👉 **Dove usarlo**: o come chiusura dell'Atto 0 (una slide in più tra la 4 e la 5), oppure — meglio — tenutelo in tasca e sparalo nell'**Atto 4**, quando parli di come cambiano le skill. Non usarlo due volte.

💬 **Citazione Obama alternativa**, se preferisci il registro istituzionale a quello pop:
> *"In the new economy, computer science isn't an optional skill — it's a **basic skill**, right along with the three R's."*
> — 30 gennaio 2016, lancio dell'iniziativa **Computer Science For All** (4 miliardi di dollari)
È più forte come affermazione di policy e invecchia in modo più interessante (nel 2016 "basic skill" significava *scrivere* codice; nel 2026 significa *giudicarlo*). Ma la triade *"make one / help design it / program it"* funziona molto meglio detta ad alta voce, e ti regala l'aggancio all'Hour of AI. **Io userei quella del 2013.** 📎 [whitehouse.gov](https://obamawhitehouse.archives.gov/blog/2016/01/30/computer-science-all)

💡 *Bonus se vuoi il colpo di grazia*: aggiungi Karpathy che nel **feb 2025** conia "vibe coding" e nel **mag 2026** intitola il suo keynote *"From vibe coding to **agentic engineering**"*. Ma sii onesto in voce: **non è una contraddizione, è un'evoluzione** — e infatti è quella che useremo dopo.

---

### Slide 4 — Payoff: "Tutto e il contrario di tutto"
🖼️ Le **sette** facce della slide precedente, tutte insieme, piccole, in griglia. Sopra, grande: **"Tutto e il contrario di tutto."**
🗣️ *"In trent'anni — da Jobs a IBM — il pendolo ha fatto un giro completo e mezzo. E queste sono le persone che decidono dove va l'industria. Io invece devo decidere cosa scrivo nel programma di settembre. Quindi smetto di guardare le dichiarazioni e guardo i dati."*

---

### Slide 5 — "Oh shit, here we go again"
🖼️ Il meme (CJ, GTA San Andreas). Accanto, due colonne:

| Quello che **potremmo** fare con l'AI | Quello che **facciamo** davvero |
|---|---|
| Aumentare le persone | Sostituirle |
| Far crescere i junior più in fretta | **Non assumerli più** |
| 21% delle sessioni su Claude Code | **79%** delle sessioni su Claude Code |
| *augmentation* | *automation* |

🗣️ *"Il dato a destra non è un'opinione. Anthropic ha analizzato mezzo milione di conversazioni di coding: su **Claude Code**, l'agente, il **79%** è classificato come automazione — l'AI che esegue il compito. Su **Claude.ai**, la chat, è il **49%**. Stesso modello, stesso momento, stessa azienda: cambia lo strumento e il default si ribalta. E il default dell'agente è: fallo tu."*
*"Tenete a mente questa parola — automazione contro aumento — perché tra tre slide diventa la cosa più importante del talk."*
📎 **Attenzione alla fonte**: NON è l'Economic Index di gennaio 2026 (lì Claude Code non compare). È [*AI's Impact on Software Development*](https://anthropic.com/research/impact-software-development), **28 aprile 2025**, su conversazioni del **6–13 aprile 2025**.
⚠️ **Sono dati vecchi di 17 mesi, su Claude Code appena uscito.** Anticipa l'obiezione tu: *"dati di aprile 2025, quindi vecchi — se qualcuno ha numeri più freschi me li dica. Ma il confronto che conta è tra i due strumenti nello stesso momento, e quello non invecchia."* Il confronto 79 vs 49 regge; "il 79% oggi" no.

---

# ATTO 1 — I NUMERI (10 slide, ~11 min)

### Slide 6 — Titolo di atto
🖼️ **"1. Cosa dicono i dati"** — slide di stacco, nera, tre parole.
🗣️ *"Niente aneddoti. Buste paga."*

---

### Slide 7 — I canarini nella miniera
🖼️ Copertina del paper + un canarino. Grande: **"Canaries in the Coal Mine?"** — Brynjolfsson, Chandar, Chen — Stanford Digital Economy Lab.
Sotto, piccolo: *dati di busta paga ADP · 25+ milioni di lavoratori USA · non sondaggi, non annunci*
🗣️ Spiega perché questo studio conta più degli altri: non chiede alle persone cosa pensano, guarda chi viene pagato.
📎 [Stanford DEL](https://digitaleconomy.stanford.edu/publication/canaries-in-the-coal-mine-six-facts-about-the-recent-employment-effects-of-artificial-intelligence/)

---

### Slide 8 — Il grafico (la slide più importante dell'atto)
🖼️ Un grafico a due linee da novembre 2022 a giugno 2026. Numeri grandi sopra — **questi, verificati sul paper, versione agosto 2026**:

> ### Lavoratori **22–25 anni** nelle occupazioni **più esposte** all'AI: **−11%**
> ### Lavoratori **22–25 anni** nelle occupazioni **meno esposte**: **+10%**
> *novembre 2022 → giugno 2026*

🗣️ *"Stessa fascia d'età. Stesso periodo. Stesso Paese. L'unica differenza è **quanto quel lavoro è esposto all'AI**. Undici punti sotto da una parte, dieci sopra dall'altra."*
Pausa. Lascia la slide in silenzio due secondi.

📎 Citazione letterale dal paper: *"employment of 22–25-year-olds in the two most exposed quintiles fell about **11%** between November 2022 and June 2026, while employment of the same age group in the three least-exposed quintiles grew about **10%**."*

✅ **Perché questi numeri e non altri**: sono in livelli, sulla stessa fascia d'età, senza modelli statistici di mezzo — e sono quelli che **gli autori hanno scelto di mettere in evidenza nella versione più recente**, abbandonando le stime di regressione.
⚠️ **Non usare il "16% controllando per gli shock aziendali"**: era la stima di regressione della vintage settembre 2025, che gli autori hanno **esplicitamente de-enfatizzato** (*"Earlier versions of this study headlined regression estimates… We now emphasize the simpler descriptive divergence"*).

💡 **Se vuoi il dato sugli sviluppatori software specificamente** — ed è quello che la sala vuole sentire — puoi dirlo, ma **con la sua data**:
> *"By September 2025, employment for software developers aged 22-25 declined **nearly 20%** compared to **its peak in late 2022**."*
È della versione **novembre 2025**, con dati fino a **settembre 2025**. Nella versione di agosto 2026 il caso degli sviluppatori è finito nell'appendice, senza percentuale. Quindi: *"nella versione dell'anno scorso, gli sviluppatori 22–25 erano quasi il 20% sotto il loro picco del 2022"*. Non attribuirlo all'update 2026.
📎 [update ago 2026](https://digitaleconomy.stanford.edu/news/canariesaug26/) — il gap "kept-pace" è passato dal **15%** (lug 2025) al **19%** (giu 2026)

---

### Slide 9 — Come avviene il taglio
🖼️ Una sola frase, grande, virgolettata dal paper:
> *"principalmente attraverso la **riduzione delle assunzioni** di giovani, non attraverso un aumento dei licenziamenti"*

🗣️ *"Nessuno vi ha licenziato. Semplicemente la porta non si è aperta. Ed è per questo che non fa notizia: un licenziamento è un evento, una mancata assunzione è un non-evento. Non c'è niente da fotografare."*

---

### Slide 9-bis — ⚠️ I limiti, detti da te prima che te li dicano *(15 secondi, non saltarla)*
🖼️ Una riga sola, virgolettata **dall'abstract del paper**:
> *"We interpret these facts as **early, descriptive indicators** — canaries in the coal mine — **rather than causal estimates**."*

🗣️ *"Tre avvertenze che mettono gli autori stessi: le occupazioni esposte e non esposte divergevano già prima di ChatGPT, attorno al COVID; l'effetto si attenua se controlli per il titolo di studio — anche se loro stessi dicono che potrebbe essere proprio quello il canale attraverso cui l'AI agisce; e il campione ADP è più marcato dei benchmark nazionali."*
*"Quindi non vi sto dicendo 'l'AI ha causato questo'. Vi sto dicendo che il canarino ha smesso di cantare. È diverso, ed è comunque il motivo per cui si esce dalla miniera."*

💡 **Perché vale la pena**: quindici secondi e diventi l'unico speaker della giornata che cita i limiti dei propri dati. Se in sala c'è un economista, sei coperto; se non c'è, hai comunque guadagnato credibilità per tutto il resto del talk.

---

### Slide 10 — Il fatto che cambia tutto: automazione vs aumento
🖼️ Due colonne, con il grafico che diverge:
- **Dove l'AI automatizza** → occupazione giovanile ↓↓
- **Dove l'AI complementa** → occupazione **piatta o in crescita**, soprattutto tra gli esperti

Sotto: **conoscenza codificata** (libri, tutorial, Stack Overflow) → sostituibile
**conoscenza tacita** (esperienza, giudizio) → resiste

🗣️ *"Questo è il fatto numero sei del paper e nessuno lo cita mai, perché è quello che non fa clickbait. Non è 'l'AI distrugge i posti di lavoro'. È: **la stessa tecnologia, usata in due modi diversi, produce disoccupazione o produttività**. E la differenza la fa come la usi — cioè qualcosa che si può insegnare."*
*"Ricordate la slide di CJ? Il 79%. Stiamo scegliendo il modo sbagliato per default."*

---

### Slide 11 — E in Italia?
🖼️ Tre blocchi numerici, uno per fonte:

| | |
|---|---|
| **50,9%** | dei **laureati** che le imprese cercano è di **difficile reperimento** (57,3% per i diplomati ITS) — su 670.000 laureati e 120.000 ITS richiesti *(Excelsior–Unioncamere, dati 2025)* |
| **76%** | degli annunci per white-collar ad alta qualificazione chiede **competenze AI**; il **78%** delle organizzazioni fatica ad assumere *(Osservatori PoliMi)* |

✂️ *Tolto AlmaLaurea ("Informatica tra i gruppi con le più alte chance occupazionali"): è una posizione in classifica, non un numero, e non aggiunge nulla ai due sopra. Costringeva la sala a registrare una terza sigla per zero informazione in più.*

🗣️ *"In Italia il problema non è che ci sono troppi informatici. È che le aziende non trovano quelli che cercano. E tra un attimo vediamo **cosa** cercano, perché è cambiato."*
📎 [Excelsior](https://www.unioncamere.gov.it/comunicazione/comunicati-stampa/excelsior-introvabili-la-meta-dei-laureati-e-dei-diplomati-its) · [Osservatori PoliMi](https://www.osservatori.net/artificial-intelligence/)

---

### Slide 12 — I ragazzi lo hanno già capito
🖼️ Due numeri enormi, affiancati:

> ## 70%
> dei laureandi in Informatica è **pessimista** sulla propria carriera
> *(64% dei pessimisti indica l'AI come causa)*

> ## 42%
> **usa l'AI generativa ogni giorno**
> *(media degli altri laureandi: 24%)*

E sotto, il contrasto che vale più della percentuale (fonte primaria NSC, 11 agosto 2026):
> Iscrizioni a **informatica**, primavera 2026: **−8,4%** (quadriennali) · **−11,2%** (biennali) · graduate **−14%**
> Iscrizioni universitarie **totali**, stesso periodo: **+1,3%**
> NSC la definisce *"un'anomalia nelle tendenze di iscrizione più ampie"*.

💡 E il dato che non cita nessuno: la **persistenza al secondo semestre** degli studenti di informatica è la **più bassa tra i dieci corsi di laurea principali (85,0%)**. Non solo se ne iscrivono meno — quelli che si iscrivono mollano di più.

🗣️ *"Sono contemporaneamente i più spaventati dall'AI e quelli che la usano di più. Provate a immaginare di studiare così. Io non devo immaginarlo: ce li ho in aula."*
📎 [Handshake Class of 2026](https://joinhandshake.com/research/economic-research/class-of-2026-spotlight-computer-science-majors/) · [Fortune / National Student Clearinghouse](https://fortune.com/2026/08/06/computer-science-enrollment-plunging-ai-college-campus/)

---

### Slide 13 — Il contro-trend: IBM
🖼️ Logo IBM. In grande il **fatto**, non la citazione:

> ## IBM triplica le assunzioni entry-level negli USA nel 2026
> *annunciato il 12 febbraio 2026 · l'azienda non ha diffuso cifre assolute*

E sotto, la citazione verificata di Nickle LaMoreaux (CHRO):
> *"Le aziende che tra tre-cinque anni avranno più successo sono quelle che **hanno raddoppiato sulle assunzioni entry-level** in questo periodo."*

Sotto, la riga che conta:

> **Non hanno solo assunto di più. Hanno riscritto il ruolo.**
> Meno coding di routine → più contatto col cliente e **validazione degli output dell'AI**
> Il senior fa: *evaluation, pattern recognition, e insegna ai giovani a esercitare il giudizio*

🗣️ *"E la motivazione che danno è cinica nel modo giusto: chi taglia i junior oggi tra tre anni non ha i mid-level, e deve comprarseli dai concorrenti a caro prezzo."*
📎 [Axios](https://www.axios.com/2026/02/13/ai-ibm-tech-jobs) · [CIO](https://www.cio.com/article/4134276/ibm-looks-beyond-short-term-ai-gains-tripling-entry-level-hiring.html)

---

### Slide 14 — 🪜 **La scala senza i pioli** *(slide cardine dell'atto)*
🖼️ Illustrazione: una scala a pioli in cui **i primi tre pioli mancano**. In cima, una figura. In basso, una figura che guarda in su e non può salire.
Testo minimo: **"Nessuno ha tolto la scala. Hanno tolto i primi pioli."**

🗣️ Qui rallenta. È il punto di svolta del talk.
*"La seniority non si compra e non si scarica: si costruisce facendo il lavoro da junior. Il CRUD noioso, il bug stupido cercato per tre ore, la code review in cui ti massacrano. Erano i pioli. Se automatizzi i pioli bassi, la scala resta in piedi — ma da dove escono i senior del 2031?"*
*"Questo non è un problema dei giovani. È un problema di chi tra dieci anni avrà bisogno di qualcuno che sappia guardare 50.000 righe generate e dire 'no, qui c'è qualcosa che non va'."*

---

# ATTO 2 — IL CODICE È GRATIS. E ALLORA? (3 slide, ~5 min)

> ✂️ **Atto dimagrito.** Prima erano 7 slide e 4 fonti con slide propria (Veracode, Stack Overflow, Octoverse, METR). Ora sono 2 slide di contenuto, con l'ancora su **Veracode** — l'unica fonte di quest'area che pubblica un **benchmark riproducibile**. Octoverse e Stack Overflow restano come **righe** dentro la slide 17. METR e Apiiro sono tagliati: il perché è in fondo, in "Cosa ho tolto e perché".

### Slide 15 — Titolo di atto
🖼️ **"2. Il codice è gratis. E allora?"**

---

### Slide 16 — Circa la metà *(l'ancora dell'atto)*
🖼️ Numero enorme: **~50%**. Sotto: *del codice generato dagli LLM non supera i test di sicurezza.*
Riga di metodo, in piccolo ma **leggibile** — è quella che rende il numero credibile:
> **100+ modelli · 80 task standardizzati · quattro linguaggi · rimisurato a ogni ciclo**

Dettagli: Java **72%** di fallimento · C# 45% · JavaScript 43% · Python 38% · **XSS: i modelli falliscono nell'86% dei casi**
E la riga cattiva: **"Invariato da un anno e mezzo."**

🗣️ *"Ottanta task standardizzati, più di cento modelli, quattro linguaggi. È un benchmark: **chiunque può rifarlo**. E il punto non è il numero in sé, è che non si muove — i modelli sono migliorati in tutto, tranne che qui."*

⚠️ **Precisione**: Veracode 2025 dà **45%** di fallimento; l'aggiornamento primavera 2026 ragiona in *tassi di superamento* e i valori oscillano **tra 45% e 55%**. Non dire "45% invariato": di' **"circa la metà, invariato"**, che regge su entrambi.
📎 [Veracode 2025](https://www.veracode.com/blog/genai-code-security-report/) · [primavera 2026](https://www.veracode.com/blog/spring-2026-genai-code-security/)

---

### Slide 17 — Il combinato disposto *(la slide che chiude l'argomento)*
🖼️ Tre righe che compaiono una alla volta, poi la conclusione:

> **36 milioni** di nuovi sviluppatori su GitHub in un anno. **Quasi l'80%** usa Copilot **entro la prima settimana**.
> **Circa la metà** del codice generato non supera i test di sicurezza — e non migliora da un anno e mezzo.
> Gli sviluppatori **esperti** sono quelli che se ne fidano **meno**: *"more developers actively distrust the accuracy of AI tools (**46%**) than trust it (**33%**)"*.

> ### Stiamo formando una generazione che si fida di più proprio dello strumento di cui gli esperti si fidano di meno — senza darle gli strumenti per verificarlo.

🗣️ Leggi la conclusione lentamente. È la tesi del talk in una frase.
*"E notate chi sono i più scettici: non i nostalgici. Quelli che lo usano meglio. Il 2,5% degli sviluppatori esperti si fida molto. Il 20,7% diffida molto."*

📎 [Octoverse 2025](https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/) · [Veracode](https://www.veracode.com/blog/genai-code-security-report/) · [Stack Overflow 2025](https://survey.stackoverflow.co/2025/)
⚠️ Octoverse dice *"**nearly** 80%"*: di' "quasi l'80%".

---

# ATTO 3 — KARPATHY: PAVIMENTO E SOFFITTO (4 slide, ~5 min)

### Slide 18 — Titolo di atto
🖼️ **"3. Dove va a finire il mestiere"**

---

### Slide 19 — Software 3.0
🖼️ Foto Karpathy + la progressione:
- **Software 1.0** → scrivi codice
- **Software 2.0** → alleni pesi
- **Software 3.0** → **scrivi contesto** (prompt, esempi, tool, memoria, istruzioni)

Citazione: *"Programming shifts from writing code to **writing context**."*
🗣️ *"Quello che ci resta da fare è dire con precisione a una macchina cosa vogliamo. Che è, se ci pensate, la definizione di programmare che avevamo prima che esistessero i linguaggi di programmazione."*
📎 [Karpathy, Sequoia Ascent, mag 2026](https://karpathy.bearblog.dev/sequoia-ascent-2026/)

---

### Slide 20 — Pavimento e soffitto *(l'immagine da rubare)*
🖼️ Una stanza in sezione. Il **pavimento** che si alza. Il **soffitto** che si alza. Due frecce.

| **Vibe coding** alza il **pavimento** | **Agentic engineering** alza il **soffitto** |
|---|---|
| Chiunque può costruire software | Il professionista va 10× più veloce |
| Basta descrivere | Specifiche, review, test, permessi, confini |
| Il risultato è *plausibile* | Il risultato è *verificato* |

🗣️ *"Questa è la distinzione più utile che ho trovato in tre anni di discussioni. E notate: non sono in competizione. Il pavimento che si alza è una **bellissima notizia** — più gente costruisce software. Il punto è che tra il pavimento e il soffitto c'è una distanza, e quella distanza si chiama ancora ingegneria del software."*
*"Il mio lavoro, e forse il vostro, è **portare la gente dal pavimento al soffitto**. Non è mai stato così chiaro."*

---

### Slide 21 — Le due frasi da portare a casa
🖼️ Due citazioni, una sopra l'altra, nient'altro.

> *"Puoi delegare la memorizzazione delle API. Le decisioni sulla **forma del sistema** — identità, confini di sicurezza, integrità dei dati — restano umane."*
> — Karpathy, 2026

> *"Il programma non è il codice: è la **teoria** che i programmatori hanno in testa su come il codice rispecchia il mondo. Il codice senza la teoria è morto."*
> — Peter Naur, *Programming as Theory Building*, **1985**

🗣️ *"Quarantun anni di distanza. Naur diceva che se la teoria muore — se il team si scioglie — il programma è morto anche se il codice compila, perché nessuno sa più **perché** è fatto così."*
*"Il codice generato da un LLM è codice **senza teoria**. A meno che qualcuno la costruisca leggendolo. E quel qualcuno deve saper leggere."*
💡 Se ti resta una battuta: *"Nel 1985 Naur non aveva in mente Claude. Aveva in mente il vostro collega che si è licenziato a marzo."*

---

# ATTO 4 — LE NUOVE SKILL (3 slide, ~4 min)

### Slide 22 — Cosa sta comprando davvero il mercato
🚨 **ATTENZIONE — questa slide va rifatta o verificata prima di usarla.**

I numeri Randstad (+303% pensiero critico, +122% AI auditing, ecc.) **non sono confermati da nessuna fonte Randstad primaria**: esistono solo su testate italiane che riportano la stessa sintesi. Sul materiale Randstad compaiono numeri *diversi* (prompt engineering +403%; promozioni 3,5× più veloci, non 2,5×). È il numero più grande della slide ed è l'unico che non regge a una verifica.

**Due opzioni:**

**A) Scarica il report *Age of Augmentation* e verifica.** Se i numeri ci sono, è una slide ottima: 427.768 annunci italiani sono un dato che nessun altro speaker avrà.

**B) Rifà la slide con dati verificabili** — funziona quasi uguale:

| | |
|---|---|
| **76%** | degli annunci per white-collar ad alta qualificazione in Italia richiede **competenze AI** *(Osservatori PoliMi)* |
| **78%** | delle organizzazioni italiane **fatica ad assumere**, soprattutto su AI, Big Data, Cybersecurity *(Osservatori PoliMi)* |
| **50,9%** | dei laureati cercati è **introvabile** *(Excelsior–Unioncamere 2025)* |

✂️ *Ho tolto il WEF Future of Jobs ("39% delle competenze cambia entro il 2030", "analytical thinking n.1 per 7 aziende su 10"). È il report che cita chiunque in qualunque talk: non ti dà credibilità, te ne toglie, perché suona come riempitivo. I due numeri italiani sopra sono più specifici, meno noti e nessun altro speaker li avrà.*

🗣️ *"Il mercato italiano non chiede meno informatici. Chiede informatici che sappiano **giudicare** — e non li trova. Un'offerta su due per un laureato resta scoperta."*
📎 [Osservatori PoliMi](https://www.osservatori.net/artificial-intelligence/) · [Excelsior](https://www.unioncamere.gov.it/comunicazione/comunicati-stampa/excelsior-introvabili-la-meta-dei-laureati-e-dei-diplomati-its) · [WEF](https://www.weforum.org/publications/the-future-of-jobs-report-2025/in-full/3-skills-outlook/)

---

### Slide 23 — Bloom rovesciato
🖼️ La piramide di Bloom classica **capovolta**, con una freccia rossa.

| Prima | Adesso |
|---|---|
| *Creare* era la cima (difficile, costoso) | **Creare è gratis** |
| *Ricordare/Capire* era la base | **Valutare e analizzare sono il collo di bottiglia** |

🗣️ *"Abbiamo costruito trent'anni di curricula che salgono dal basso: prima la sintassi, poi scrivi, poi — se c'è tempo, e non c'è mai — leggi e progetti. Quel percorso ha senso solo se scrivere è la parte difficile. Non lo è più."*
*"Non significa 'non insegniamo più a scrivere'. Significa che scrivere non è più il **traguardo**: è il **mezzo** per costruire la capacità di giudicare."*

---

### Slide 24 — La lista
🖼️ Sei voci, secche:
1. **Leggere** codice che non hai scritto
2. **Specificare** in modo non ambiguo (il prompt è una specifica)
3. **Decomporre** un problema
4. **Debuggare** ciò che non hai scritto
5. **Valutare** criticamente un output sicuro di sé anche quando sbaglia
6. **Sapere quando fermarti** e non delegare

🗣️ *"Questa lista non è nuova. È **la** lista. È quello che abbiamo sempre detto di voler insegnare e che poi valutavamo con 'scrivi una funzione che...'. La differenza è che adesso non possiamo più fingere."*

---

# ATTO 5 — SI PUÒ INSEGNARE? (6 slide, ~7 min)

### Slide 25 — Titolo di atto
🖼️ **"4. Ma allora l'AI in aula: sì o no?"**
🗣️ *"Domanda sbagliata. Ve lo dimostro con quattro studi."*

---

### Slide 26 — L'esperimento di Anthropic
🖼️ Setup a sinistra, risultato a destra:
*52 sviluppatori · libreria nuova (Trio, async) · metà con AI, metà a mano · quiz subito dopo*

> ## 50% vs 67%
> **17 punti percentuali** · *"quasi due voti di differenza"* — Cohen's d = 0,738 · p = 0,01
> Il gap più grande: **sulle domande di debugging**
> La velocità: **+2 minuti** con l'AI *(non significativo)*

🗣️ *"Hanno risparmiato due minuti e hanno capito due voti in meno. E lo pubblica **l'azienda che vende l'agente di coding**."*

⚠️ **Non dire "diciassette per cento in meno".** Anthropic scrive *"17% lower"*, ma i punteggi grezzi sono 50 e 67: sono **17 punti percentuali**, che in termini relativi sarebbe un −25%. Di' *"diciassette punti"* oppure *"cinquanta contro sessantasette"*. Il *"quasi due voti"* invece è testuale e puoi usarlo.
📎 [Anthropic, gen 2026](https://www.anthropic.com/research/AI-assistance-coding-skills)

---

### Slide 27 — ⭐ I sei pattern *(la slide più utile del talk)*
🖼️ Due colonne, verde e rossa.

| 🔴 Sotto il **40%** | 🟢 Sopra il **65%** |
|---|---|
| **Delega totale** — "fammelo tu" | **Genera, poi chiedi spiegazioni** |
| **Reliance progressiva** — inizi chiedendo, finisci delegando | **Codice + spiegazione insieme** |
| **Debug iterativo** — "aggiusta" invece di "spiega" | **Conceptual inquiry** — solo domande concettuali, errori risolti da solo |

E sotto, in rosso o evidenziato:
> ### Il gruppo "conceptual inquiry" era anche il **secondo più veloce in assoluto**.

🗣️ *"Questo distrugge l'alibi del trade-off. Non è 'o vai veloce o impari'. Chi usa l'AI per **capire** va veloce **e** impara. Chi la usa per **delegare** va uguale e non impara niente."*
*"E allora la domanda non è più 'AI sì o no'. È: **quale di queste sei colonne stiamo insegnando?** Perché se non insegniamo niente, il default è la colonna rossa."*

🙋 **Momento interattivo n.1** (30 secondi, gratis): *"Alzate la mano: in quale di queste sei vi riconoscete stamattina?"* — funziona sempre, e mette la sala dentro il problema invece che a guardarlo.

---

### Slide 28 — Lo stesso modello, due risultati opposti
🖼️ Tre barre: *controllo · GPT Base · GPT Tutor*. Due momenti.

| | Durante la pratica | **All'esame senza AI** |
|---|---|---|
| **GPT Base** (ChatGPT normale) | +48% | ### −17% |
| **GPT Tutor** (stesso modello, guardrail: dà hint, non risposte) | **+127%** | ### nessun danno |

*~1.000 studenti · PNAS 2025 · Bastani et al.*

🗣️ *"Stesso modello. Stesso identico GPT-4. Cambia solo come è stato **impacchettato**. Con i guardrail raddoppi l'apprendimento; senza, chi lo usa finisce **sotto** chi non l'ha mai avuto."*
*"Ecco perché 'AI sì o no' è la domanda sbagliata. La domanda è: **AI progettata come**. E quella è una decisione didattica, non tecnologica."*
📎 [PNAS](https://www.pnas.org/doi/10.1073/pnas.2422633122)

---

### Slide 29 — Il divario che si allarga ⚠️
🖼️ Due curve che divergono. Titolo: **"The Widening Gap"** — Prather et al., ICER 2024.
*Studio **qualitativo**: 21 studenti, 21 sessioni di laboratorio con osservazione, interviste ed **eye-tracking**.*

> Chi **accelerava** usava la GenAI per scrivere codice che sapeva già di voler scrivere, e ignorava i suggerimenti sbagliati.
> Chi **arrancava** ha visto le proprie difficoltà metacognitive **aggravarsi**, e ne sono emerse di nuove.
> Finivano con *"dissonanza cognitiva sulla propria capacità di risolvere problemi, convinti di aver fatto meglio di quanto avessero fatto"*, e con una…

> # illusione di competenza

⚠️ **Dì che sono 21 e che è qualitativo** — con l'eye-tracking è normale, e toglie l'obiezione. Non dire "studenti con voti e autoefficacia più alti": quella formulazione girava nelle sintesi ma non è nell'abstract. **"Illusione di competenza" è testuale** ed è più forte.

🗣️ Qui abbassa la voce. È la parte personale.
*"Questa per me è la slide che fa più male, perché io lavoro con adulti in riqualificazione. Gente di 40 anni che cambia vita. Quelli sono, quasi per definizione, il gruppo a bassa autoefficacia. Sono esattamente quelli che l'AI **sembra** aiutare e sta lasciando indietro."*
*"Il 'falso senso di progresso' non è un modo di dire: è un costrutto della ricerca sulla metacognizione dagli anni Ottanta. L'AI lo mette sotto steroidi."*
📎 [ICER 2024](https://dl.acm.org/doi/10.1145/3632620.3671116)

---

### Slide 30 — La trappola della facilità
🖼️ Una frase sola, grande — **questa è quella testuale**:
> ## *"If letting AI in makes the task feel effortless, it is in the wrong place."*

Sotto, piccolo: *The Effortless Trap*, Brcic & Frljic, giugno 2026 · e la letteratura sulle **desirable difficulties** (Bjork)
💡 "La facilità è un campanello d'allarme" tienila come tua sintesi parlata, non come citazione tra virgolette.
E la riga di Anthropic: *"lo sforzo cognitivo — e persino il **restare dolorosamente bloccati** — è probabilmente importante per la padronanza."*

🗣️ *"Se i vostri studenti non sono mai bloccati, non state insegnando: state intrattenendo. E questo vale anche per voi, quando imparate una libreria nuova alle undici di sera con l'agente aperto."*
📎 [arXiv 2606.26181](https://arxiv.org/abs/2606.26181)

---

# ATTO 6 — ADESSO TOCCA A VOI (10 slide, ~8 min)
*(10 intestazioni ma 6 momenti: due esercizi hanno una slide di setup e una di rivelazione, ed è giusto così — la rivelazione deve arrivare dopo il silenzio.)*

*Formato: mostri la slide, conti fino a dieci in silenzio, chiedi "be'? sapreste farlo?". Niente di organizzato, niente gruppi, niente post-it. Solo mani alzate e disagio produttivo.*

> 📄 **Il materiale completo di questi cinque esercizi — codice, soluzioni, numeri, cosa dire — è in `esercizi-aula.md`.**
> Tutto il codice è stato **eseguito e verificato**: i test verdi sono verdi davvero, l'exploit funziona davvero, il centesimo balla davvero.
> Qui sotto solo l'essenziale per impaginare le slide.

### Slide 31 — Setup
🖼️ **"Cinque esercizi che nel 2019 erano stupidi. Nel 2026 sono il programma."**
🗣️ *"Ve li mostro e basta. Non vi chiedo di farli: vi chiedo di chiedervi se **sapreste** farli. E se sapreste **valutare** qualcuno che li fa."*

---

### Slide 32 — Esercizio 1: **Prompt Problem** · *specificare*
🖼️ **Nessun testo del problema.** Solo questo:

```
[1, 2, 2, 3, 3, 3]   →   [1, 2, 3]
[5, 5]               →   [5]
["b", "a", "b"]      →   ???
[]                   →   ???
[3, 1, 3]            →   ???
```
**"Scrivete il prompt. Un tentativo solo. Deve passare tutti i test."**

🗣️ *"Chi ha scritto 'rimuovi i duplicati' ha già sbagliato **tre casi su cinque**. E il modello non ve lo dirà: vi darà `sorted(set(xs))`, pulito, con la docstring, che passa i due test che avevate in mente."*
Le quattro ambiguità che nessuno ha risolto: **ordine** (ordinato o di prima apparizione?), **tipo**, **lista vuota**, **mutazione**.
📎 [Prompt Problems, SIGCSE 2024](https://arxiv.org/abs/2311.05943) · [Promptly](https://arxiv.org/abs/2307.16364)

---

### Slide 33 — Esercizio 2: **Explain in Plain English** · *comprendere*
🖼️
```python
def h(xs):
    a, b = 0, 0
    for x in xs:
        a = max(a + x, x)
        b = max(b, a)
    return b
```
**"In UNA frase: cosa fa? Non riga per riga — cosa FA."**

🗣️ Distingui i due livelli: ❌ *multistrutturale* ("tiene due variabili, per ogni elemento...") = riassunto · ✅ *relazionale* ("somma massima di una sottosequenza contigua" = Kadane) = comprensione.
Poi il bug verificato: `h([-3,-1,-7])` → **0**, dovrebbe essere −1.
E il twist: **la vostra frase diventa il prompt**. Se il modello rigenera codice equivalente, avevate capito.
📎 [Explaining Code with a Purpose](https://arxiv.org/abs/2403.06050) · [function naming](https://arxiv.org/pdf/2503.12207)

---

### Slide 34 — Esercizio 3: **Trova la vulnerabilità** · *valutare criticamente*
🖼️ Endpoint Flask `/cerca` (15 righe, f-string nell'HTML + `log.info(f"...{q}")`). Accanto, in verde:
```
$ pytest -q
...                                    [100%]
3 passed in 3.34s
```
**"I test sono verdi. È in produzione. Chi la vede?"**

🗣️ Le vulnerabilità sono **tre**, non una: XSS riflessa su `{q}`, XSS **stored** su `{a['titolo']}` (questa non la vede quasi nessuno), **log injection** — con un `%0A` forgi una riga di log falsa nell'audit trail.
Poi: *"la domanda vera è: **l'avreste vista se non aveste mai scritto codice a mano?**"*
📎 [Veracode](https://www.veracode.com/blog/spring-2026-genai-code-security/)

---

### Slide 35 — Esercizio 4: **Il test di Naur** · *costruire la teoria*
🖼️ `calcola_totale(ordine)`, ~35 righe generate: promo %, punti fedeltà, coupon, soglia spedizione gratis, IVA. Funziona, è pulito, ha i commenti numerati.
**"Il marketing chiede: la soglia spedizione deve valere sul carrello PRIMA degli sconti, e i punti non devono maturare sull'IVA. Dove mettete le mani?"**

🖼️ **Slide successiva — la rivelazione** (numeri reali, carrello 2×32,50 € con promo −20%):

| | Totale |
|---|---|
| Senza usare i punti | **63,44 €** |
| Usando 300 punti (= 3,00 € di sconto) | **68,20 €** |

> ## Spendere 3,00 € di punti fa **aumentare** il totale di 4,76 €.

🗣️ *"Questo codice funziona, passa i test, ha i commenti. Ed è un disastro — ma **non potete saperlo leggendolo**, perché il codice non vi dice se è una decisione di business o un incidente."*
*"E notate cosa vi ho chiesto: non 'trova il bug', ma **dove mettete le mani**. Chi ha la teoria risponde in dieci secondi. Chi non ce l'ha o se la costruisce adesso — al triplo del costo — o dice all'agente 'rigenera tutto', e al giro dopo è di nuovo esattamente qui."*

---

### Slide 36 — Esercizio 5: **Code review al contrario** · *decidere e motivare*
🖼️ Issue: *"Il totale del carrello a volte è sbagliato di un centesimo."* Due PR, entrambe verdi, entrambe generate.
**PR #1** *(+2 −1)*: `return round(t - t * sconto/100, 2)` — **PR #2** *(+9 −3)*: `Decimal` + `quantize(ROUND_HALF_UP)`
**"Quale approvate? E cosa scrivete nel commento?"**

🖼️ I numeri reali (trovati su 400.000 carrelli casuali):

| Carrello | Sconto | PR #1 | PR #2 |
|---|---|---|---|
| `[28.20, 55.44, 22.01]` | 10% | **95,09** | **95,08** |
| `[41.56, 54.89]` | 50% | **48,23** | **48,22** |

E la riga che chiude: `>>> round(2.675, 2)` → `2.67` *(banker's rounding, non half-up)*

🗣️ *"PR #1 è più corta, più leggibile, passa i test, e il bug **ricomparirà tra sei mesi**: non ha risolto niente, ha spostato l'arrotondamento più in là. PR #2 è più lunga, più brutta, e ha ragione."*
*"Questo è letteralmente il lavoro di un junior in IBM nel 2026: 'genera cinque soluzioni, dimmi quale è giusta **e perché**'. Il 'e perché' è tutto il mestiere."*
*"Ed è la risposta al problema della valutazione: se il codice funzionante non dimostra più niente, si torna a valutare **facendo parlare le persone**. Colloquio, spiegazione, review dal vivo, 'difendi questa PR'. Meno scalabile. Più vero."*

💡 Se qualcuno obietta che **anche PR #2 è discutibile** — e in questa sala succederà — è il momento migliore del talk: dagli ragione (si arrotonda lo sconto o il totale? è una decisione di business) e poi *"ecco, questa conversazione che stiamo facendo adesso **è** la competenza. Non c'è nel diff, non c'è nel prompt, non c'è nei test."*

---

### Slide 37 — Cosa hanno in comune
🖼️ I cinque esercizi in fila, e sotto, una riga per ciascuno:

| Esercizio | Cosa allena |
|---|---|
| Prompt Problem | **Specificare** |
| Explain in Plain English | **Comprendere** |
| Trova la vulnerabilità | **Valutare criticamente** |
| Il test di Naur | **Costruire la teoria** |
| Code review al contrario | **Decidere e motivare** |

> ### In nessuno di questi cinque il compito è **scrivere codice**.
> ### In tutti e cinque, **non li sai fare se non hai mai scritto codice**.

🗣️ Questa è la chiusura dell'atto e praticamente la tesi del talk. Non aggiungere niente.

---

# CHIUSURA (3 slide, ~3 min)

### Slide 38 — La risposta
🖼️ Il titolo del talk, e sotto la risposta:

> ## Sì. Più di prima.
> ### Ma non per produrre codice — quello è gratis.
> ### Per costruire la **teoria** che rende il codice vivo, e la **capacità di giudicare** una macchina che sbaglia con sicurezza.

🗣️ *"È una competenza tacita. Si costruisce con la fatica. E — per citare l'unica frase che vi chiedo di ricordare — **non si può delegare**."*

---

### Slide 39 — Tre cose da portare a casa
🖼️ Tre righe, numerate, niente altro.

1. **Automazione o aumento**: la stessa tecnologia, due esiti opposti. Chi insegna decide quale.
2. **La facilità è un segnale d'allarme**, non un obiettivo. Per gli studenti e per voi.
3. **I pioli bassi della scala non si automatizzano impunemente.** Qualcuno deve restare a costruirli.

🗣️ Se hai 20 secondi in più, aggiungi a voce: *"E se lavorate in un'azienda che ha smesso di assumere junior: fate vedere ai vostri responsabili la slide di IBM. Non è buonismo, è pianificazione."*

---

### Slide 40 — Grazie
🖼️ Nome, contatti, QR code al documento con tutte le fonti. Claim dell'evento se ti va: *"Train you must. Not with a saber — with knowledge."*
🗣️ *"Tutte le fonti sono qui. Ci sono anche gli studi che mi danno torto, perché ce ne sono."*

---

---

# Note di regia

**Arco narrativo**: pendolo (confusione) → dati (chiarezza scomoda) → pioli mancanti (il problema vero) → Karpathy (dove va il mestiere) → studi (si può fare qualcosa) → esercizi (ecco come) → risposta.

**Le 5 slide che devi fare bene**, se il tempo per prepararle è poco: **8** (le due linee −11%/+10%), **14** (la scala senza pioli), **16** (il benchmark Veracode), **i sei pattern** dell'RCT Anthropic, e **la chiusura degli esercizi** ("in nessuno dei cinque il compito è scrivere codice").

**Slide di riserva (backup, dopo il grazie)** per il Q&A:
- **Kazemitabaar 2023**: novizi 10–17 anni con Codex → *meglio*, nessun danno ai task manuali. La contro-evidenza. Averla pronta ti rende credibile: *"sì, c'è anche questo, e cambia il quadro così..."*
- **METR** *(tagliato dal talk, tenuto qui)*: 16 sviluppatori esperti, 246 issue sui loro repository. Si aspettavano +24%, hanno fatto **−19%**, e dopo erano ancora convinti di aver accelerato del 20%. Serve **solo** se qualcuno dice "ma l'AI mi fa andare più veloce": la risposta è *"forse. Anche loro ne erano convinti."* Non usarlo come prova che l'AI rallenta — il follow-up 2026 è inconcludente e il campione è 16.
- **DORA 2025**: l'AI è un **amplificatore** — potenzia le organizzazioni sane, amplifica le disfunzioni. Le 7 capability sono tutte di ingegneria del software, nessuna è "saper promptare".
- **GitClear**: blocchi duplicati **8×** nel 2024, copy/paste nello stesso commit **+41%**, costrutti che mascherano gli errori **+47%**, e soprattutto **refactoring −70%** e **manutenzione del legacy −74%** rispetto al 2022. Non si scrive solo più codice: **si smette di sistemarlo.** *(Il «+75% di codice committato» che circolava non è verificabile su fonti GitClear primarie: non usarlo.)*
- **Dagstuhl 25311 / 27062**: la comunità mondiale di ricerca ha dichiarato obsoleto il modello "tanti piccoli programmi + autograder", e a febbraio 2027 c'è un seminario intitolato letteralmente *What Should We Teach CS Students in the Age of AI?*. Utile se qualcuno ti chiede "ma ci sta lavorando qualcuno seriamente?".
- **CS50 Harvard**: il "duck" con guardrail, dal 2023 su migliaia di studenti. È il GPT Tutor di Bastani applicato alla programmazione — la prova che si può fare su larga scala.

**Da preparare a mano** (non si improvvisano):
- ~~Gli snippet degli esercizi~~ → ✅ **fatti e verificati**: sono in `esercizi-aula.md`, tutti eseguiti davvero (test verdi reali, exploit funzionante, divergenza da un centesimo trovata su 400.000 carrelli, paradosso dei punti fedeltà misurato). Rifiniscili pure a mano, ma i **numeri che dici dal palco reggono così come sono**.
- Il grafico della slide 8 (le due linee −11% / +10%).
- L'illustrazione della scala senza pioli (slide 14) e quella pavimento/soffitto (slide 20).
- Gli screenshot: per la slide 34 conviene una vera cattura di `pytest -q` con i tre pallini verdi, e per la 35 una vera finestra di agente. Sono più credibili di un blocco di codice impaginato.

**Trappole da evitare**:
- Non fare il nostalgico. La slide 22 deve dire chiaramente che **il pavimento che si alza è una buona notizia**.
- Non citare il MIT "Your Brain on ChatGPT" come prova: 54 persone, preprint. Usalo come metafora ("debito cognitivo") o non usarlo.
- Non usare i numeri virali ("−67% di annunci entry-level", "54% delle aziende non assume più junior"): non hanno fonte primaria verificabile. Hai Stanford, non ti serve altro.
- Non rimettere METR "perché è famoso". Se proprio te lo chiedono in Q&A, la risposta sta nelle slide di riserva.

**Stack Overflow Survey**: la riga Stack Overflow della slide 17 è **chiusa con i dati 2025 verificati** (84% adozione · **46% diffida contro 33% che si fida** · **2,5%** tra gli esperti), che sono pubblicati, citabili e reggono da soli. La **Survey 2026** è in campo da giugno e potrebbe uscire a ridosso del 26 settembre: se esce in tempo, l'unica cosa da fare è sostituire le cifre e la data in calce — la struttura della slide e la battuta ("quelli che lo conoscono meglio se ne fidano meno") funzionano identiche. Se non esce, non cambia nulla: **non aspettarla**.

---

# ✂️ Cosa ho tolto, e perché

Criterio: **una tesi, una fonte**. Un secondo soggetto che ripete un punto già fatto meglio da un altro non aggiunge rigore — costringe la sala a tenere a mente un nome in più, e diluisce quello forte. Da ~20 fonti citate a **11**.

| Tolto | Perché |
|---|---|
| **METR** *(aveva una slide)* | Il suo punto — "la percezione della produttività è inaffidabile" — lo fanno già **Prather** ("illusione di competenza") e i **sei pattern** di Anthropic, entrambi più vicini al tema didattico. In più costava due caveat dal palco (n=16, follow-up inconcludente). Due caveat per un punto che hai già è un cattivo affare. → **spostato nelle slide di riserva**, dove serve solo se qualcuno solleva l'obiezione. |
| **Stack Overflow** *(aveva una slide)* | Misura **opinioni**, non esiti. Tenuto come **una riga** nella slide 17, dove la frase "gli esperti si fidano meno" lavora dentro un argomento più grande invece di essere l'argomento. |
| **Apiiro** | **Vendor di application security che vende il prodotto che trova i problemi che descrive.** Non è peer-reviewed, è un post sul blog aziendale, e soprattutto **non dichiarano come hanno classificato uno "sviluppatore assistito da AI"** — che non è un dettaglio, è tutto lo studio. I numeri erano i più spettacolari del mazzo (sintassi −76%, privilege escalation +322%) ed è esattamente per questo che andavano guardati due volte. **Tagliato.** |
| **WEF Future of Jobs** | Lo cita chiunque in qualunque talk sul futuro del lavoro. Non aggiunge credibilità, la toglie: suona come riempitivo. I dati italiani al suo posto sono più specifici e nessun altro li avrà. |
| **AlmaLaurea** | Una posizione in classifica, non un numero. Terza sigla italiana sulla stessa slide per zero informazione aggiuntiva. |
| **GitClear** | Resta una riga nelle slide di riserva per il suo punto distinto (*"il refactoring è calato del 70%: non si scrive solo più codice, si smette di sistemarlo"*), che nessun'altra fonte fa. |
| **MIT "Your Brain on ChatGPT"** | 54 persone, preprint, e fuori dalla programmazione. Da non citare come prova. "Debito cognitivo" resta utilizzabile come **metafora parlata**, senza attribuzione in slide. |
| **Randstad +303%** | Non verificabile su fonti primarie (vedi `audit-fonti.md`). |

**Le 11 che restano**, ognuna con un compito che nessun'altra fa:

| Fonte | Il suo compito |
|---|---|
| **Stanford / Canaries** | Il problema esiste, ed è sui giovani |
| **Handshake + NSC** | I ragazzi l'hanno già capito, e stanno scappando |
| **IBM** | Non è un destino: qualcuno sta facendo il contrario |
| **Veracode** | Circa metà di quel codice non regge — *benchmark riproducibile* |
| **Octoverse** | I nuovi arrivano già con lo strumento in mano |
| **Stack Overflow** *(1 riga)* | Chi lo conosce meglio se ne fida meno |
| **Karpathy** | Dove va il mestiere: pavimento e soffitto |
| **Naur (1985)** | Perché capire non si delega |
| **Anthropic RCT** | Il *come* lo usi decide se impari |
| **Bastani (PNAS)** | La domanda non è "AI sì o no" ma "AI progettata come" |
| **Prather** | E intanto il divario si allarga — *"illusione di competenza"* |
| **Excelsior + PoliMi** | In Italia il mercato chiede proprio questo, e non lo trova |

*(Sono 13 righe per 11 soggetti: Veracode e Stack Overflow non hanno una slide propria, Excelsior e PoliMi condividono la stessa.)*

💡 **Se vuoi tagliare ancora** — per esempio se lo slot si accorcia — il prossimo candidato è **Handshake/NSC**: il pessimismo degli studenti è vero e ti riguarda da vicino, ma è la parte che puoi raccontare **come insegnante, a voce, senza slide**. Un aneddoto dalla tua aula vale quanto il 70%, e ti costa zero fonti.

---

---

# 🔍 Il criterio di provenienza

Quasi tutta la ricerca su questo tema viene da aziende che hanno qualcosa da vendere. Non è squalificante di per sé — è il campo che è fatto così — ma la domanda da farsi prima di mettere un numero in slide è una sola:

> ### Lo posso **controllare**, o devo **crederlo**?

**Veracode** è un vendor di security. Ma pubblica un **benchmark**: 100+ modelli, 80 task standardizzati, quattro linguaggi. Chiunque può rifarlo e vedere se torna. Lo puoi controllare.

**Apiiro** è anch'esso un vendor di security, ma misura sviluppatori reali su **repository aziendali privati**, con il **proprio strumento**, e non pubblica i criteri di classificazione. Devi crederlo. **Per questo è stato tagliato**, nonostante avesse i numeri più spettacolari del mazzo — o meglio, proprio per quello.

Vale la pena applicare la stessa domanda alle altre fonti che restano, così sai dove sei esposto:

| Fonte | Chi è | Lo puoi controllare? |
|---|---|---|
| **Stanford / Canaries** | ricerca accademica (NBER), dati ADP | ✅ paper pubblico, metodologia dichiarata, limiti dichiarati |
| **Anthropic RCT** | azienda che vende l'agente di coding | ✅ *e il risultato va **contro** il loro interesse commerciale: è il caso in cui il conflitto lavora a favore della credibilità* |
| **Bastani / PNAS** | ricerca accademica | ✅ peer-reviewed, RCT su ~1.000 studenti |
| **Prather / ICER** | ricerca accademica | ✅ peer-reviewed *(ma n=21 qualitativo: dillo)* |
| **Veracode** | vendor di security | ✅ benchmark riproducibile |
| **NSC** | ente statistico no-profit | ✅ dati amministrativi |
| **Octoverse** | GitHub, che vende Copilot | ⚠️ dati proprietari sulla propria piattaforma — ma il dato che usi ("quasi l'80% usa Copilot") è **a loro favore**, quindi non c'è incentivo a gonfiarlo al contrario |
| **Handshake** | piattaforma di recruiting | ⚠️ sondaggio sui propri utenti, dimensione del campione non dichiarata |
| **Excelsior / PoliMi** | ente camerale / università | ✅ pubblici |
| **IBM** | azienda che annuncia le proprie assunzioni | ⚠️ è una **dichiarazione**, non un dato: citala come tale ("hanno detto che") |

Le due righe con ⚠️ non sono da togliere — sono da **attribuire con precisione**. "Secondo un sondaggio di Handshake sui propri utenti" costa due parole in più e ti mette al riparo.
