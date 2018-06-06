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
Før du kan generere en fakturafil, må du forut ha [godkjent og klargjort fakturagrunnlaget.](https://manual.aktiv-kommune.no/?p=571)

> OBS! Før du starter med genereringen, må du vite at du har registrert rett mottaker/økonomisystem (Agresso brukes i beskrivelsen her, men det er likt for andre økonomisystemer). For å endre konteringsdimensjoner se ["Hvordan endre konteringsdimensjoner for fakturaeksport."](http://manual.aktiv-kommune.no/?p=622)

Når fakturagrunnlag er godkjent og klargjort, kan du generere en fakturafil ved å velge kommandoen:

<strong>BOOKING => FAKTURAEKSPORTER => KLAR FOR GENERERING</strong>

Skjermbildet ser da slik ut: 
![skjermbilde fakturagenerering](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbildefakturagenerering.png)

Kontroller at alle fakturabehandlere (om kommunen har flere av disse) er ferdig med å fakturere sine respektive bygg/anlegg (ressursgrupper) innen avtalt tid (for eksempel senest den 9. hver måned).

Når alle filene fra fakturabehandlere/saksbehandlerne er klar, klikk på 
![generer filer](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbildegenererfiler.png)

Filene vil nå samles i en fil og få tildelt et ID-nummer. 

Under "loggfil" kan du klikke på den blå teksten "last ned", og i neste omgang lagre filen som et dokument i en egen filmappe. Du velger selv om det skal lagres en kopi av filen lokalt på C:/-disken (anbefales ikke) eller på et (personlig) fellesområde (en annen disk). 

..

Se skjermbilde for navn og forklaring på fil
![skjermbilde fil navn og forklaring](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/forklaringfildato.png)

Eksempel:
1502021 står for 15 = år, 02 = måned, og neste 02 = dag, og 1 er nummerering av antall filer om du sender flere filer på samme dag. Neste fil vil da måtte ha 2 til slutt, og neste deretter 3 til slutt, etc.

Klikk så "Last opp" under "Eksport". 
Filen legger seg da på en server (avtalt filområde) hvor den vil bli hentet og overført til Agresso i løpet av en kjøring som finner sted om natten. 

Send så en e-post med fakturafilen(e) til de aktuelle personene i din kommune (økonomi/regnskap/fakturering). 

Dersom alt er OK, så mottar du du en e-post fra økonomi/regnskap/fakturering /(i Bergen: LRS)/ som bekrefter:
1. antall elementer og 
2. totalsummen 

som er overført til økonomisystemet.

> NB! Hver kommune må trolig justere og tilpasse denne rutinen noe. Poenget med rutinen er at saksbehandler(faktureringsansvarlig) i Aktivkommune må:
1. <em>varsle</em> en person på økonomi/regnskap i aktuell kommune om at fakturafil er klar, 
2. <em>faktisk tilrettelegge</em> for filoverføring, eventuelt sende aktuell fakturafil til rett sted/mottaker og
3. <em>ideelt sett motta</em> melding fra økonomi/regnskap om at overføringen har gått greit og at videre fakturering skjer i økonomisystemet (eller eventuelt få et varsel om at det er funnet feil i fakturagrunnlaget).

Innholdet i filen har nå fått et ordrenummer (f.eks. i Bergen er Aktivkommune tildelt 3700(...)-serien, det vil si at ordrenummeret starter med 3700 (...). 

Dersom det finnes feil i filen som er overført, vil faktureringsansvarlig i Aktivkommune (som regel en saksbehandler) normalt motta en oversikt over feilene fra økonomi/regnskap (Agresso). 

Alle feil må korrigeres før filen kan bli oversendt på ny fra Aktivkommune og til økonomisystemet. Faktureringsansvarlig må finne feilene og rette på disse; 
med andre ord:
gjenta operasjonene som er beskrevet under [klargjøring og generering av fakturagrunnlag.](https://manual.aktiv-kommune.no/?p=571)