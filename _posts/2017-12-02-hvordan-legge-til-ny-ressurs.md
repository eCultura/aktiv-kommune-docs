---
ID: 522
post_title: >
  Hvordan legge til nytt utleieobjekt (ny
  ressurs)?
author: Marie Aune
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/arkiv/522
published: true
post_date: 2017-12-02 09:06:38
---
>Et utleieobjekt (i Aktivkommune omtalt som "ressurs") er selve kjernen i bookingsystemet. Det er selve utleieobjektet som leies ut, og den må derfor være unik. En ressurs er alltid tilknyttet en "ressursgruppe" (som er opprettet ved BOOKING=>BYGG/ANLEGG). Et eksempel: Idrettsbygget "Voldahallen" har tre saler. Dersom det skal være mulig å leie disse salene hver for seg, så må de tre salene skilles ved å opprette tre utleieobjekter (ressurser) tilknyttet ressursgruppen (bygget) "Voldahallen". Ressursene må få unike navn innenfor ressursgruppen. for eksempel "Sal A, Sal B og Sal C". Men skal hele Voldahallen leies ut til et større arrangement, så må altså alle de tre salene bookes/bestilles samtidig.

Filmen viser i korte trekk hvordan du legger til en nytt utleieobjekt (ny ressurs). For mer utdypet informasjon les teksten under.
http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Ny-ressurs.mp4


Når du har opprettet en ressursgruppe (et bygg/anlegg), så må du tilknytte utleieobjekter  (ressurser) til det. Et utleieobjekt må alltid knyttes opp mot en ressursgruppe (et bygg/anlegg) under opprettelse.

Et utleieobjekt (ressurs) kan være:
1. en del av et bygg, som f.eks. en hall, garderobe, et rom eller 
2. en del av et uteområde, f.eks. en park, en fotballbane, eller
3. utstyr som kan leies/lånes ut, f.eks. AV-utstyr, håndballmål, kanoer.

Et utleieobjekt (ressurs) kan rent teoretisk inngå i flere ressursgrupper, men for praktisk bruk anbefales det at et utleieobjekt, f.eks. en gymsal tilknyttet en skole opprettes en gang, og at Skolen disponerer gymsalen på dagtid (fra kl.08 - 16), og at idrett disponerer gymsalen på kveldstid (fra kl. 16 - 22). Dette styres gjennom begrepene "Sesong og rammetid" (for å lese mer om dette,  se henvisning helt nederst på denne siden)
 
Utleieobjektene kan leies ut hver for seg eller samlet.

For å opprette en nytt utleieobjekt (ressurs) velger du kommandoen:

<strong>BOOKING => BYGG/ANLEGG => RESSURSER </strong>

Du får da opp dette skjermbildet: 
![skjermbilde ressurser](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbilderessurser.png)

For å opprette nytt utleieobjekt (ressurs) klikker du på 
![ny](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png)

