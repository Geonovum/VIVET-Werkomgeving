## Inleiding

### Context 

Het programma
[VIVET](https://www.geonovum.nl/uploads/documents/Rapport%20VIVET%20Definitief-1.0.pdf)
(Verbetering Informatie Voorziening EnergieTransitie) bevat voorstellen voor de
verbetering van de informatievoorziening van de energietransitie. Het programma
is opgesteld door het CBS, het Kadaster, PBL, RVO.nl en Rijkswaterstaat op
verzoek van de ministeries van Economische Zaken en Klimaat en Binnenlandse
Zaken en Koninkrijksrelaties. In het werkplan VIVET t/m maart 2020 is een
vijftal activiteiten voorzien. Eén van die activiteiten is een verkenning van
een centraal register van energie-installaties, met als deelstudie een
Voorstudie voor een centraal installatieregister. Op dit moment ontbreekt het
veel betrokken partijen aan informatie over installaties die energie kunnen opwekken,
converteren of opslaan. De informatie is deels niet beschikbaar, deels niet
vindbaar, deels niet ontsloten, en deels niet koppelbaar. Dat betekent dat
optimale besluitvorming voor de regionale energiestrategieën (RES) en
transitievisie warmte (TVW), systeemintegratie en de hoofdinfrastructuur energie
niet goed mogelijk is. Uit de voorstudie moet blijken op welke manier de reeds
bestaande informatie over energie-installaties naar relevante stakeholders
(besluitvormers, dataspecialisten e.d.) in de energietransitie ontsloten kan
worden.
Voor uitgebreidere toelichting van deze contex en VIVET zie [Bijlage 9](#bijlage-9).

### Verkenning Informatiemodel energie-installaties

#### Doel en resultaat

RVO wil via deze voorstudie zicht krijgen op welke manier de reeds bestaande
informatie over energie-installaties naar relevante stakeholders
(besluitvormers, dataspecialisten e.d.) in de energietransitie ontsloten kan
worden. Daartoe zal Geonovum de volgende resultaten opleveren.

1.  Een voorstel hoe een breed gedragen informatiemodel voor
    energie-installaties tot stand kan komen om de huidige en toekomstige
    informatie-uitwisseling te faciliteren voor versnelling van de
    energietransitie.

2.  Draagvlak bij de belangrijkste stakeholders om tot een gemeenschappelijk
    informatiemodel te komen.

3.  Eerste versie van een informatiemodel, waarmee een Proof Of Concept (POC)
    kan worden gevoerd. De scope hiervan beperkt zich tot de door VIVET
    aangedragen usecases, maar met de potentie om dat uit te bouwen tot een
    breder model binnen het energiedomein, onder andere voor installaties,
    gebouwen, energienetwerken.

In de gesprekken over de opdracht is een aantal organisaties genoemd die worden
betrokken bij de voorstudie: TNO, RVO, Netbeheer Nederland, EDSN, Expertgroep
EnergieTransitieRekenmodellen (EG ETRM), Techniek Nederland en partners binnen VIVET. Voorts wordt
voorgesteld om voort te bouwen op bestaande informatiemodellen en systemen voor
installaties, zoals ESDL, Cerise, CERES, PIR, INSPIRE, en de Basisregistraties.
zie voor de lijst met deelnemers [Bijlage 8](#bijlage-8)

#### Aanpak

Als aanpak is gekozen voor de volgende werkwijze: deskresearch van bestaande modellen, overleg met
kennisdragers en stakeholders, en het realiseren van een concept informatiemodel
voor een PoC-energie-installaties.  

Hieronder het stappenplan:

1.  Voorgesprekken en kick-off meeting met opdrachtgever en stakeholders

-   Verder concretiseren van context en scope.

-   Realiseren van betrokkenheid van partijen bij dit onderzoek.

2.  Deskresearch om bestaande modellen te bestuderen

-   Eerste inventarisatie van de uitgangspunten en onderdelen van een
    informatiemodel door bestuderen van bestaande modellen en systemen.

3.  Expertsessies

-   Organiseren en faciliteren van enkele werksessies met actieve stakeholders
    om de uitgangspunten van het informatiemodel scherper te krijgen.

4.  Realisatie concept informatiemodel gericht op usecases voor POC

-   De eerste versie van het informatiemodel bevat een conceptuele beschrijving
    van informatiebehoeften in de keten van gegevensuitwisseling.

-   De beschrijving is geschikt voor verder gebruik in VIVET-usecases voor de
    POC.

5.  Consultatie stakeholders

-   Communiceren van resultaten van het onderzoek en ophalen commentaar.

6.  Schrijven eindrapportage

-   Voorstel en aanbevelingen hoe te komen tot een breed gedragen
    informatiemodel waarmee informatie voor energie-installaties kan worden
    verzameld, beheerd en uitgewisseld.

<div class="note">
    Deze versie is het resultaat van de stappen 1 t/m 4. De consultatie zal in digitale vorm gebeuren, daarna volgt het definitieve eindrapport 
</div>

Doelgroep
---------

Dit document is primair bestemd voor de opdrachtgever, de Stuurgroep VIVET.
Daarnaast is het gericht op beheerders van huidige registraties, stakeholders
uit energiedomein en beleidswereld, en kennisdragers op het gebied van
informatievoorziening.

Leeswijzer
----------

Na deze inleiding bevat dit rapport achtereenvolgens een beschrijving van het
landschap met registraties van energie-installaties, zowel qua datasets als
gehanteerde informatietooling (informatiemodellen, classificaties e.d.).

Deze beschrijving is vervolgens gestructureerd door de geïnventariseerde
datasets te verbinden met de aanwezige informatietooling. Het resultaat staat in het hoofdstuk ['Analyse'](#analyse)

In het hoofdstuk ['Informatiemodellen'](#informatiemodel) is een eerste stap gemaakt naar het
verbinden van datasets door enkele kernentiteiten in de gebruikte
informatiemodellen op elkaar te mappen.

De bevindingen van deze voorstudie hebben geleid tot een aantal conclusies en
aanbevelingen voor het vervolg die zijn opgenomen in het [laatste hoofdstuk](#conclusies-en-aanbevelingen).

Gedurende dit onderzoek is veel informatie verzameld, die is vastgelegd in de
bijlagen bij dit rapport.

Management samenvatting
-----------------------

Tijdens dit onderzoek is duidelijk geworden dat er behoefte is aan het kunnen koppelen van data 'voor de meter' en 'achter de meter', en deze koppeling te laten verlopen via de reeds bestaande basisregistratie(s). Concreet gezegd zou het opnemen van een Uniek (BAG of BGT) ID in de verschillende registraties een goede basis leggen voor diverse informatieproducten binnen het thema 'energietransitie'. De Data is data van de installaties zelf, maar ook meet-data over verbruik, levering, opslag, conversie en transport van energie. Al deze data komt samen in een 'informatiepunt' dat gekoppeld kan worden aan de Basisregisters.

Het opnemen van zo'n uniek ID klinkt eenvoudig, maar is dat niet. Er moet tussen veel partijen overlegd worden over de concrete invulling daarvan, en de implementatie heeft impact op alle bestaande registraties en applicaties die nu nog niet zo'n ID hebben. Aan de andere kant is het mooi dat er al zoveel geregistreerd wordt: hierdoor kan een vliegende start worden gemaakt.

Het hebben van goede use-cases helpt bij het definieren van de voor de energietransitie benodigde informatieproducten. Het blijkt lastig om die goede uses-cases te bepalen. De verwachting is dat er de komende tijd meer usescases helder zullen worden.

Omdat de acceptatie van standaarden, classificatie en informatiemodellen niet vanzelfsprekend is, is sturing en beheer op de samenhang van standaarden belangrijk, en moet worden belegd. In dit kader kan gedacht worden aan de publicatie
van ontwikkelde standaarden op de overheidslijst van open-standaarden
