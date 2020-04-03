Conclusies en aanbevelingen
---------------------------

In dit hoofdstuk worden de belangrijkste conclusies uit de voorgaande
hoofdstukken uitgelicht, en wordt een aantal aanbevelingen gedaan voor een
eventueel vervolgproject.

(\@\@\@ todo: Aan de hand van hoofdstuk analyse en informatiemodel) bevindingen
nalopen en omzetten in conclusies en aanbevelingen.)

### Conclusies

#### Er is al veel data beschikbaar

Uit de voorgaande hoofdstukken blijkt dat er al heel veel data beschikbaar is.
Deze data is en wordt verzameld vanuit verschillende invalshoeken. Zo wordt door
de installatiebranche data verzameld die alles te maken heeft met het beheer en
onderhoud van installaties bij klanten. En wordt vanuit andere organisaties weer
met een heel andere bril naar de data gekeken. Er is data over de installaties
zelf, maar ook data die meetwaarden bevat

#### Er zijn veel verschillende partijen betrokken

Uit het hoofdstuk Landschapsverkenning blijkt dat er veel verschillende partijen
betrokken zijn bij het verzamelen en gebruiken van data en informatie van de
installaties. Sommige partijen hebben de data nodig voor hun dagelijkse werk, en
andere partijen gebruiken de ingewonnen data van andere partijen voor het
afleiden van statistieken en trends.

#### Er zit overlap in de datamodellen

Kijkend naar de datamodellen ontstaat eenzelfde beeld. De datamodellen zijn
gemaakt voor het doel dat zij dienen. Ook is er een overlap te zien, wat heel
logisch is omdat dezelfde objecten (installaties, meetwaarden, leeftijden,
fysieke kenmerken) in beschouwing worden genomen. Ook wil eenzelfde naam voor
iets niet zeggen dat er ook hetzelfde mee bedoeld wordt.

#### Er zit verschil in de datamodellen

Ook zit er verschil in de datamodellen, en in de data en informatie. Zo zijn
vastleggingsmodellen anders dan de informatiemodellen. Ergens tussen data en
informatie vindt een bewerking of berekening plaats om betekenis te geven aan de
data.

#### Welke informatievraag is er eigenlijk?

Belangrijk is het om te werken vanuit een informatievraag waar use-cases onder
liggen. Bij een andere aanpak ontstaat het gevaar dat er aanbod-gedreven gewerkt
gaat worden, waarbij het niet duidelijk is of de vraag naar het aanbod er
eigenlijk wel is. In het speelveld "energietransitie" leven verschillende
informatievragen bij verschillende organisaties. Zo zijn netbeheerders
geïnteresseerd in de (geplande) capaciteitsvraag voor hun netwerken, om daarop
te anticiperen. Installateurs zijn waarschijnlijk geïnteresseerd in de
vervangingsvraag voor installaties bij klanten, zodat zij daarop kunnen
inspelen. Overheidsorganisaties zullen vooral willen weten of zij aan de CO2
doelstellingen voldoen.

### Aanbevelingen

### Voorstel voor doorontwikkeling informatiemodel energie-installaties

\@\@\@ (Jan todo: Voorstel uitwerken conform werkplan VIII VIVET 2020) a) Een
voorstel hoe een breed gedragen informatiemodel voor energie-installaties tot
stand kan komen om de huidige en toekomstige informatie-uitwisseling te
faciliteren voor versnelling van de energietransitie.

#### Warmte

De warmtesector is in sterke mate gefragmenteerd. Informatiesystemen zijn binnen
organisaties ontwikkeld zonder afstemming met andere partijen in de sector. Een
generiek informatiemodel voor warmtenetwerken bestaat dan ook niet, zoals ook
geconstateerd in VIVET Project A1, waar de gebiedsgerichte ontsluiting van
warmtenetten is onderzocht. De conclusie is ook daar, dat de sector zeer
terughoudend is waar het gaat om het delen van informatie; oorzaken zijn
complexiteit van de materie, commerciële belangen en juridische bezwaren.

De locaties van warmtenetten worden overigens wel toegankelijk gemaakt via KLIC.

