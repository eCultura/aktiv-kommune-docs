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


<h2>Om brukergrupper og roller i Aktivkommune</h2>
Systemet leveres i utgangspunktet med tre predefinerte brukergrupper (default). Disse gruppene er:
1. Admins:           alle rettigheter
2. Booking admin:    reduserte admin-rettigheter
3. booking:          saksbehandler for booking (Aktiv…)

Disse tre brukergruppene bør omgående skifte navn til noe mer forståelig, og forslag til nye gruppenavn er: 
fra (admins)            til      Systemadministrator 
fra (Booking admin)     til      Superbruker 
fra (booking)           til      Saksbehandler 

Det er i skrivende stund ikke besluttet om dette navneskiftet skal gjøres i forkant av leveransen, eller om den nye kommunen selv skal gjøre dette.

Hver kommune kan definere nye brukergrupper ut over disse tre, men dette frarådes fordi support og brukermanualer i utgangspunktet kun omfatter disse tre gruppene.

For større kommuner kan det være aktuelt å opprette Saksbehandlere som kun har tilgang til et begrenset antall utleieressurser (det vil si konkrete <em>Ressursgrupper</em> og <em>Ressurser</em>). Mer om dette i avsnittet "XXXXXXXX - kommer senere-  XXXXX " 

Systemet blir levert med to default brukere:
1) Brukeren «sysadmin», som er medlem av «Admins»/ (Systemadministrator). Denne brukeren har tilgang til alt i systemet (både menyvalg og kommandoer). Systemadministrator blir bare brukt når kommunen skal opprette ny superbruker.
2) Bookingguest. Denne brukeren definerer tilganger for innbygger/bruker (bookingfrontend-bruker). Tilgang gis «automatisk» når innbygger/bruker åpner et søknadskjema i bookingsystemet (bruker blir et anonymt medlem ("gjestebruker") av modulen bookingfrontend).

<h2>Hva skal gjøres ved første gangs bruk/pålogging i Aktivkommune</h2>

Etter at instans er opprettet (se over), vil driftsleverandør (Stavanger kommune) sende e-post til systemansvarlig i kommunen/enheten.
I denne e-posten vi kommunen motta brukernavn (systemadministrator) og passord til systemadministrator. Hver kommune vil også få en eller flere <em>superbrukere</em> tildelt med eget brukernavn(ident) og passord. Navn og passord bli delt ut på samme måte som for Systemadministrator (se over). NB STAVANGER MÅ LEGGE DETTE INN I "OPPSTARTS"-RUTINEN! ELLERS MÅ DETTE GJØRES AV KOMMUNENS SYSTEMADMINISTRATOR.

(0. Logg på som Systemadministrator) STAVANGER?
1. Klikk på "Ny bruker", og legg inn nødvendige opplysninger (se avsnitt under). Denne brukeren må krysses av og bli medlem av «booking admin» (gruppen "Superbruker"). 
LAG EGET SKJERMBILDE

(2. Logg av som  Systemadministrator) STAVANGER?
3. Du som er tildelt rollen som superbruker (konkret person), tar konfigureringen av systemet videre.
Denne brukeren brukes til videre konfigurasjon av systemet


><li>Instansen trenger normalt bare en <em>systemadministrator</em>, og denne brukeren vil ha tilgang til alle menyvalg/kommandoer i systemet.  </li> <

Det aller viktigeste av konfigurering av bookingsystemet skjer via en person som har fått tildelt rolle som superbruker. En instans bør ha flere enn en superbruker, men dette er ikke et absolutt krav.

><li>En <em>superbruker</em> vil kunne gjøre det meste i systemet, men antall menyvalg/kommandoer er "skrellet" ned til et minimum. </li> <


<h2>Support/backup på roller/tilganger. </h2>
Driftsleverandør vil ha egen pålogging til kommunens instans. Skulle for eksempel systemansvarlig miste passordet sitt, så vil driftsleverandør kunne bistå med nytt passord. I en oppstartsfase vil kommunen trolig ha noe behov for at driftsleverandør kan gå inn og kontrollere, eventuelt gi råd om oppsett og konfigurasjon av systemet. Før dette skjer, vil driftsleverandør avtale med systemansvarlig hvordan dette best kan foregå.

<h2>Oppsett av nettside (frontend); Om framsidebilder, logo og framsidetekst</h2>
Kommunene må selv legge inn logo (kommunelogo), framsidebilde (om ønskelig) og tekst (både tekst som legger seg over framsidebilde og egen tekst. Følgende steg må derfor gjennomføres før oppstart:

Velg først kommandoen: 
<strong>ADMINISTRASJON => ADMIN => GLOBAL KONFIGURASJON</strong>
<ul>

<li>Angi tittel for nettstedet:
På det nye skjermbildet finner du <em>Utseende</em>, og deretter kan du skrive inn ønsket navn under <em>Angi tittel for nettstedet</em>. Dette navnet trenger ikke ha noen sammenheng med instansnavnet som er nevnt over, men kan gjerne være det samme.</p></li>

<li>Angi url for logo (hvor ligger (kommune)logoen): 
eksempel: Fjell kommune henter sin logo fra: https://no.wikipedia.org/wiki/Sund_(Hordaland)#/media/File:Sund_komm.svg
Se <a href="https://no.wikipedia.org/wiki/Wikipedia:V%C3%A5pengalleri/Kommunev%C3%A5pen">Wikipedia</a></p></li>

<li><p>E-post brukerstøtte:
Her legger man inn epostkontoen for brukerstøtte. NB! Det må etableres en rutine for å sjekke og lese eventuelle e-poster.
eksempel på e-postadresse (for Fjell kommune): informasjon@fjell.kommune.no</p></li>

<li><p>For å skrive inn tekst som skal være på forsiden / startsiden velger du:
<strong>ADMINISTRASJON => BOOKINGFRONTEND => METADATA</strong>
og skriver inn aktuell tekst i feltene "Tekst over framsidebilde" og "Framsidetekst"</p></li>
</ul>

<p>Når du er ferdig å fylle ut, klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/lagre3.png" alt="lagre" />
Neste trinn er å legge inn <a href="https://manual.aktiv-kommune.no/?p=267">brukere og brukergrupper</a>.