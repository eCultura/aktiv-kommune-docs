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
Før man kan generere en fakturafil, må man forut ha [godkjent og klargjort fakturagrunnlaget.](https://manual.aktiv-kommune.no/?p=571)

> OBS! Før man starter med genereringen må man vite at man har registrert rett system (Agresso brukes i beskrivelsen her, men det er likt for andre systemer). For å endre konteringsdimensjoner se [Hvordan endre konteringsdimensjoner for fakturaeksport.](http://manual.aktiv-kommune.no/?p=622)

Når fakturagrunnlag er klargjort, kan du generere en fakturafil ved å velge kommandoen:

<strong>BOOKING => FAKTURAEKSPORTER => KLAR FOR GENERERING</strong>

Skjermbildet ser da slik ut: 
![skjermbilde fakturagenerering](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbildefakturagenerering.png)

Kontroller at alle fakturabehandlere (om kommunen har flere av disse) er ferdig med å fakturere sine respektive bygg/anlegg innen avtalt tid (for eksempel senest den 9. hver måned).

Når alle filene fra fakturabehandlere er klar, klikk på 
![generer filer](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbildegenererfiler.png)

Filene vil nå samles i en fil og få tildelt et ID-nummer. 

Under "loggfil" kan du klikke på "last ned" og lagre filen som et dokument i en egen mappe på datamaskinen. 

Se skjermbilde for navn og forklaring på fil
![skjermbilde fil navn og forklaring](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/forklaringfildato.png)

Eksempel:
1502021 står for 15 = år, 02 = måned, og neste 02 = dag, og 1 er nummerering av antall filer om du sender flere filer på samme dag. Neste fil vil da måtte ha 2 til slutt, og neste deretter 3 til slutt, etc.

Klikk så "Last opp" under "Eksport". Filen legger seg da på en server hvor den vil bli hentet og overført til Agresso i løpet av en kjøring som finner sted om natten. 

Send så en e-post med fakturafilen(e) til de aktuelle personene i din kommune (fakturering/økonomi). 

> NB! Hver kommune må tilpasse denne rutinen slik den må passe for dere. Poenget er at saksbehandler(faktureringsansvarlig) i Aktivkommune må <em>varsle</em>  og <em>faktisk overføre/sende aktuell fakturafil </em> til en person på økonomi/regnskap i aktuell kommune.

Dersom alt er OK mottar du en e-post fra økonomi/regnskap /(Bergen: LRS) som bekrefter antall elementer og totalsummen som er overført. 
Innholdet i filen har nå fått ordrenummer (f.eks. i Bergen er Aktivkommune tildelt 3700(...)-serien, det vil si at ordrenummeret starter med 3700 (...). 

Dersom det finnes feil i filen som er overført, vil den som har ansvar for genereringen motta en oversikt over dette fra økonomi/regnskap (Agresso). 
Alle feil må korrigeres før filen blir fakturert i Agresso. På sett og vis må faktureringansvarlig gjenta opersjonene som er beskrevet under "generering av fakturagrunnlag"