Geharmoniseerde data van de warmtesector komt bijeen in de rapportages aan ACM.
Warmtebedrijven rapporteren aan ACM zodat deze het reguleringsregime kan
handhaven en ontwikkelen. Dit is uitgewerkt in bijv. het
[Warmtebesluit](https://wetten.overheid.nl/BWBR0033940/2020-01-01), waarin
gespecificeerd is over welke temperatuur- en aansluitcategorieën de
warmtebedrijven moeten rapporteren. Ook in het [Tarievenbesluit
Warmte](https://www.acm.nl/sites/default/files/documents/2019-12/tarievenbesluit-warmteleveranciers-2020.pdf)
is veel te vinden over de informatie-uitvraag door ACM.  
De in deze rapportages gespecificeerde classificaties kunnen dienen bij de
informatiemodellering van warmte-installaties. Ook dit is overigens een
dynamisch veld, omdat de regulering van het warmtesysteem de komende jaren zich
nog sterk zal ontwikkelen.

Nu de verduurzaming van de gebouwde omgeving wordt aangepakt, komen er nieuwe
samenwerkingsverbanden, bijv. in kader van MMIP-programma van de TKI Energie:
WarmingUP (MMIP4 collectieve warmte) en IETBB (MMIP3 en MMIP4 gebouw-gebonden
warmte). Hierbij zijn vele partijen betrokken uit de hele warmteketen en dat
geeft nieuwe mogelijkheden om met de warmtesector te werken aan inzicht in de
desbetreffende informatievoorziening.

#### Energy Data Repository

Informatiemodellen bevatten verwijzingen naar in het universum geaccepteerde
definities, classificaties e.d. die vastgelegd zijn in thesauri of repositories.
De taal ESDL is verbonden met een z.g. Energy Data Repository, die nu nog
slechts verwijzingen bevat naar SBI-codes (CBS) en Energiedragers (RVO).
Uitbreiding daarvan draagt bij aan dataharmonisering, en de geïnventariseerde
classificaties in dit onderzoek zoude daarvoor in aanmerking kunnem komen.  
Voor het warmtedomein kan hier gedacht worden aan definities voor verschillende
typen biomassa en biofuels-installaties. Experts van CBS, NVWA, SDE-registratie
en het Team Biomassa van RVO kunnen hiertoe kennis inbrengen, bij voorkeur
gerelateerd aan internationale geaccepteerde normen.

Het is belangrijk om hier de juiste governance voor te ontwikkelen, zodat
repositories ook de noodzakelijke statuur krijgen.

#### EFI Energy Flexibility Interface

FAN (Flexible Power Alliance Network) heeft EFI ontwikkeld, de Energy
Flexibility Interface. EFI is een communicatieprotocol dat het mogelijk maakt
voor een eindgebruiker om diverse slimme apparatuur te besturen, zoals
wasmachines, airco, zonnepanelen, opladen van de auto en daarmee flexibele
energie te ontsluiten. In dit protocol zijn ook diverse typen
energie-installaties gedefinieerd. De specificatie van EFI is beschikbaar op
[Github](https://github.com/flexiblepower/efi).

#### Internationaal perspectief

Op dit moment wordt uiteraard ook internationaal gewerkt aan
informatiestandaarden in het energiedomein en open source-ontwikkelingen. EDSN
vertegenwoordigt bijvoorbeeld Nederland in internationale gremia (zoals
[ebIX](http://www.ebix.org)) die zich richten op harmonisering van
berichtenverkeer en informatievoorziening voor facilitering van de energiemarkt.
De inbreng van internationale standaarden kan zorgen voor een meer toekomstvaste
informatievoorziening, en moet bij het vervolgproject in acht worden genomen.
Andersom kunnen ontwikkelingen in NL (te denken is dan aan ESDL) ook
internationaal ingebracht worden. Expertise van RVO/ECW, zowel inhoudelijk als
kennis van ontwikkelingen bij de EU kan hier ingezet worden.

#### Illstratie: Invoering begrip Standaardjaarafname (SJA) en Standaardjaarinvoeding (SJI)

Het standaardjaarverbruik (SJV) is een kernvariabele in energiedata. Kort gezegd
is het het voor temperatuureffecten gecorrigeerd verbruik van gas door een
afnemer. Het wordt ook gebruikt voor elektriciteit. Het SJV wordt gebruikt in
verschillende processen in het energiesysteem.

In verband met sterk toenemende situaties waarin invoeding in het net
plaatsvindt, is besloten om het SJV om te dopen in Standaardjaarafname (SJA) en
daarnaast het concept Standaardjaarinvoering in te voeren. E.e.a. is uitgebreid
beschreven in de brief van ACM ‘Codewijzigingsvoorstel tot invoering van
standaardjaarinvoeding en-afname’.

Waarom is dit interessant? Omdat de codes (Netcode, Informatiecode, etc.)
centraal staan in de praktische uitwerking van de regelgeving in het
energiedomein. Nieuwe datadefinities en wijzigingen van bestaande datadefinities
beginnen vaak hier, en daarom is dat dé plek om te zorgen dat metadata goed
wordt geformuleerd zodat deze hanteerbaar is voor informatiestandaarden en
-modellering.

#### Factsheets

Een interessante bron van informatie zijn z.g. factsheets over
installatie-installaties die verschillende organisaties opstellen. Factsheets
beschrijven de eigenschappen van energie-installaties en zijn bijv. te vinden
bij

-   TNO op de site [Energy.nl](https://energy.nl)

-   CE Delft: [Warmtetechnieken ](https://www.ce.nl/warmtetechnieken)

-   Expertise Centrum Warmte:
    [Kennis](https://expertisecentrumwarmte.nl/kennis/factsheets)