### Fyll ut informasjonen om utleieobjektet/ressursen: 
Feltnavn | Forklaring / Aksjon
--------------------------------|-----------------------------------------------------
**Navn:** |Navn på utleieobjekt/ressurs. NB! DET ER DETTE navnet SOM BLIR SØKBART og VISES I BOOKINGFRONTEND.
**Sortering:** |   ---Ikke i bruk.---
**Bygg/anlegg:** |Bygg/anlegg (<strong>RESSURSGRUPPEN</strong>) som ressursen skal knyttes til. Bygg/anlegg (Ressursgruppe) må legges til før man legger til ressurs. For å legge til ny ressursgruppe (nytt bygg/anlegg) se [her](http://manual.aktiv-kommune.no/?p=166). Man vil få opp forslag når man skriver om bygg/anlegg (ressursgruppe) er lagt inn. 
**Type:** |Velg hvilken ressurstype du legger til fra nedtrekksmenyen.
**Beskrivelse:** |Beskrivelse av utleieobjektet/ressursen. Vi anbefaler en svært kort og beskrivende tekst, eller ingen tekst i det hele.
**Organisasjons ID-er:** |Her kan du legge inn en kommaseparert liste med organisasjons ID-er(9-sifret organisasjonsnummer) som vil få e-post dersom noen avbestiller denne ressursen. <em>For eksempel: 976245539, 994239929, 975674614</em>. NB! Disse organisasjonene må være registrert under "BOOKING=>ORGANISAJONER" for å få melding.

<style>
table, th, td {
    border: 1px solid black;
    border-collapse: collapse;

}
td {padding: 10px;}

</style>


Når du er ferdig, klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

> Ønsker du å knytte bilde eller filer til utleieobjektet/ressursen,  kan dette gjøres i det nye skjermbildet ved å klikke på *Legg til dokument*

På det nye skjermbildet vil det i bunnen ligge tre knapper med valgene: 
![knappevalg ressurser](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/Skjermbilderessurs.png)

Dersom du ønsker å redigere utleieobjektet/ressursen du har lagt til, klikker du på:
![rediger](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/rediger.png)

Ønsker du å se kalenderoversikten for utleieobjektet/ressursen, klikker du på:
![ressurskalender](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/ressurskalender.png)

Ønsker du å gå tilbake til hovedsiden for utleieobjekteene/ressurser, for å legge til enda en ny ressurs eller avslutte redigeringen av ressursen klikker du på:
![avbryt](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/avbryt.png)

## Aktiviteter
Et utleieobjekt(en ressurs) er alltid knyttet til en <em>aktivitet</em>. 

Aktiviteter er gjerne organisert hierarkisk med topp-nivåer som f.eks. «Idrett», «Kultur», "Skole" osv.
Hvert toppnivå kan ha en videre forgrening av underkategorier, f.eks. IDRETT/FOTBALL, og IDRETT/BASKETBALL. Dette er mest aktuelt om kommunen ønsker å ha statistikk på hvilke aktiviteter som ressursen brukes til.

Målgrupper og deltakerstatistikk er også i søknaden differensiert per toppnivå.

>Hensikten med å knytte et utleieobjekt (en ressurs) til en <em>aktivitet </em> er todelt:
1. Valg av aktivitet (toppnivå) bestemmer om det er fagavdelingen for IDRETT eller fagavdelingen for KULTUR som skal saksbehandle søknader som kommer inn på utleieobjektet/ressursen. Dette må altså avtales i forkant av opprettelsen av utleieobjektet/ressursen.
2. Dersom en kommune vil ha statistikk på hva utleieobjektet/ressursen brukes til, så vil man raskt kunne se om det er IDRETT eller KULTUR som bruker utleieobjektet/ressursen. En svakhet her er at det av og til er et idrettslag som benytter en "kulturressurs" (f.eks. et møterom i et kulturhus), eller omvendt; det kan komme et kulturarrangement i en "idrettsressurs" (idrettshall). Men er saksbehandler klar over feilkildene, så kan statistikken korrigeres og avvik forklares.

## Kalender
Kalenderen vises per uleieobjekt/ressurs, og kan vises i to nivåer:
1) Per utleieobjekt/ressurs
- Når en viser kalender for et utleieobjekt/en ressurs, vil det fremgå hva som er ledig tid.
2) Per ressursgruppe («Bygg/Anlegg»)
-  Kalenderen viser bare utleieobjekter/ressurser som er booket. 
-- Ledig tid vises for ressurser som også er «opptatt» innenfor tidsrammen i kalenderen.
-- Utleieobjekter/Ressurser som er helt ledig (ikke har bookinger ennå), vises ikke på dette nivået.(<em>Dette er en svakhet i systemet vi ønsker å rette på i kommende versjoner av systemet)</em>


Når man har opprettet aktuelle utleieobjekter/ressurser, så er neste steg å opprette [sesong og rammetid](http://manual.aktiv-kommune.no/?p=502) for å definere når utleieobjektene/ressursene er tilgjengelig for utleie/lån.