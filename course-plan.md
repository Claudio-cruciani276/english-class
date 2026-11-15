# English Class: piano del corso

File di lavoro dell'insegnante (Claude). Lo legge e lo aggiorna ogni notte l'attività "Lezione del giorno dopo". L'admin lo rivede nel weekend insieme a Claude. Non fa parte dell'app.

## 1. Regole del piano

- PRIORITA' (admin, 15 novembre): la sezione 8 (reading piu' lunghi e interessanti, domande di comprensione difficili) PREVALE sulle istruzioni generiche della procedura notturna per i reading, i listening, le canzoni e le verifiche: dove la procedura dice 10-12 battute, 8 esercizi, 15 minuti, vale la sezione 8.
- Il piano della settimana (sezione 3) decide gli argomenti. Se manca, usa l'ordine di default della sezione 4 e salta quelli già nel registro (sezione 5).
- Ogni lezione di grammatica contiene: UN tempo verbale principale + 1 o 2 mini argomenti + un breve blocco di ripasso mirato (errori ricorrenti o argomento della lezione precedente). Almeno per le prime settimane, per recuperare le basi.
- Verifiche speciali indicate nel piano (per esempio il weekend 21-22 novembre) prevalgono sul formato standard del sabato (20 punti) e della domenica (ripasso).
- Regola dell'admin dal 15 novembre: in ogni lezione di grammatica il blocco di ripasso ripropone a rotazione esercizi di TUTTI i tempi verbali già fatti (scelta del tempo), per fissarli. Vale anche nelle settimane successive finché l'admin non dice altro.
- Tutto quello che è in piano va fatto: se un argomento non entra, lo si sposta con una riga nel registro, non lo si cancella.
- Dopo aver creato la lezione del giorno, aggiorna anche topics.json (root): la pagina "Argomenti del corso" dell'app, sintetica, raggruppata per tempi verbali, preposizioni, nomi/articoli/quantita', parole interrogative, altri punti di grammatica, phrasal verbs, listening e writing, letture, canzoni. Aggiungi voci brevi (2-5 parole, in inglese e in italiano) con date = giorno della lezione (l'app le mostra solo da quel giorno). Per i reading, le canzoni e i phrasal verbs, una voce per settimana con date = lunedi'.
- Dopo aver creato la lezione del giorno, aggiungi una riga al registro (sezione 5): data, formato, tempo verbale, mini argomenti, note utili (per esempio "poco spazio per X, riprendere giovedì").
- Le spiegazioni e gli esercizi sono sempre originali: le linee guida della sezione 4 vengono dal libro di grammatica dell'admin (livello intermedio), ma niente frasi o esercizi copiati. Si riprendono i punti di grammatica e i tipi di esercizio, con frasi nuove.
- Revisione del weekend: se nella sezione 6 ci sono note dell'admin, applicale. Se l'admin non ha potuto rivedere, la notte di domenica Claude decide da solo: scrive o corregge il piano della settimana successiva (marcandolo "bozza di Claude") e lo usa.

## 2. Formato nuovo della lezione di grammatica (da lunedì 9 novembre)

Le lezioni della prima settimana richiedevano meno di 10 minuti: ora si allungano leggermente.

- minutes: 30 (negli index e nel file).
- 4 spiegazioni brevi a schermate: (1) tempo verbale principale, uso e forma; (2) tempo verbale principale, negativa, domanda e casi particolari; (3) mini argomento A; (4) mini argomento B (o il confronto con il tempo della lezione precedente).
- 22-26 esercizi (mcq, fill, order), dal facile al difficile, in blocchi: prima il tempo verbale, poi i mini argomenti, alla fine un blocco misto con tutti. Almeno la metà sono fill e order (produzione), non solo mcq.
- 8-10 flashcard collegate (parole e strutture).
- Nel blocco di ripasso: 3-4 esercizi su errori ricorrenti o su un punto della lezione precedente.
- Tipi di esercizio da usare (ispirati al libro): completare una frase con un verbo scelto da una lista nella forma giusta; riscrivere una routine come cosa fatta ieri; scrivere la domanda per una risposta data; positivo o negativo con il verbo dato; scegliere la forma corretta tra due; abbinare due metà di frase; trasformare una situazione in una frase con una parola data.

### Verifica del sabato: confronto tra i tempi verbali (regola dell'admin, 7 novembre)

Capire quando si usa un tempo verbale e non un altro e' la parte piu' importante. Quindi nella verifica da 20 punti:
- almeno 8 dei 16 esercizi di grammatica sono sulla SCELTA TRA I TEMPI della settimana (past simple, past continuous, present perfect; quando e' utile anche present simple e continuous delle settimane precedenti);
- tipi: scegliere il tempo giusto dato un indizio (yesterday, last night, when, while, just, already, yet, ever, never, so far, this week); completare con il verbo nel tempo corretto; scegliere la frase corretta tra due o tre tempi; correggere un errore di tempo; una mini storia da completare con i verbi tra parentesi;
- ogni why e why_it spiega perche' si usa quel tempo e non gli altri (indizio di tempo, azione finita o in corso, collegamento con il presente);
- gli altri esercizi coprono i mini argomenti della settimana.
Lo stesso confronto va anche nel blocco misto della lezione di giovedi (vedi "Confronto tra i tre tempi" nella sezione 4) e nel ripasso della domenica, che parte dagli errori di scelta del tempo.

## 3. Piano delle settimane

### Settimana 9-15 novembre (approvata dall'admin il 7 novembre)

- Lun 9, grammatica: PAST SIMPLE (was/were, verbi regolari con -ed, irregolari più comuni, did/didn't + infinito) + preposizioni di luogo in/on/at + PAROLE INTERROGATIVE 1 (where, when, who, why, which, whose; vedi sezione 4). There is / there are: NIENTE spiegazione (l'admin dice che si sanno), solo usati negli esercizi.
- Mar 10, grammatica: PAST CONTINUOUS (anche in confronto con il past simple, when/while; qualche esercizio di scelta tra past simple e past continuous) + PAROLE INTERROGATIVE 2: how much / how many, how far, how long, how often (vedi sezione 4) + this / these / that / those (spiegazione veloce). There is / there are senza spiegazione, solo negli esercizi.
- Mer 11, listening: situazione nuova, per esempio una persona che si trasferisce in un nuovo appartamento e lo descrive (there is/are, preposizioni di luogo, past simple per raccontare il trasloco).
- Gio 12, grammatica: PRESENT PERFECT 1 (have/has + past participle, been/gone, just/already/yet) + countable e uncountable (a/an, some/any, many/much light; some/any e' stato spostato qui da martedi') + blocco di ripasso su past simple e past continuous. Il present perfect è il punto più difficile per un italiano (falso amico del passato prossimo): più spazio a lui, mini argomento leggero. Inserire una schermata di confronto tra i tre tempi (sezione 4, "Confronto tra i tre tempi") e un blocco misto con esercizi di scelta del tempo.
- Vocabolario della settimana 9-15 (dal quaderno dell'admin, sezione 4 "La stanza e le preposizioni di luogo"): le preposizioni di luogo e le parole della stanza entrano nelle flashcard delle lezioni di grammatica, nel reading dell'hotel (descrivere la camera, problemi in camera), nel listening del nuovo appartamento e nel writing di venerdi'. This/these/that/those: spiegazione veloce (una schermata breve con 4 esempi e 3-4 esercizi) nella lezione di martedi' 10, e poi usati negli esempi.
- Phrasal verbs della settimana (sezione 7): dieci verbi, lezione dedicata nella sezione "Phrasal verbs della settimana" dell'app.
- Ven 13, writing: descrivere casa o quartiere (there is/are, much/many/a lot of) e un breve diario di che cosa si è fatto nel weekend (past simple).
- Sab 14: verifica da 20 punti: 8 esercizi sulla scelta tra past simple, past continuous e present perfect (regola della sezione 2), gli altri su in/on/at di luogo, parole interrogative, countable e uncountable con some/any, e 4 di comprensione (there is/are solo dentro le frasi).
- Dom 15: ripasso (parte dagli errori della verifica).
- Reading della settimana: hotel, shopping per vestiti, dal medico e in farmacia. Canzoni: This Is the Life e Starlight (scelte dall'admin il 9 novembre).

### Settimana 16-22 novembre (approvata dall'admin il 15 novembre, con i nuovi argomenti dei suoi quaderni e del libro)

REGOLA DELLA SETTIMANA (admin, 15 novembre): in ogni lezione di grammatica il blocco di ripasso diventa piu' ampio (6-8 esercizi) e RIPROPONE tutti i tempi verbali gia' fatti (present simple, present continuous, past simple, past continuous, present perfect), a rotazione e sempre con scelta del tempo: nessun tempo resta fuori per piu' di un paio di giorni. Il lunedi' e il martedi' rivedono i due presenti e i due passati, il giovedi' tutti e cinque piu' il present perfect continuous. Lezioni da 30 minuti, 24-26 esercizi.

- Lun 16, grammatica: PRESENT PERFECT 2, cioe' le ESPERIENZE fino a oggi: ever (solo nelle domande), never (con verbo positivo), been to, still / just / already / yet come richiamo dello schema dell'admin (still ancora, just appena, already gia', yet gia'/ancora; vedi sezione 4 "Present perfect 2"), confronto con il past simple (I have eaten Thai food three times this week / I ate Thai food yesterday), "It's the first time I've...". + PRONOMI SOGGETTO E COMPLEMENTO (I/me, you/you, he/him, she/her, it/it, we/us, they/them; sezione 4) + DOPPIA NEGAZIONE (in inglese una sola negazione: I never go, non I don't never go; nobody, nothing, nowhere). Dentro gli esempi: here / there / over there.
- Mar 17, grammatica: PRESENT PERFECT con FOR e SINCE (duration form: I've known him for ten years, I haven't eaten for two days, from...to, since = momento iniziale, for = durata, How long have you...?; con i verbi di stato si usa il present perfect simple) + PAROLE POSSESSIVE: aggettivi possessivi (my, your, his, her, its, our, their) e pronomi possessivi (mine, yours, his, hers, ours, theirs; senza articolo) + GENITIVO SASSONE (Carlo's car, the dog's leg; per le cose the leg of the table / table leg). Piu' ripasso a rotazione dei tempi.
- Mer 18, listening: un viaggio e i suoi progetti (per esempio due amici che pianificano un viaggio e raccontano un'esperienza passata): present perfect per le esperienze, past simple per raccontare, going to e would like to per i progetti, will per le decisioni al momento; parole di viaggio. Pronomi e possessivi negli esempi (that's mine, it's yours).
- Gio 19, grammatica: PRESENT PERFECT CONTINUOUS (have/has been + -ing: attivita' che dura fino a ora o appena finita con risultati visibili, how long / for / since, azioni ripetute; confronto con il present perfect simple: attivita' contro risultato, how long contro how many / how much; sezione 4) + INTENZIONE E DECISIONE: be going to (intenzione), would like to (desiderio), will (scelta spontanea); + verbi di gusto con -ing (love, like, hate, enjoy + verbo in -ing: I love watching TV). Ripasso dei cinque tempi. Schermata di confronto tra i tempi passati e presenti collegati al presente.
- Ven 20, writing: un'email o un diario di una vacanza (present perfect per le esperienze, past simple per raccontare, going to per i progetti). Schermata "Language boost": i QUANTIFICATORI (no, a little / a few, too much / too many, too + aggettivo; sezione 4) e here / there / over there, poi esercizi di trasformazione e riordino.
- WEEKEND 21-22 NOVEMBRE: VERIFICA SPECIALE IN DUE TEST (richiesta dell'admin, 15 novembre). QUESTA REGOLA PREVALE sul formato standard del sabato (20 punti) e della domenica (ripasso) della procedura: nel weekend NON si fa ne' la verifica da 20 punti ne' il ripasso, ma i due test qui sotto. Riprendono TUTTO quello fatto dal 2 novembre (lezioni di grammatica, listening, writing, reading, canzoni, phrasal verbs, flashcard) con 90 domande in totale, divise in due file da 45 (originali, mai copiate dal libro). Ogni esercizio ha why e why_it. Niente audio. minutes: 50 per ogni test. Percorso del punteggio: 1 punto per domanda (45 per test, 90 in tutto).
  - Sab 21 = TEST 1 (lessons/2026-11-21.json, titolo "Weekly check: test 1 (grammar)"): 30 esercizi di GRAMMATICA + 15 esercizi dell'area "quello che manca" (vedi sotto: 8 di correzione errori e 7 di comprensione di brevi testi).
  - Dom 22 = TEST 2 (lessons/2026-11-22.json, titolo "Weekly check: test 2 (vocabulary and phrasal verbs)"): 30 domande di VOCABOLARIO + 15 domande sui PHRASAL VERBS.
  - GRAMMATICA (30, nel test 1): copre tutti gli argomenti svolti: present simple, present continuous e confronto, past simple, past continuous, present perfect simple (esperienze, just/already/yet/still, for/since), present perfect continuous, scelta tra tutti i tempi (REGOLA DELLA SEZIONE 2: almeno 15 dei 30 sono sulla scelta del tempo, con indizi come yesterday, last night, while, ever, never, yet, already, just, since, for, how long, this week, now, usually), parole interrogative, in/on/at di tempo e di luogo, preposizioni della stanza, this/these/that/those, countable e uncountable e quantificatori (some/any/no, much/many/a lot of, a little/a few, too much/too many), pronomi soggetto e complemento, possessivi e genitivo sassone, going to / would like to / will, love/like/hate/enjoy + -ing, doppia negazione, avverbi di frequenza. Tipi: mcq, fill, order, correggi l'errore, mini storia da completare.
  - VOCABOLARIO (30, nel test 2): le parole e le frasi delle flashcard e delle tabelle di tutte le lezioni, dei reading (frasi chiave di aeroporto, ristorante, indicazioni, hotel, shopping, medico e dei reading della settimana 16-22), delle canzoni e il vocabolario della stanza. Prendi le parole dai campi "cards" e dalle tabelle English/Italiano dei file in lessons/, senza ripetere la stessa parola due volte. Tipi: significato in contesto (mcq), completare una frase con la parola giusta (fill), parola contraria o collegata, riordinare una frase di un reading.
  - "QUELLO CHE MANCA" (30 in tutto: 15 nel test 1 + 15 nel test 2; interpretazione di Claude, da confermare con l'admin): le aree che non sono ne' grammatica pura ne' vocabolario: PHRASAL VERBS (15, test 2: i verbi delle due settimane, 9 e 16 novembre, in frasi diverse da quelle gia' viste), CORREZIONE DI ERRORI in frasi con errori tipici di un italiano (8, test 1: did + passato, present perfect con yesterday, doppia negazione, too/very, much/many, how long time ecc.) e COMPRENSIONE di 2 brevi testi nuovi scritti da te (7 domande, test 1, a livello B1).
  - I risultati di entrambi i test alimentano il piano della settimana dopo (errori ricorrenti da riprendere nel blocco di ripasso).
- Reading della settimana: dal piano di default (biglietti di treno e autobus, al telefono per fare un piano con un amico, presentarsi a una festa): usare anche going to, would like to e will nei dialoghi.
- Phrasal verbs della settimana 16-22: dieci nuovi (sezione 7).
- Canzoni: coppia da confermare dall'admin (songs-queue.json). Se non ha ancora confermato, e' in coda la coppia proposta da Claude.

### Settimana 23-29 novembre (bozza di Claude, da rivedere nel weekend)

- Lun 23, grammatica: FUTURO: will contro going to (previsioni, promesse, offerte, piani gia' decisi; present continuous per gli appuntamenti) + a / an e the (prima menzione, cosa chiara, tipo contro uno specifico; sezione 4). Ripasso a rotazione di tutti i tempi.
- Mar 24, grammatica: COMPARATIVI E SUPERLATIVI (-er/-est, more/most, as...as, than) + countable e uncountable 2 (advice, information, news, luggage, weather...; nomi con due significati). Ripasso a rotazione dei tempi.
- Mer 25, listening: situazione diversa dalle precedenti (per esempio fare un piano per il weekend o un consiglio a un amico); present perfect, past simple e futuro.
- Gio 26, grammatica: VERBI MODALI (can / can't / could, must / mustn't, have to / don't have to, should) + richiamo di present perfect simple e continuous. Ripasso a rotazione dei tempi.
- Ven 27, writing: un'email con consigli e progetti (modali, will, going to, tempi passati).
- Sab 28: verifica da 20 punti con la scelta del tempo al centro (regola della sezione 2). Dom 29: ripasso.
- Phrasal verbs 23-29 e 30 novembre: come proposta nella sezione 7.

## 4. Linee guida di contenuto per argomento

### Past simple
- Si usa per azioni finite in un momento passato definito (yesterday, last week, three days ago, in 2019, when I was a child).
- Verbi regolari: -ed, con i cambi di ortografia (stopped, studied, lived). Irregolari: gruppo ristretto e frequente (go-went, see-saw, write-wrote, have-had, buy-bought, take-took, shut-shut ecc.) a gruppi tematici.
- Negativa e domanda con did/didn't + infinito senza to (Did you enjoy it? I didn't buy anything). Errore tipico italiano: did + passato. Segnalare anche "do" come verbo principale (What did you do? I didn't do anything).
- Passato di be: was/wasn't, were/weren't, domande Was she...? Were they...?
- Esercizi: la routine di una persona riscritta come "ieri"; scrivere le domande per le risposte di una vacanza; verbo da lista nella forma giusta; positivo o negativo con il verbo dato.

### Past continuous
- was/were + -ing: azione in corso a un momento del passato ("alle 10.30 stavano giocando a tennis"); era iniziata prima e non era finita.
- Confronto con il past simple: azione in corso contro azione completa ("We were walking home when I met Dan" / "We walked home after the party").
- Azione breve nel mezzo di una più lunga: when/while ("It was raining when I got up", "Matt phoned while we were having dinner"). Una cosa dopo l'altra: past simple.
- Verbi di stato (know, want, like, understand) di norma non in forma continua.
- Esercizi: verbo da lista nella forma giusta; abbinare le due metà con when/while; completare con past simple o past continuous; descrivere una scena in un momento preciso.

### Present perfect 1 (e 2)
- have/has + past participle (regolare in -ed, irregolare da imparare). Collegamento con il presente: un'informazione nuova o un risultato adesso ("I've lost my key" = non ce l'ho ora).
- been (essere stato e tornato) contro gone (andato e ancora là).
- just (appena), already (prima del previsto), yet (finora; in domande e negative, in fondo alla frase).
- In inglese britannico, per questi usi si preferisce il present perfect al past simple.
- Parte 2 (settimana dopo): esperienze fino a ora con ever/never ("Have you ever been to...?"), recently, in the last few days, so far, since..., today/this week/this year; "It's the first time I've...".
- Esercizi: situazione breve da trasformare in frase con il verbo dato; been o gone; just/already/yet in base alla situazione; domande con ever.

### Present perfect 2: esperienze, still / just / already / yet (quaderno dell'admin, lezione 5, 15 novembre)
Schema dell'admin (3a colonna del verbo, "aggiornamento"): ever? (mai, solo nelle domande), never + (mai, con verbo positivo), still + ? - (ancora), just + (appena), already + ? (gia'), yet - ? (gia' / ancora, in fondo alla frase).
- Esperienze: Have you ever been to London? I have never been to London. Have you ever seen the film? Have you ever eaten Thai food? Risposte corrette: Yes, I have. / No, I haven't. / No, I've never eaten it. ATTENZIONE: nel quaderno c'e' "Yes, I've never eaten Thai food", che e' SBAGLIATO (never gia' nega: la risposta giusta e' "No, I've never eaten Thai food"). Non riprodurre l'errore; puo' diventare un esercizio "correggi l'errore".
- Confronto con il past simple: I have eaten Thai food three times this week (periodo non finito, nessun momento preciso) / I ate Thai food yesterday (momento finito, yesterday chiama il past simple). Es. con been: I have never been to London (esperienza), I went to London last year (momento preciso).
- still: ancora, di solito PRIMA del verbo, con la negativa prima di hasn't / haven't: I'm still waiting for you. She still hasn't called me.
- just: appena, poco tempo fa: I've just eaten. I've just done my homework. I've just met Marco.
- already: gia', prima del previsto: I've already eaten. She has come already! (enfasi). Have you already finished? (sorpresa). Es. dell'admin: Have you already cleaned the kitchen? (probabilmente non lo so, ma penso di si).
- yet: finora, fino a ora (until now); domande e negative, in fondo: Have you eaten yet? I haven't cleaned the room yet (non ho ancora iniziato l'azione di pulire).
- Doppia negazione (nota dell'admin): in inglese non si usano mai le doppie negazioni. Con never il verbo resta positivo: I never go to school (non I don't never go). Vale anche per nobody, nothing, nowhere, no one: I haven't seen anybody / I've seen nobody (non I haven't seen nobody).
- Esercizi: ever o never; been o gone; just / already / yet / still in base alla situazione; domande con ever e risposte brevi; scelta tra past simple e present perfect con indizi (yesterday, last year, this week, ever); correggere l'errore di doppia negazione.

### Pronomi (quaderno dell'admin, "3 lezione", 15 novembre)
- Soggetto (si usano solo come soggetto, a inizio frase o prima del verbo): I, you, he, she, it, we, you, they.
- Complemento (dopo il verbo o la preposizione): me, you, him, her, it, us, you, them. Es. Yesterday I went to the cinema with you. Es. I saw them at the station. Give it to her.
- Esercizi: scegliere soggetto o complemento; sostituire il nome con il pronome giusto; riordinare; correggere (Me and her went... e' un errore tipico).

### Possessivi e genitivo sassone (quaderno dell'admin, 15 novembre)
- Aggettivi possessivi (davanti a un nome): my, your, his, her, its, our, your, their. Pronomi possessivi (da soli): mine, yours, his, hers, (its: non c'e' il pronome), ours, yours, theirs. I possessivi non vogliono l'articolo (NON the my pen).
- Esempi dell'admin da usare come modello (non copiarli tali e quali): That is my pen, this is mine. Yesterday I took your bag and I put it next to yours.
- Genitivo sassone, solo per persone e animali: Carlo's car (la macchina di Carlo), the dog's leg (la zampa del cane). Per le cose: the leg of the table oppure table leg (il nome usato come aggettivo). Aggiungere un cenno al plurale (the girls' room) e ai nomi in -s (James's bike).
- Errore tipico italiano: la macchina di Carlo = Carlo's car (ordine invertito), non the car of Carlo.
- Esercizi: scegliere aggettivo o pronome possessivo; completare con il genitivo; trasformare con of o con il genitivo; this / that con i possessivi (This is mine, that is hers).
- Avverbi di luogo (nota dell'admin): here = qui, there = li', over there = laggiu'. Usarli negli esempi (I put it there; The bus stop is over there).

### Present perfect con for / since e la forma di durata (quaderno dell'admin, lezione 5, 15 novembre)
- Parola chiave: da / per. Es. dell'admin: sto aspettando da due ore.
- Schema: from...to = da...a; since = momento iniziale (since Monday, since 2019, since I was ten); for = durata (for two hours, for three days, for ten years).
- Present perfect simple (duration form 1): I've studied maths for three days. I've known him for ten years. I haven't eaten for two days. How long have you lived here?
- Verbi di stato (non in forma continua): be, verbi di sentimento (love, like, hate, mind), percezione involontaria (see, notice), attivita' mentale (know, understand), volonta' (want), possesso (have, own): con questi SI USA il present perfect simple (I've known him for ten years, non I've been knowing). Nota di Claude: live, work e study ammettono entrambe le forme (I've lived here / I've been living here for two years); l'elenco dell'admin mette live tra i sentimenti, ma nei compiti l'accettare entrambe e spiegare che la forma continua insiste sulla durata.
- Con la negativa, di norma present perfect simple: I haven't eaten for two days (si preferisce a I haven't been eating).
- Esercizi: for o since; completare con il verbo nel present perfect; scrivere la domanda How long...?; trasformare "I started studying English in 2023" in "I have studied English since 2023"; scelta tra past simple e present perfect (I lived in Rome for two years = non vivo piu' li'; I've lived in Rome for two years = ci vivo ancora).

### Present perfect continuous (quaderno dell'admin e Unit 9-10 del libro, 15 novembre)
- have/has been + verbo in -ing. Duration form 2: I've been studying English for three years. How long have you been living here? She's been playing since she was eight.
- Usi: (1) attivita' che dura da un certo tempo e continua (how long, for, since); (2) attivita' appena finita o recente con risultati visibili: The ground is wet, it's been raining. My hands are dirty, I've been repairing my bike; (3) azioni ripetute, per sottolineare la durata: They have been going there for years.
- Si usa spesso con how long, for, since. Nota dell'admin: mai con la forma negativa nella duration form (I haven't been eating for two days e' evitato; si dice I haven't eaten for two days).
- Present perfect continuous contro present perfect simple (Unit 10): il continuous pensa all'ATTIVITA' (anche non finita: I've been painting my bedroom), il simple pensa al RISULTATO e alla quantita' (I've painted my bedroom, now it's yellow). How long have you been reading that book? (durata, continuous) / How many pages have you read? (quantita', simple). Joe has been eating too much recently (attivita'), Somebody has eaten all the chocolate, the box is empty (risultato).
- I verbi di stato (know, like, want, have...) non vanno al continuous; eccezione: want e mean (I've been meaning to phone Anna).
- Esercizi: completare con il verbo nella forma giusta (simple o continuous); scrivere la domanda con how long / how many; trasformare una situazione in una frase con una parola data; scegliere tra i due tempi dato il risultato o la durata; scelta tra tutti i tempi del presente e del passato.

### Intenzione e decisione (quaderno dell'admin, 15 novembre)
- be going to + verbo: intenzione o progetto gia' deciso. I'm going to buy a house in London. She's going to spend a night in that hotel.
- would like to / 'd like to + verbo: desiderio, richiesta gentile. I'd like to have some cake.
- will: scelta o risposta spontanea sul momento. What would you like to eat? I'll have some cake.
- Piccolo schema di scelta: progetto gia' preso = going to; desiderio = would like to; decisione ora = will. Usare nei dialoghi (listening del mercoledi', reading del telefono) e nella verifica. Ricordare che in canzoni e nel parlato going to diventa gonna.

### Verbi di gusto con -ing (quaderno dell'admin, 15 novembre)
- love, like, hate, enjoy (e don't mind) + verbo in -ing: I love watching TV. I like playing football. I enjoy cooking. What do you usually do? (come ripasso del present simple con gli avverbi di frequenza).

### Quantificatori (quaderno dell'admin, 15 novembre)
- some (+), any (? -), no (= not any, piu' forte; I've got no friends; There is no water in the fridge). Con no il verbo e' positivo.
- Uncountable: a lot of = tanto/a (+), much = tanto/a (? -), a little = poco/a. Countable: a lot of = tanti/e (+), many = tanti/e (? -), a few = pochi/e.
- I've got some friends (+). Have you got any friends? (?). I haven't got any friends (-). There isn't any bread. Is there any bread in the fridge? Yes, there's some bread on the table. (there is / there are solo come uso, non spiegato.)
- Per dire che proprio non c'e': I've got no coffee (= non ne ho proprio).
- too: troppo. Con gli aggettivi solo too (You are too tall). Con i nomi too much (uncountable) e too many (countable): I've got too much money. There are too many cars.
- Esempi tipo dell'admin: I haven't got much water but I've got a lot of beer. There are a lot of cars, there aren't many cars. Are there many people in the room? I've got a little time. There are a few cars.
- Esercizi: some / any / no; much / many / a lot of; a little / a few; too / too much / too many; correggere l'errore.

### Confronto tra i tre tempi (past simple, past continuous, present perfect)
Una schermata con tabella che risponde alla domanda "quale tempo uso?":
- Past simple: azione finita in un momento passato definito (yesterday, last week, in 2019, three days ago, when I was a child). Una cosa dopo l'altra in una storia.
- Past continuous: azione in corso a un momento del passato, sfondo di una storia, azione interrotta (when/while).
- Present perfect: collegamento con il presente, nessun momento passato definito (just, already, yet, ever, never, so far, this week, today, "I've lost my key").
- Parole spia da far notare: yesterday e last night chiamano il past simple, never e just il present perfect, while il past continuous. Con un tempo finito NON si usa il present perfect (I have seen him yesterday e' sbagliato).
- Esercizi: scegliere il tempo dato l'indizio, stessa situazione con due tempi diversi e due significati diversi, correggere l'errore, completare una mini storia.

### Countable e uncountable 1
- Countable: banana/bananas, si possono contare; uncountable: rice, water, music, money, sand, electricity, luck, che non hanno plurale e non si contano con numeri.
- a/an solo con countable singolare; i countable plurali stanno da soli (I like bananas); gli uncountable stanno da soli (I eat rice). Contenitori e unità: a bowl of rice, a packet of..., a grain of...
- some/any con countable plurali e uncountable; many/few con countable plurali; much/little con uncountable. A lot of con entrambi.
- Esercizi: correggere frasi dove serve a/an; completare con parole date usando a/an solo dove serve; scegliere much o many; singolare o plurale.

### Countable e uncountable 2 (più avanti)
- Nomi che sono countable in un significato e uncountable in un altro: a noise/noise, a paper/paper, a hair/hair, a room/room, an experience/experience, a time/time, a coffee/coffee.
- Nomi di solito uncountable: accommodation, advice, baggage/luggage, bread, chaos, furniture, information, luck, news, progress, scenery, traffic, weather, work, travel (contro a trip/a journey). Niente a/an e niente plurale (news è singolare).

### a/an e some; a/an e the (più avanti)
- a/an con countable singolare; per dire che cosa è qualcosa o qualcuno e il lavoro (She's a nurse); plurale da solo (Those are nice chairs). some = un certo numero di / non tutti; non si usa some per le cose in generale.
- Prima volta a/an, poi the (a sandwich... the sandwich); the quando è chiaro quale (the light, the door, the station, the bank, the doctor); a/an per tipo (a very cheap hotel) contro the per uno specifico; once a week, three times a day, £1.50 a kilo.

### Parole interrogative (note dell'admin dal suo quaderno, 7 novembre)
Parte 1 (lunedi' 9): where (dove), when (quando), who (chi), why (perche'; si risponde con because), which (quale, tra opzioni limitate: Which bus do you take?), whose (di chi: Whose pen is it?). Eventuale what come richiamo.
- Ordine della domanda: parola interrogativa + ausiliare + soggetto + verbo. Mostra la STESSA parola in quattro tempi, cosi' si ripassa la scelta del tempo: Where do you usually go? (present simple) / Where are you going? (present continuous) / Where did you go yesterday? (past simple) / Where have you been? (present perfect).
- Regola dell'admin: le parole interrogative non vogliono nulla davanti, la preposizione va in fondo alla frase: Who are you talking to? (non To who...). Con chi/cosa e' soggetto non serve do/did: Who called you?
- Esercizi: scrivere la domanda per una risposta data; scegliere la parola interrogativa giusta; riordinare le parole di una domanda; scegliere il tempo giusto nella domanda (yesterday, usually, now, ever).
Parte 2 (martedi' 10): how much / how many (quanto, quanti: much con gli uncountable, many con i countable plurali), how far (quanto e' lontano, distanza), how long (quanto dura; MAI how long time), how often (quanto spesso). Esempi: How much milk do we need? How many people came? How far is the station? How long did the film last? How often do you go to the gym?
- While NON e' una parola interrogativa (e' nell'elenco dell'admin): e' una congiunzione che va con il past continuous (I was cooking while he was studying). Spiegarlo in una frase e usarlo nella lezione di martedi' con when/while.

### La stanza e le preposizioni di luogo (quaderno dell'admin, 7 novembre)
Lista dell'admin, da usare come VOCABOLARIO della settimana 9-15 novembre (flashcard, esempi, esercizi, reading dell'hotel, listening del nuovo appartamento, writing su casa e quartiere) e, in forma di tabella, dentro la spiegazione di in/on/at di luogo di lunedi':
- on = sopra, a contatto (la penna e' sul tavolo); onto = sopra con movimento (la penna e' caduta sul tavolo)
- over / above = sopra, senza toccare
- under = sotto, in verticale o coperto da qualcosa; below = sotto, piu' in basso (altezza, livello)
- between = tra; behind = dietro; in front of = davanti; opposite = di fronte
- in = dentro; into = dentro con movimento; out of = fuori da
- to = a, verso (movimento); from = da
- near = vicino (generico); next to = accanto; close to = molto vicino
- this / these = questo/a, questi/e (vicini); that / those = quello/a, quelli/e (lontani)
- Parole della stanza (dal quaderno): table, chair, door, floor, ceiling, wall, light, picture, window, pen (la lista dell'admin continua: aggiungere altre parole comuni di casa e ufficio).
Esempi originali con una scena di stanza (la lampada e' sopra il tavolo, il gatto e' sotto la sedia...). Esercizi: scegliere la preposizione giusta guardando una descrizione, riordinare, completare, descrivere una stanza con 4 frasi.

### Preposizioni di luogo in/on/at, there is / there are, some / any
- NOTA DELL'ADMIN: there is / there are NON vanno spiegati (si sanno): si usano solo nelle frasi degli esercizi e degli esempi. Resta la spiegazione di in/on/at di luogo; some/any sono spiegati giovedi' con countable/uncountable.
- in (dentro uno spazio o una città), on (sopra una superficie, su una strada, su un piano), at (punto preciso: at the bus stop, at the door, at home, at work).
- (Solo per riferimento, NON spiegare) there is / there are, negativa e domanda: usarli liberamente nelle frasi degli esercizi (There aren't any shops near here. Is there a bank?).
- Contesti: casa, camera, città, hotel.

### Phrasal verbs (introduzione, più avanti)
- Verbi con in/on/up/off/away/back/out...: look out, get on, take off, run away; spesso il significato cambia (break down, find out, give up, get on, get by).
- Con preposizione: look forward to, keep up with, run away from, look up at.
- Con complemento: due posizioni (turn on the light / turn the light on), ma con un pronome una sola (turn it on, non turn on it).

## 5. Registro argomenti svolti

| Data | Formato | Tempo verbale / argomento | Mini argomenti e note |
|---|---|---|---|
| 2026-11-02 lun | grammatica | Present simple | in/on/at del tempo |
| 2026-11-03 mar | grammatica | Present continuous | |
| 2026-11-04 mer | listening | Una telefonata alla stazione | |
| 2026-11-05 gio | grammatica | Present simple vs continuous | avverbi di frequenza |
| 2026-11-06 ven | writing | Una giornata tipica | |
| 2026-11-07 sab | verifica | Present simple e continuous | |
| 2026-11-08 dom | ripasso | Present simple vs continuous | trappole (verbi di stato, -s dopo does, avverbi), in/on/at del tempo, ascolto leggero (6 Minute English, Big City Small World, Paddington, Shape of You solo ascolto guidato), riflessione scritta. Preparato senza i risultati della verifica: errori ricorrenti da raccogliere in 04_Progressi |
| 2026-11-09 lun | grammatica | Past simple | in/on/at di luogo con la stanza (on/onto, over/above, under/below, between, behind, in front of, opposite, into, out of, to/from, near/next to/close to); parole interrogative 1 (where, when, who, why, which, whose); there is/are solo negli esercizi; ripasso present simple/continuous. 26 esercizi |
| 2026-11-09 lun | reading | hotel, shopping per vestiti, dal medico e in farmacia | settimana 9-15 novembre; phrasal verbs e canzoni This Is the Life (Amy Macdonald) e Starlight (Muse) della settimana |
| 2026-11-10 mar | grammatica | Past continuous | parole interrogative 2 (how much, how many, how far, how long, how often; while spiegato come congiunzione); this/these/that/those (schermata veloce); there is/are solo negli esercizi; confronto past simple/continuous con when/while; ripasso past simple, in/on/at di luogo, parole interrogative 1. 26 esercizi |
| 2026-11-11 mer | listening | Un nuovo appartamento (telefonata Emma e Jack) | there is/are, preposizioni di luogo (on, between, above, next to, opposite, close to), past simple del trasloco; 16 esercizi |
| 2026-11-12 gio | grammatica | Present perfect 1 | been/gone, just/already/yet; countable e uncountable (a/an, some/any, much/many/a lot of); schermata di confronto tra i tre tempi passati; blocco misto di scelta del tempo; ripasso past simple, past continuous, how often. 26 esercizi |
| 2026-11-13 ven | writing | Descrivere casa o quartiere e diario del weekend | there is/are, a lot of / much / many, preposizioni di luogo (between, opposite, next to, at/on/in), past simple del diario, linkers (first, then, after that); due testi modello, checklist, 25 esercizi, compito libero (non corretto dall'app) |
| 2026-11-14 sab | verifica | Past simple, past continuous, present perfect (scelta del tempo) | 9 esercizi su scelta del tempo (indizi yesterday/last night/while/yet/just, risultato adesso, been/gone, errore da correggere, order con when); poi between/at di luogo, whose, how often, much, some/any, advice; testo su Ben a Edimburgo con 4 domande. 20 punti |
| 2026-11-15 dom | ripasso | Past simple, past continuous, present perfect (scelta del tempo) | trappole (did + verbo base, no present perfect con tempo finito, been/gone, when/while), preposizioni di luogo, parole interrogative, countable/uncountable, present simple/continuous richiamo; ascolto leggero (6 Minute English, Big City Small World, Notting Hill, Viva la Vida solo ascolto guidato), riflessione scritta. Preparato senza i risultati della verifica: errori ricorrenti da raccogliere in 04_Progressi. 28 esercizi |

Reading già fatti: aeroporto, ristorante, indicazioni, hotel, shopping per vestiti, dal medico e in farmacia. Canzoni già fatte: Young and Beautiful, Yellow (settimana 2-8 novembre), This Is the Life, Starlight (settimana 9-15 novembre).

## 6. Note dell'admin e revisione del weekend

- 2026-11-07: ogni lezione di grammatica deve avere anche un tempo verbale oltre ai mini argomenti, almeno per le prime settimane. Lezioni leggermente più lunghe (la prima settimana richiedeva meno di 10 minuti). Settimana 9-15: past simple, past continuous, present perfect 1.
- 2026-11-07: dal secondo quaderno dell'admin: stanza e preposizioni di luogo (on/onto, over/above, under/below, between, behind, in, into, out of, in front of, opposite, to, from, near, next to, close to) e this/these/that/those. Da inserire tra le parole (flashcard) e nei reading di situazioni, dettagli nella sezione 4.
- 2026-11-07: confermati: under = sotto in verticale o coperto, below = sotto come livello; this/these/that/those con spiegazione veloce (martedi' 10); lunedi' 9 puo' essere piena (past simple, parole interrogative, preposizioni).
- 2026-11-07: there is / there are non vanno spiegati, solo usati negli esercizi. Al loro posto le PAROLE INTERROGATIVE dal quaderno dell'admin (sezione 4): lunedi' where/when/who/why/which/whose, martedi' how much/many/far/long/often.
- 2026-11-07: la verifica del sabato deve confrontare l'uso dei tre tempi (quando si usa uno e non l'altro): regola nella sezione 2. Nuova sezione settimanale con una decina di phrasal verbs e vari esempi per ognuno (sezione 7).

- 2026-11-09: canzoni della settimana 9-15 cambiate dall'admin: This Is the Life (Amy Macdonald) e Starlight (Muse). Quelle della settimana precedente (Young and Beautiful, Yellow) restano nella sezione lezioni passate > Canzoni. In songs-queue.json la settimana 16-22 e' tornata a 'proposed' (Yesterday, Someone Like You) in attesa della scelta dell'admin; l'admin ha chiesto in futuro canzoni utili per i tempi passati.

- 2026-11-15: l'admin ha portato nuovi argomenti dai suoi quaderni e dal libro (Unit 9 e 10): doppia negazione, pronomi soggetto e complemento, possessivi, genitivo sassone, quantificatori (some/any/no, a lot of/much/many, a little/a few, too much/too many), present perfect 2 (ever, never, still, just, already, yet), duration form (for, since, how long), present perfect continuous e confronto con il simple, intenzione e decisione (going to, would like to, will), love/like/hate/enjoy + -ing, here/there. Distribuiti nel piano 16-22 novembre (sezione 3, dettagli nella sezione 4). Richiesta: nella settimana riproporre in ogni lezione esercizi di TUTTI i tempi verbali fatti, per fissarli (blocco di ripasso piu' ampio con scelta del tempo). Canzoni: l'admin vuole confermare personalmente le coppie (ha chiesto proposte): fino alla conferma vale la coppia in coda. Correzioni di Claude agli appunti: "Yes, I've never eaten" e' sbagliato (No, I've never eaten...); live/work ammettono anche il continuous; nella forma negativa della duration form si usa il simple.

- 2026-11-15 (sera): per il weekend 21-22 novembre l'admin vuole una verifica che riprende tutti gli argomenti, divisa in test 1 (sabato) e test 2 (domenica): 30 esercizi di grammatica, 30 domande di vocabolario e altre 30 su quello che manca (Claude: phrasal verbs, correzione errori, comprensione di testi brevi; da confermare). Dettagli nel piano della settimana 16-22. Canzoni 16-22: l'admin ha scelto la coppia A (Have You Ever Seen the Rain?, Haven't Met You Yet).

- 2026-11-15 (sera): l'admin dice che le domande di comprensione sono spesso troppo facili e vuole reading piu' lunghi, complessi e interessanti, con ricerca sul web. Standard nella sezione 8, che prevale sulla procedura generica.

## 7. Phrasal verbs della settimana (nuova sezione dal 9 novembre)

Ogni settimana, la domenica notte (quando domani e' lunedi), insieme a reading e canzoni si crea UN file lessons/phrasal-<lunedi della settimana>.json di tipo kind:"phrasal", che nell'app compare nella sezione "Phrasal verbs della settimana". Modello esatto: lessons/phrasal-2026-11-09.json.

- 10 phrasal verbs nuovi ogni settimana, mai ripetuti (controlla l'elenco qui sotto). Scelta di uso quotidiano e livello B1, legati ai temi della settimana quando possibile.
- Per ogni verbo: significato in inglese semplice e in italiano, almeno 3 frasi d'esempio originali (con traduzione) che mostrano usi diversi (se il verbo ha piu' significati, almeno due: per esempio take off con i vestiti e con l'aereo), indicazione se e' separabile (turn it on) o no, e un contrario o un verbo collegato quando c'e'.
- Struttura: 5 schermate explain (2 verbi per schermata, tabella Phrasal verb / Meaning / Italiano piu' le frasi d'esempio; la prima schermata della prima settimana spiega anche la regola del pronome in mezzo), 20 esercizi (8 mcq, 8 fill, 4 order, tutti con why e why_it), 10 flashcard (una per verbo).
- Campi del file: kind:"phrasal", week, order:1, title "Phrasal verbs of the week", title_it, goal, goal_it, minutes:20, steps, cards. Voce nell'index: {id:"phrasal-<week>", kind:"phrasal", week, order:1, title, title_it, goal, goal_it, minutes, exercises}.
- Registrare i 10 verbi qui sotto dopo averli creati.

Verbi gia' fatti:
- Settimana 9 novembre: get up, come back, turn on, turn off, put on, take off, find out, give up, break down, look forward to.

Proposta per le prossime settimane (da rivedere nel weekend, modificabile):
- 16 novembre: get on, get off, pick up, drop off, set off, look up, look after, wake up, go out, sit down.
- 23 novembre: carry on, run out of, throw away, work out, check in, check out, call back, fill in, hurry up, slow down.
- 30 novembre: take care of, get along with, ask for, look like, get back, get into, put away, cheer up, stand up, move on.

## 8. Standard di qualita' di reading e domande di comprensione (richiesta dell'admin, 15 novembre)

Feedback dell'admin: le domande di comprensione sono spesso troppo facili (la risposta giusta si trova a colpo d'occhio) e i reading devono essere piu' lunghi, piu' complessi e piu' interessanti, con ricerca sul web se serve. Da applicare da subito a TUTTO: reading, listening (domande di comprensione), canzoni (domande sul significato), verifiche.

### Reading (vale per i 3 reading della settimana creati la domenica notte)
- Ogni reading ha DUE parti: (1) un TESTO LUNGO in inglese britannico di 300-450 parole (articolo divulgativo, post di blog, email, mini guida o racconto) sulla situazione della settimana, con fatti reali e curiosita' che rendano il tema interessante; (2) il DIALOGO della situazione, di 14-18 battute, con le frasi chiave. Livello B1+ con alcune parole B2, che vanno spiegate nella tabella delle frasi chiave (10 frasi o parole invece di 7).
- RICERCA: se hai WebSearch e WebFetch, cerca fatti reali e aggiornati sul tema (per esempio come funzionano i biglietti del treno in Gran Bretagna: Advance, Off-Peak, Railcard; le abitudini dello small talk britannico: il tempo, la fila; come funziona il pronto soccorso e il NHS; come funzionano le mance nei ristoranti). Usa almeno due fonti per i fatti, cifre e regole che possono cambiare, e nel testo scrivi "at the time of writing" quando serve. Se la ricerca non e' disponibile, usa solo fatti di cui sei sicuro, evita cifre precise e dillo nel riepilogo.
- Il testo e' SEMPRE scritto da te con parole tue: non copiare ne' riassumere da vicino un articolo (diritto d'autore). I fatti si possono riprendere, la forma no. Nessun link inventato: se citi le fonti consultate, in una breve schermata finale "Where this comes from" nomina solo siti e organizzazioni realmente consultati (per esempio National Rail, NHS, BBC Learning English, British Council) e metti un link SOLO se l'hai aperto e verificato.
- Esercizi: 14-16 invece di 8 (minutes: 25): 6-7 mcq di comprensione DIFFICILI, 2-3 mcq o fill sul vocabolario in contesto, 3 fill sulle frasi chiave, 2 order (domande o richieste gentili), 1-2 esercizi vero / falso / non detto (come mcq con tre opzioni: True, False, Not stated). Dalle flashcard, 10-12 invece di 7.
- Il tema della settimana (tempi verbali e strutture del piano) entra nei testi in modo naturale: per esempio present perfect e past simple nel racconto di un'esperienza, going to e would like to nei progetti.
- Tre reading della stessa settimana = tre temi e tre forme diverse (per esempio un articolo, un'email, una mini guida), non lo stesso schema ripetuto.

### Domande di comprensione (reading, listening, canzoni, verifiche)
Regole per ogni mcq di comprensione:
1. Tutte le quattro opzioni sono plausibili, simili per lunghezza e registro. La risposta giusta NON e' la piu' lunga, NON e' quella che ripete le parole del testo e NON e' sempre la piu' specifica. I distrattori riusano parole del testo ma sono sbagliati (trappola lessicale) o sono veri in generale ma non lo dice il testo.
2. Niente domande risolvibili cercando una sola parola. Almeno meta' delle domande di ogni file richiedono inferenza o collegare due informazioni: perche' una persona fa una certa cosa, che cosa significa una frase nel contesto, a chi o a che cosa si riferisce "it" / "they", quale conclusione si puo' trarre, qual e' lo scopo del testo, che atteggiamento ha chi parla, che cosa NON e' vero.
3. Includere domande su dettagli precisi (numeri, orari, ordine degli eventi, negazioni, "only", "except", "unless") e almeno una domanda "which statement is NOT true / not stated".
4. Evitare risposte sciocche o ovvie (nessun distrattore assurdo). Ogni distrattore deve poter essere scelto da chi ha letto in fretta.
5. La risposta giusta cade in posizioni diverse e distribuite in modo equilibrato (non sempre B o C).
6. why e why_it dicono dove sta la prova nel testo e perche' ciascun distrattore e' sbagliato (almeno il piu' tentante).
7. Prima di salvare, rileggi ogni domanda come uno studente stanco: se la risposta si trova in meno di cinque secondi, rendila piu' sottile.
8. Per i listening: stesse regole; le domande sul secondo ascolto chiedono dettagli e inferenze, non solo lo scopo generale.
