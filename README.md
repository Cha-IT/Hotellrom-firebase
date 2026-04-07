# Oppgave: Hotellrom-database

I denne oppgaven skal du lage en enkel webside som bruker Firebase til å registrere hotellrom og finne ledige rom.

Du skal legge inn minst 15 hotellrom i en Firebase Firestore-database. Rommene skal registreres med romnummer, etasje, type (enkeltrom, dobbeltrom, suite), maks antall sengeplasser, og status (om rommet er ledig eller opptatt).

Lag en webside eller web-app der en bruker kan søke opp hotellrom i databasen baset på gitte kriterier (se eksempler under). Du velger selv om du vil lage websiden i React eller Vanilla (HTML/CSS/JS). 


Bruk [guidene om å skrive og lese data i Cloud Firestore](https://cha-im.github.io/note/Firebase) som bakgrunnsstoff.

## Kriterier
Det skal gå an å gjøre alle disse søkene på nettsiden:
1. Skriv ut informasjon om alle rom på hotellet.
2. Skriv ut alle rom i 1. etasje (eller la brukeren velge etasje).
3. Skriv ut alle rom med mer enn to sengeplasser (eller la brukeren velge antall sengeplasser).
4. Skriv ut alle rom som er ledige.
5. Skriv ut alle suiter som er ledige.
6. Skriv ut alle dobbeltrom i 1. etasje som er ledige.


## Ekstraoppgave
Legg inn funksjonalitet for å booke et rom. Statusen på rommet skal da endres fra ledig til opptatt og Navn og kontaktinfo til personen som har bestilt rommet skal legges inn på rommet i databasen.
