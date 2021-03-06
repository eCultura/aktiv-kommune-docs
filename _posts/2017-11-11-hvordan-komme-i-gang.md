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
Før du kan bruke Aktivkommune, må kommunen ha opprettet en driftsavtale med Stavanger kommune. Du kan trykke <a href="#">her</a> for å fylle ut et skjema. Dette skjemaet sendes deretter til driftsansvarlig for godkjennelse. Når driftsavtalen er på plass vil systemansvarlig (en superbruker) i din kommune motta en e-post med brukernavn og en SMS med passord, samt henvisning til denne siden.

<h2>Systemansvarlig</h2>
Hver kommune må ha en systemansvarlig eller sørge for at en person som er ansatt hos en samarbeidspartner/ekstern bedrift, blir tildelt denne rollen. En systemansvarlig, i denne sammenheng, er en person med generell god digital kompetanse, eller person som evner å forstå og utføre veiledningen under. En systemansvarlig vil ha tilgang til alle deler (kommandoer) i systemet.

<h2>Oppretting av ny instans i Aktivkommune</h2>
Etter at driftsavtale er inngått, vil driftsleverandør først opprette en egen <em>instans</em> ("systemkonto") for den nye kommunen /enheten. Som regel vil instansen ha samme navn som kommunen, men også kommunenummer og andre begreper kan benyttes som instansnavn.

<blockquote>En <em>instans</em> er avgrenset til :
<ul>
 	<li>1. de brukere (systemadministrator, superbruker, saksbehandler og innbyggere/lag/organisasjoner) som skal bruke løsningen i din kommune,</li>
</ul>
og til
<ul>
 	<li>2. de utleieobjekter (ressurser; rom, anlegg, utstyr) som din kommune ønsker å leie ut.</li>
</ul>
En instans er altså helt avgrenset til en konkret kommune, og det vil ikke være noen som helst kobling mellom de ulike instansene (kommunene); hverken på brukernivå eller for utleieressursene. Systemet vil rettnok takle kommunesammenslåinger, men dette temaet blir ikke gjennomgått i dette avsnittet.

Instansen inneholder alle moduler i FDV-systemet (Portico Estate), men for å etablere og bruke Aktivkommune brukes kun følgende fire moduler:

* Booking (full bruk)
* Bookingfrontend (full bruk)
* Administrasjon (delvis bruk)
* Eiendom (delvis bruk)

Denne manualen konsentrerer seg kun om de moduler og funksjoner som til sammen utgjør Aktivkommune</blockquote>

<h2>Om brukergrupper og roller i Aktivkommune</h2>
Systemet leveres i utgangspunktet med tre predefinerte brukergrupper (default). Disse gruppene er:

1. Admins: alle rettigheter
2. Booking admin: reduserte admin-rettigheter
3. booking: saksbehandler for booking (Aktivkommune)

Disse tre brukergruppene bør omgående skifte navn til noe mer forståelig, og forslag til nye gruppenavn er:

* fra (admins) til Systemadministrator
* fra (Booking admin) til Superbruker
* fra (booking) til Saksbehandler

&gt;Det er i skrivende stund ikke besluttet om dette navneskiftet på brukergruppene skal gjøres i forkant av leveransen, eller om den nye kommunen selv skal gjøre dette.

Hver kommune kan definere nye brukergrupper ut over disse tre, men dette frarådes fordi support og brukermanualer i utgangspunktet kun omfatter disse tre gruppene.

For større kommuner kan det være aktuelt å opprette Saksbehandlere som kun har tilgang til et begrenset antall utleieressurser (det vil si konkrete <em>Ressursgrupper</em> og <em>Utleieobjekter (ressurser) </em>). Mer om dette i avsnittet <a href="http://manual.aktiv-kommune.no/?p=166">Hvordan legge til ny ressursgruppe(nytt bygg eller anlegg)</a>" og <a href="http://manual.aktiv-kommune.no/?p=522">Hvordan legge til nytt utleieobjekt (ny ressurs)?</a>

Systemet blir levert med to default brukere:

1. Brukeren «sysadmin». Denne brukeren er medlem av brukergruppen «Admins»/ (Systemadministrator), og den har tilgang til alt i systemet (både menyvalg og kommandoer). Systemadministrator blir bare brukt når kommunen skal opprette ny superbruker.
2. Brukeren "Bookingguest". Denne brukeren definerer tilganger for innbygger/bruker (bookingfrontend-bruker). Tilgang gis «automatisk» når innbygger/bruker åpner et søknadskjema i bookingsystemet (bruker blir en anonym bruker ("gjestebruker") av modulen bookingfrontend).

<h2>Hva skal gjøres ved første gangs bruk/pålogging i Aktivkommune</h2>
Etter at instans er opprettet (se over), vil driftsleverandør (Stavanger kommune) sende e-post til systemansvarlig i kommunen/enheten. I denne e-posten vi kommunen motta brukernavn (systemadministrator). Passord til systemadministrator blir sendt i en egen SMS. Hver kommune vil også få en eller flere <em>superbrukere</em> tildelt med eget brukernavn(ident) og passord. Navn og passord bli delt ut på samme måte som for Systemadministrator (se over).

<strong> NB STAVANGER MÅ LEGGE DETTE INN I "OPPSTARTS"-RUTINEN! ELLERS MÅ DETTE GJØRES AV KOMMUNENS SYSTEMADMINISTRATOR.</strong>

