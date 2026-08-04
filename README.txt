MIN LP-SAMLING v1.0

Last opp alle filene i denne mappen til samme mappe i GitHub-repositoriet ditt:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

Appen lagrer LP-er og egne, komprimerte coverbilder lokalt i IndexedDB på enheten.
Bruk Sikkerhetskopi-knappen regelmessig for å eksportere samlingen til en JSON-fil.

Digitalt cover-søk krever internett. Resten av appen kan brukes uten internett etter at PWA-en er lastet inn én gang.

Merk: v1.0 kan søke etter digitale cover når artist og album er skrevet inn. Automatisk identifisering av artist og album direkte fra et bilde krever en ekstern bildeanalyse-tjeneste og er ikke aktivert i denne lokale versjonen.


NYTT I V1.1
- Henter opptil 200 albumutgivelser fra en artistkatalog.
- Søker i både norsk og amerikansk katalog for bedre dekning.
- Registrer flere album fra samme artist samtidig.
- Velg signert/ikke signert for hvert album i flervalgslisten.
- Hopper over album som allerede er registrert.
