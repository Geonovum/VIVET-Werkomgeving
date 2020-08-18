Inleiding
---------

### Context

Het programma
[VIVET](https://www.geonovum.nl/uploads/documents/Rapport%20VIVET%20Definitief-1.0.pdf)
(Verbetering Informatie Voorziening EnergieTransitie) bevat voorstellen voor de
verbetering van de informatievoorziening van de energietransitie. Het programma
is opgesteld door het CBS, het Kadaster, PBL, RVO.nl en Rijkswaterstaat op
verzoek van de ministeries van Economische Zaken en Klimaat en Binnenlandse
Zaken en Koninkrijksrelaties. In het werkplan VIVET t/m maart 2021 is een
achttal activiteiten voorzien. Project VIII bevat activiteiten die conditioneel
zijn voor en daaromgerelateerd zijn aan de overige projecten. Het project omvat
drie onderdelen, die aan elkaar gerelateerd zijn, maar in afzonderlijke
rapportages zijn uitgewerk:

-   VIII-A: Datastandaarden;

-   VIII-B: ICT-Architectuur;

-   VIII-C: Informatiemodel Energie-installaties nadere uitwerking van de
    voorstudie VIMET-I (Vivet Werkplan 2019).

### Datastandaarden

#### Doel en resultaat

Project beschrijving

#### Aanpak

Kort noemen: Belang van voorbereiding en methodiek, Werken met use cases

Doelgroep
---------

Dit document is primair bestemd voor de opdrachtgever, de Stuurgroep VIVET.
Daarnaast is het gericht op beheerders van huidige registraties, stakeholders
uit energiedomein en beleidswereld, en kennisdragers op het gebied van
informatievoorziening.

Leeswijzer
----------

XXX dit nog verwerken in de leeswijzer: :

>   Voorbereiding

>   Methodiek

>   Definitie en selectie van use cases

>   Use case ‘Gebouw en Energie’

>   Use case 2

>   Use case 3

>   Conclusies

>   Aanbevelingen

XXX

Tekst uit VIMET-I – nog bovenstaande in verwerken

Na deze inleiding bevat dit rapport achtereenvolgens een beschrijving van het
landschap met registraties van energie-installaties, zowel qua datasets als
gehanteerde informatietooling (informatiemodellen, classificaties e.d.).

Deze beschrijving is vervolgens gestructureerd door de geïnventariseerde
datasets te verbinden met de aanwezige informatietooling. Het resultaat staat in
het hoofdstuk ['Analyse'](#analyse)

In het hoofdstuk ['Informatiemodellen'](#informatiemodel) is een eerste stap
gemaakt naar het verbinden van datasets door enkele kernentiteiten in de
gebruikte informatiemodellen op elkaar te mappen.

De bevindingen van deze voorstudie hebben geleid tot een aantal conclusies en
aanbevelingen voor het vervolg die zijn opgenomen in het [laatste
hoofdstuk](#conclusies-en-aanbevelingen).

Gedurende dit onderzoek is veel informatie verzameld, die is vastgelegd in de
bijlagen bij dit rapport.

Management samenvatting
-----------------------

Een InformatieModel Energie-Installaties heeft betrekking op
informatieverzamelingen uit een cross-sectoraal landschap (bouw, energie,
installatie-onderhoud, assetmanagement, basisregistraties). Het realiseren van
slimme koppelingen op informatie-technisch gebied is effectiever dan een nieuw
fysiek register opzetten. Goed gedragen usecases kunnen hier de richting
aangeven.

Informatiekundig bestaat meer samenhang tussen de vele datasets die ontwikkeld
zijn in de bouw- en installatiewereld dan die in het energiedomein. Voor VIVET
is het van groot belang dat er één taal gesproken wordt om die samenhang te
creëren. Daartoe is een inventarisatie gemaakt van z.g. infotools:
afsprakenstelsels, informatiemodellen, classificaties en datasets. Deze zijn aan
elkaar gerelateerd waardoor duidelijk werd welke informatiemodellen en
kernentiteiten centraal staan bij het brengen van samenhang.

Resultaaat van deze studie is ook dat de stakeholders van de huidige
registraties veel betrokkenheid hebben getoond en verdere samenwerking beogen.
Dit heeft naast een netwerk ook gezorgd voor een uitgebreid (en deels nog niet
in kaart gebracht) overzicht van de aanwezige data, informatiemodellen en
initiatieven rond installaties, energie en gebouwde omgeving.

De geselecteerde vier informatiemodellen IMSG, ESDL, CIM-Ceres en
Installatieregister blijken, na een mapping met behulp van enkele
kandidaat-kernentiteiten, een goede basis te vormen voor doorontwikkeling naar
een geharmoniseerd InformatieModel Energie-Installaties, waarvan een eerste
versie is beschreven. De vier informatiemodellen hebben overlappende use cases,
kennen voldoende samenhang, zijn op globaal niveau vergelijkbaar en bieden met
geo-standaarden bruikbare koppelvlakken met basisregistraties BAG en BGT. Bij
doorontwikkeling zullen entiteiten en kenmerken van de vier informatiemodellen
nog in detail moeten worden verbonden in het resulteren informatiemodel, waarin
delen van ESDL en CIM-Ceres kunnen naar verwachting worden overgenomen.

Tijdens dit onderzoek is duidelijk geworden dat er behoefte is aan het kunnen
koppelen van data 'voor de meter' en 'achter de meter', en deze koppeling te
laten verlopen via de reeds bestaande basisregistratie(s). Concreet gezegd zou
het opnemen van een Uniek (BAG of BGT) ID in de verschillende registraties een
goede basis leggen voor diverse informatieproducten binnen het thema
'energietransitie'. De Data is data van de installaties zelf, maar ook meet-data
over verbruik, levering, opslag, conversie en transport van energie. Al deze
data komt samen in een 'informatiepunt' dat gekoppeld kan worden aan de
Basisregisters.

Het opnemen van zo'n uniek ID klinkt eenvoudig, maar is dat niet. Er moet tussen
veel partijen overlegd worden over de concrete invulling daarvan, en de
implementatie heeft impact op alle bestaande registraties en applicaties die nu
nog niet zo'n ID hebben. Aan de andere kant is het mooi dat er al zoveel
geregistreerd wordt: hierdoor kan een vliegende start worden gemaakt.

Het hebben van goede use-cases helpt bij het definieren van de voor de
energietransitie benodigde informatieproducten. Het blijkt lastig om die goede
uses-cases te bepalen. De verwachting is dat er de komende tijd meer usescases
helder zullen worden.

Omdat de acceptatie van standaarden, classificatie en informatiemodellen niet
vanzelfsprekend is, is sturing en beheer op de samenhang van standaarden
belangrijk, en moet worden belegd. In dit kader kan gedacht worden aan de
publicatie van ontwikkelde standaarden op de overheidslijst van
open-standaarden.
