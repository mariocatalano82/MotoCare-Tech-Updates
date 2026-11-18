# MotoCare Tech — aggiornamenti approvati

Questo repository distribuisce esclusivamente profili diagnostici firmati e
pacchetti completi MotoCare Tech. Non contiene il repository sorgente privato,
chiavi private, credenziali, trace diagnostiche o dati degli utilizzatori.

I profili sono definizioni dati per driver compilati e revisionati. Non sono
plugin eseguibili. Ogni nuovo driver richiede un programma completo approvato.
Cataloghi: profiles/catalog.json e software/catalog.json. Programmi: Releases.
L’app verifica Ed25519, SHA-256, revoche, sequenze e piattaforma senza token GitHub.
Le chiavi di fiducia sono incorporate nell’app, non recuperate da questo server.

0.12.0: mantenere i profili offline; chiudere l’app prima di sostituire il programma.
Le firme di distribuzione non equivalgono ad Authenticode/notarizzazione o a prove
su una motocicletta. I limiti S0–S4 sono dichiarati dai profili e dall’app.
Le condizioni di riuso di ogni profilo sono indicate nella sua provenienza;
i programmi completi rimangono soggetti ai termini MotoCare. Nessun diritto sul
codice sorgente privato viene concesso dalla pubblicazione di questi archivi.
