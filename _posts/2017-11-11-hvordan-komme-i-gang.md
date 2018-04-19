---
ID: 69
post_title: Hvordan komme i gang med Aktivkommune?
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=69
published: true
post_date: 2017-11-11 15:27:56
---
Prosesskart for nødvendige forberedelser før oppstart finner du <a href="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Aktivkommune-prosesskart-for-nødvendige-forberedelser-før-oppstart-PDF-1.pdf">her.</a>

<h2>Forberedelser</h2>
Før du kan bruke Aktivkommune, må kommunen ha opprettet en driftsavtale med Stavanger kommune. Du kan trykke <a href="#">her</a> for å fylle ut et skjema. Dette skjemaet sendes deretter til driftsansvarlig for godkjennelse. Når driftsavtalen er på plass vil systemansvarlig i din kommune motta en e-post med brukernavn og passord samt henvisning til denne siden.

<h2>Systemansvarlig</h2>
Hver kommune må ha en systemansvarlig eller sørge for at en person som er ansatt hos en samarbeidspartner/ekstern bedrift, blir tildelt denne rollen. En systemansvarlig, i denne sammenheng, er en person med generell god digital kompetanse, eller person som evner å forstå og utføre veiledningen under. En systemansvarlig vil ha tilgang til alle deler (kommandoer) i systemet.

<h2>Oppretting av ny instans i Aktivkommune</h2>
Etter at driftsavtale er inngått, vil driftsleverandør først opprette en egen <em>instans</em> ("systemkonto") for den nye kommunen /enheten. Som regel vil instansen ha samme navn som kommunen, men også kommunenummer og andre begreper kan benyttes som instansnavn. 
>En <em>instans</em> er avgrenset til :
<li>1. de brukere (systemadministrator, superbruker, saksbehandler og innbyggere/lag/organisasjoner) som skal bruke løsningen, </li>
 og til
<li>2. de utleie-ressurser(rom, anlegg, utstyr) som kommunen ønsker å leie ut. </li>

En instans er altså 100% dedikert til en konkret kommune, og det vil ikke være noen som helst kobling mellom de ulike instansene (kommunene); hverken på brukernivå eller for utleieressursene. Systemet vil rettnok takle kommunesammenslåinger, men dette temaet blir ikke gjennomgått i dette avsnittet.


<h2>Første gangs pålogging på Aktivkommune / Om oppretting av roller i Aktivkommune</h2>
Systemet leveres i utgangspunktet med tre predefinerte brukergrupper (default). Disse gruppene er:
1. Admins:           alle rettigheter
2. Booking admin:    reduserte admin-rettigheter
3. booking:          saksbehandler for booking (Aktiv…)

Disse tre brukergruppene bør skifte navn til noe mer forståelig, og forslag til nye gruppenavn er: 
fra (admins)            til      Systemadministrator 
fra (Booking admin)     til      Superbruker 
fra (booking)           til      Saksbehandler 

Hver kommune kan definere nye brukergrupper ut over disse tre, men dette frarådes fordi support og brukermanualer i utgangspunktet kun omfatter disse tre gruppene.

For større kommuner kan det være aktuelt å opprett Saksbehandlere som kun har tilgang til et begrenset antall utleieressurser (det vil si konkrete <em>Ressursgrupper</em> og <em>Ressurser</em>). Mer om dette i avsnittet "XXXXXXXX - kommer senere-  XXXXX " 

Systemet kommer med to default brukere:
1) Brukeren «sysadmin» er medlem av «Admins»
Legg inn ny «superbruker»  som skal være medlem av «booking admin». Denne brukeren brukes til videre konfigurasjon av systemet
2) Bookingguest. Definerer tilganger for frontendbruker. Tilgang gis «automagisk».




Dernest vil systemansvarlig i kommunen/enheten via e-post få tilsendt brukernavn (til rollen systemadministrator) og via SMS et passord . Hver kommune vil også få en eller flere <em>superbrukere</em> tildelt (med egen ident og passord). 
><li>En systemansvarlig vil normalt få tildelt rollen <em>systemadministrator</em>, og ha tilgang til alt mulig av menyvalg/kommandoer i systemet.  </li> <

><li>En <em>superbruker</em> vil kunne gjøre det meste i systemet, men antall menyvalg/kommandoer er "skrellet" ned til et minimum. </li> <


<h2>Support/backup på roller/tilganger. </h2>
Driftsleverandør vil ha egen pålogging til kommunens instans. Skulle for eksempel systemansvarlig miste passordet sitt, så vil driftsleverandør kunne bistå med nytt passord. I en oppstartsfase vil kommunen trolig ha behov for at driftsleverandør kan gå inn og kontrollere, eventuelt gi råd om oppsett og konfigurasjon av systemet. Før dette skjer, vil driftsleverandør avtale med systemansvarlig hvordan dette best kan foregå.

<h2>Oppsett av nettside; bilder,logo og framsidetekst</h2>
Disse endringene gjøres under: 
<strong>ADMINISTRASJON => ADMIN => GLOBAL KONFIGURASJON</strong>
<ul>

<li>Angi tittel for nettstedet:
På det nye skjermbildet finner du <em>Utseende</em>, og deretter kan du skrive inn ønsket navn under <em>Angi tittel for nettstedet</em>. Dette navnet trenger ikke ha noen sammenheng med instansnavnet som er nevnt over, men kan gjerne være det samme.</p></li>

<li>Angi url for logo (hvor ligger (kommune)logoen): 
eksempel: Fjell kommune henter sin logo fra: https://no.wikipedia.org/wiki/Sund_(Hordaland)#/media/File:Sund_komm.svg
Se <a href="https://no.wikipedia.org/wiki/Wikipedia:V%C3%A5pengalleri/Kommunev%C3%A5pen">Wikipedia</a></p></li>

<li><p>E-post brukerstøtte:
eksempel: informasjon@fjell.kommune.no</p></li>

<li><p>For å skrive inn tekst som skal være på forsiden / startsiden velger du:
<strong>ADMINISTRASJON => BOOKINGFRONTEND => METADATA</strong>
og skriver inn aktuell tekst i feltene "Tekst over framsidebilde" og "Framsidetekst"</p></li>
</ul>

<p>Når du er ferdig å fylle ut, klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/lagre3.png" alt="lagre" />
Neste trinn er å legge inn <a href="https://manual.aktiv-kommune.no/?p=267">brukere og brukergrupper</a>.