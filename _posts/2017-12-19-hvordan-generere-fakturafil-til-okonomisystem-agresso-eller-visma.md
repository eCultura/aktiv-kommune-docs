---
ID: 567
post_title: >
  Hvordan generere fakturafil til
  økonomisystem? (Agresso eller Visma)
author: Ragnar Buset
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=567
published: true
post_date: 2017-12-19 13:05:43
---
Før man kan generere en fakturafil, må man [klargjøre fakturagrunnlag.](https://manual.aktiv-kommune.no/?p=571)

Når dette er gjort kan man generere en fakturafil ved å gå til:

OBS! Før man starter med genereringen må man vite at man har registrert rett system (Agresso brukes i beskrivelsen her, men det er likt for andre systemer). For å endre konteringsdimensjoner se [Hvordan endre konteringsdimensjoner for fakturaeksport.](http://manual.aktiv-kommune.no/?p=622)

BOOKING => FAKTURAEKSPORTER => KLAR FOR GENERERING

Skjermbildet ser da slik ut: 
![skjermbilde fakturagenerering](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbildefakturagenerering.png)

Kontoller at alle fakturabehandlere er ferdig med å fakturere sine respektive bygg/anlegg innen avtalt tid (senest den 9. hver måned).
Når alle filene fra kulturkontorene er klar, klikk på 
![generer filer](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbildegenererfiler.png)
Filene vil nå samles i en fil og få tildelt et ID-nummer. 

Under "logfil" kan du klikke på "last ned" og lagre filen som et dokument i en egen mappe på datamaskinen. Se skjermbilde for navn og forklaring på fil
![skjermbilde fil navn og forklaring](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/forklaringfildato.png)
1502021 står for 15 = år, 02 = måned 02 = dag, er nummrering av antall filer, en kan sende flere filer på samme dag, og neste fil vil da måtte ha 2 til slutt.

Klikk så "last opp" under "eksport". Filen legger seg da på en server hvor den vil bli hentet og overført til Agresso i løpet av en kjøring som finner sted om natten. 

Send så mail med følgende tekst til følgende personer: 
![mail](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/filoverforing.png)
Filnavnet skrives slik det ser ut når det ligger på serveren. Antall og beløp finner man i Portico. 
Tips: Legg inn forsinkelse på mailen (kl.12.00 påfølgende dag) slik at mottakerne ikke får denne før filen er overført til Agresso.

Dersom alt er OK mottar du en mail fra LRS som bekrefter antall elementer og totalsummen som er overført. Innholdet i filen har nå fått ordrenummer som begynneer på 3700(...). 
Dersom det finnes feil i filen som er overført, vil den som har ansvar for genereringen motta en overikt over dette fra Afresso. Alle feil må korrigeres før filen blir fakturert i Agresso.