(0. Logg på som Systemadministrator) Utføres av STAVANGER?
For å legge til ny bruker i systemet, må følgende steg gjennomføres:

1. Velg kommandoen:
<strong>ADMINISTRASJON => ADMIN => ADMINISTRER BRUKERE</strong>

Følgende skjermbilde dukker opp:
![Opprette ny bruker](http://manual.aktiv-kommune.no/wp-content/uploads/2018/05/Opprette ny bruker.png)


2. Klikk på "Legg til"-knappen

3. Skriv inn nødvendige opplysninger i arkfanen "Brukerdata", se avsnittet 
 <a href="http://manual.aktiv-kommune.no/?p=267">"Administrer brukere"</a>

4. Velg arkfanen "Grupper", og sett et kryss for valget : 
    <strong>Gruppe, superbruker</strong>


Den nye brukeren har dermed blitt medlem av gruppen "Superbruker" , default «booking admin», og vil ha nødvendige tilganger til å gjøre det meste i Aktivkommune.

(2. Logg av som Systemadministrator) Utføres av STAVANGER?
3. Du som er tildelt rollen som superbruker (konkret person), tar konfigureringen av systemet videre.
Du må være pålogget med "Superbruker"-rettigheter for å kunne gjøre resten av konfigureringene av Aktivkommune/systemet.


<ul>
 	<li>Instansen trenger normalt bare en <em>systemadministrator</em>, og denne brukeren vil ha tilgang til alle menyvalg/kommandoer i systemet. Systemadministrator vil ha tilgang til kommandoer som både vedrører FDV-delen og booking-delen av systemet Portico Estate</li>
</ul>
De aller viktigste konfigureringer av bookingsystemet gjøres av en person som har tilgang som superbruker. En instans bør ha flere enn en superbruker, men dette er ikke et absolutt krav.


> En <em>superbruker</em> vil kunne gjøre det meste i systemet, men antall menyvalg/kommandoer er "skrellet" ned til et minimum, det vil i praksis være alle kommandoer i booking-delen og noen av kommandoene i eiendoms-delen av Portico Estate.


<h2>Support/backup på roller/tilganger.</h2>
Driftsleverandør vil ha egen pålogging til kommunens instans. Skulle for eksempel systemansvarlig miste passordet sitt, så vil driftsleverandør kunne bistå med nytt passord. I en oppstartsfase vil kommunen trolig ha noe behov for at driftsleverandør kan gå inn og kontrollere, eventuelt gi råd om oppsett og konfigurasjon av systemet. Før dette skjer, vil driftsleverandør avtale med systemansvarlig hvordan dette best kan foregå.

<h2>Oppsett av nettside (frontend); Om framsidebilder, logo og framsidetekst</h2>
Kommunene må selv legge inn logo (kommunelogo), framsidebilde og tekst/informasjon. Det er ikke etablert en beste praksis her, så tipset er å se hva andre kommuner har gjort for å få dette til.

<strong>Her er det mulig å legge inn LENKER - som eksempel på forsider?</strong>

Følgende steg må gjennomføres før oppstart:

Velg først kommandoen:
<strong>ADMINISTRASJON =&gt; ADMIN =&gt; GLOBAL KONFIGURASJON</strong>

(NB! De felt som ikke blir omtalt her trenger ikke å bli fylt ut)

Forklaring for noen av feltnavnene som må fylles ut kommer her:

Feltnavn| Aksjoner/ Forklaringer
---------------------------------|----------------------------------------------------
<strong>Angi tittel for nettstedet:</strong> | På det nye skjermbildet finner du Utseende; Skriv inn ønsket navn under "Tittel for nettstedet." Dette navnet trenger ikke ha noen sammenheng med instansnavnet som er nevnt over, men kan gjerne være det samme.
<strong>Angi url for logo:</strong>| Oppgi adressen til det stedet der (kommune)-logoen er plassert. Eksempel: Fjell kommune heter sin logo fra følgende url: https://no.wikipedia.org/wiki/Sund_(Hordaland)#/media/File:Sund_komm.svg
<strong>E-post brukerstøtte:</strong>| Her legger du inn e-posten til brukerstøtte lokalt i din kommune.  

>NB! Det må etableres en rutine i din kommune slik at brukerstøtte-e-posten jevnlig blir sjekket og lest. 



For å skrive inn tekst som skal være på forsiden / startsiden velger du kommandoen:

<strong>ADMINISTRASJON =&gt; BOOKINGFRONTEND =&gt; METADATA</strong>
og skriver inn aktuell tekst i feltene "Tekst over framsidebilde" og "Framsidetekst"


Når du er ferdig å fylle ut, klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/lagre3.png" alt="lagre" />

## Opprette eier-kategorier.
Før oppstart må det legges til minimum en kategori for eierforholdet; Dette gjøres ved å bruke kommandoen:

<strong>ADMINISTRASJON => EIENDOM => EIER => (Eier kategorier).</strong>

Velg "Ny" , og legg inn minimum en eierkategori.

> Vanligvis er det nok å legge inn "offentlig" eller "kommunal" eiet, men i den grad kommunen har disposisjonsrett og skal drive utleie på private bygg og anlegg, så må også motsatt kategori legges inn, for eksempel "ikke-kommunal" eiet eiendom/bygg også legges inn.

Neste trinn er å legge inn <a href="https://manual.aktiv-kommune.no/?p=267">brukere og brukergrupper</a>.