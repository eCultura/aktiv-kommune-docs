---
ID: 522
post_title: Hvordan legge til ny ressurs?
author: Marie Aune
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=522
published: true
post_date: 2017-12-02 09:06:38
---
>En ressurs er selv kjernen i bookingsystemet. Det er denne som leies ut, og den må derfor være unik. En ressurs er alltid tilknyttet en "ressursgruppe" (som er opprettet ved BOOKING=>BYGG/ANLEGG. Et eksempel: Har idrettsbygget "Voldahallen" " tre saler og det skal være mulig å leie disse hver for seg, så må de tre salene skilles ved å opprette tre ressurser tilknyttet ressursgruppen (bygget) "Voldahallen". Ressursene kan kalles "Sal A, Sal B og Sal C" eller "Sal 1, Sal 2 og Sal 3".

Filmen viser i korte trekk hvordan du legger til en ny ressurs. For mer utdypet informasjon les teksten under.
http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Ny-ressurs.mp4


Når du har opprettet en ressursgruppe (et bygg/anlegg), så må du tilknytte ressurser til det. Ressurser knyttes opp mot et bygg/anlegg under opprettelse.

En ressurs kan være:
1. en del av et bygg, som f.eks. en hall, garderobe, eller 
2. en del av et uteområde, f.eks. en park, en fotballbane, eller
3. utstyr som kan leies/lånes ut, f.eks. AV-utstyr, håndballmål, kano.
En ressurs kan teoretisk inngå i flere ressursgrupper.

Ressursene kan leies ut hver for seg eller samlet.

For å opprette en ny ressurs går du til:

<strong>BOOKING => BYGG/ANLEGG => RESSURSER </strong>

Du får da opp dette skjermbildet: 
![skjermbilde ressurser](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbilderessurser.png)

For å opprette ny ressurs klikker du på 
![ny](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png)

### Fyll ut informasjonen om ressurs: 
Feltnavn | Forklaring / Aksjon
--------------------------------|-----------------------------------------------------
**Navn:** |Navn på ressurs. NB! DET ER DETTE navnet SOM BLIR SØKBART og VISES I BOOKINGFRONTEND.
**Sortering:** |   ---Ikke i bruk.---
**Bygg/anlegg:** |Bygg/anlegg (<strong>RESSURSGRUPPEN</strong>) som ressursen skal knyttes til. Bygg/anlegg (Ressursgruppe) må legges til før man legger til ressurs. For å legge til ny ressursgruppe (nytt bygg/anlegg) se [her](http://manual.aktiv-kommune.no/?p=166). Man vil få opp forslag når man skriver om bygg/anlegg (ressursgruppe) er lagt inn. 
**Type:** |Velg hvilken ressurstype du legger til fra nedtrekksmenyen.
**Beskrivelse:** |Beskrivelse av ressursen.
**Organisasjons ID-er:** |Her kan du legge inn en kommaseparert liste med organisasjons ID-er som vil få e-post dersom noen avbestiller denne ressursen. <em>For eksempel: 976245539, 994239929, 975674614</em>. NB! Disse organisasjonene må være registrert under "BOOKING=>ORGANISAJONER" for å få melding.

Når du er ferdig klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

> Ønsker du å knytte bilde eller filer til ressursen,  kan dette gjøres i det nye skjermbildet ved å klikke på *Legg til dokument*

På det nye skjermbildet vil det i bunnen ligge tre knapper med valgene: 
![knappevalg ressurser](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbilderessurs.png)

Dersom du ønsker å redigere ressursen du har lagt til, klikker du på:
![rediger](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/rediger.png)

Ønsker du å se kalenderoversikten for ressursen, klikker du på:
![ressurskalender](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/ressurskalender.png)

Ønsker du å gå tilbake til hovedsiden for ressurser, for å legge til enda en ny ressurs eller avslutte redigeringen av ressursen klikker du på:
![avbryt](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/avbryt.png)

## Aktiviteter
Ressursene er knyttet til Aktiviteter. 
Aktiviteter er organisert hierarkisk med topp-nivåer som f.eks. «Idrett», «Kultur», "Skole" osv.
Hvert toppnivå kan ha en videre forgrening av underkategorier, f.eks. IDRETT -> FOTBALL, og IDRETT -> BASKETBALL. Dette er bare aktuelt om kommunen ønsker å ha statistikk på hvilke aktiviteter som ressursen brukes til.

Målgrupper og deltakerstatistikk er også i søknaden differensiert per toppnivå.

>Hensikten med å knytte en ressurs til en aktivitet er todelt:
1. Type toppnivå bestemmer om det er fagavdelingen for IDRETT eller fagavdelingen for KULTUR som skal saksbehandle søknader som kommer inn på ressursen. Dette må altså avtales i forkant av opprettelsen av ressursen.
2. Dersom en kommune vil ha statistikk på hva ressursen brukes til, så vil man raskt kunne se om det er IDRETT eller KULTUR som bruker ressursen. En svakhet her er at det av og til er et idrettslag som benytter en "kulturressurs" (f.eks. et møterom i et kulturhus), eller omvendt; det kan komme et kulturarrangement i en "idrettsressurs" (Idrettshall). Men er saksbehandler klar over feilkildene, så kan statistikken korrigeres og avvik forklares.

## Kalender
Kalenderen vises per ressurs, og kan vises i to nivåer:
1) Per ressurs
- Når en viser kalender for en ressurs, vil det fremgå hva som er ledig tid.
2) Per ressursgruppe («Bygg/Anlegg»)
-  Kalenderen viser bare ressurser som er booket. 
-- Ledig tid vises for ressurser som også er «opptatt» innenfor tidsrammen i kalenderen.
-- Ressurser som er helt ledig, vises ikke på dette nivået.(Dette er en svakhet vi ønsker å rette på i kommende versjoner av systemet)


Når man har opprettet ressurs, så er neste steg å opprette [sesong og rammetid](http://manual.aktiv-kommune.no/?p=502) for å definere når ressursene er tilgjengelig for utleie/lån.