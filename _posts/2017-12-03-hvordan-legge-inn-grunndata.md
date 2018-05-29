---
ID: 265
post_title: >
  Hvordan legge til ny eller endre
  aktivitet?
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=265
published: true
post_date: 2017-12-03 10:25:00
---
I Aktivkommune er begrepet <em>aktivitet </em> knyttet til hva utleieobjektet (ressursen) brukes til. Vanligvis er følgende fire toppnivåer brukt i utleiesammenheng:
* Idrett
* Kultur
* Skole
* Byrom/friluftsliv

Noen bruksområder for "aktivitet" i systemet er disse:
I frontend (publikumsdelen) av systemet er det mulig å sortere ressursgrupper (og dermed utleieobjekter) etter hvilken aktivitet de naturlig hører inn under. Velger du "idrett", så vises bare utleieobjekter som "Idrett" disponerer/hører til "Idrett".

I backend (saksbehandlingsdelen) er det den aktiviteten som blir knyttet til ressursgruppen (bygget/anlegget) (se <a href="http://manual.aktiv-kommune.no/?p=166">"Hvordan legge til ny ressursgruppe"</a>) som avgjør hvilken fagavdeling i kommunen som skal <em>behandle </em> søknaden. Blir en ressursgruppe (og et utleieobjekt) knyttet til aktiviteten "skole", så er det skoleavdelingen eller representanter for skoleavdelingen som behandler og avgjør søknadene som kommer inn på det aktuelle utleieobjektet.

"Aktivitet" benyttes flere steder i systemet:
 * du registrerer hvilken aktivitet som en ressursgruppe (et bygg/anlegg) tilhører (backend), og 
 * i søknadsskjemaet må søker avgjøre hvilken hovedaktivitet som bookingen mest naturlig hører inn under.

>Det må opprettes minimum en aktivitet i systemet. Vi anbefaler at det opprettes aktiviteter som har samme navn eller som kan representere de fire toppnivåene som er nevnt over.

En aktivitet opprettes (og endres) ved bruk av kommandoen

<strong>BOOKING => INNSTILLINGER => AKTIVITETER</strong>

Skjermbildet som kommer opp ser slik ut: 

![skjermbilde aktivitet](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/skjermbildeaktivitet-300x251.png)

Her kan man endre informasjon om de eksisterende aktivitetene ved å klikke på mappene,  og trykke "lagre" når ønsket endring er utført. 

Finner man ikke en egnet aktivitet eller ønsker å opprette en ny aktivitet, så gjøres dette ved å klikke på 
![verktoy](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/verktoy.png)
Deretter velger du 
![ny aktivitet](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/nyaktivitet.png)

### Fyll ut informasjon om aktiviteten:

Feltnavn|  Aksjon / Forklaring
----------------------|-----------------------------------------------------------------
**Aktiviteter:** |Navn på aktivitet/ Hvilken aktivitet det er.
**Beskrivelse:** |Beskrivelse av aktiviteten.
**Overordnet kategori:** |Hvis aktiviteten din er en underkategori av en annen aktivitet så kan du her knytte aktiviteten opp mot hovedaktiviteten. Eksempel: Aktiviteten "Teater" kan være en aktivitet som er underordnet  toppnivået "kultur", og "Fotball" er en underaktivitet knyttet til toppnivået "Idrett".

Når alt er fylt ut så legger du til aktiviteten ved å klikke på 
![legg til](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/leggtil.png)

Hvordan man ønsker å opprette aktiviteter, er opp til hver enkelt kommune. Det er uansett viktig å ha i tankene at oppsettet av aktiviteter kan påvirke ulike funksjoner i systemet (eksempelvis filtrering i frontend), og hvis du ønsker å vike fra oppsettet som er i systemet, ta gjerne en sjekk med driftsleverandør (Stavanger kommune). En aktivitet som er opprettet kan ikke slettes, men settes som inaktiv i systemet. Dette gjøres for at systemet ikke skal miste historikk.