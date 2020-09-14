Use case 1 – Gebouw en energie
------------------------------

#### Mogelijke scope

-   gebouwen: link met gebouw decompositie, datastelsel utiliteitsbouw,
    installatieregister, EAN \<\> BAG, DiSGeo, WKB, en andere projecten in de
    kolom ‘Bouw’ (schema hierboven)  
    leidt tot bijv. IM-Gebouw, als verbinding tussen Energie / Installatie /
    DiSgeo / BIM

#### Omgevingsanalyse / stakeholders

Aan de use case ‘Gebouw en Energie’ direct gerelateerde Initiatieven en partijen
(stakeholders, bestuurlijke organisaties):

| **Uitvoerings-initiatieven**                                                  | **Stakeholders**                  | **Belang van stakeholders**                                                                                 | **Bestuurlijk**            | **Rol Vivet**                                                                                          |
|-------------------------------------------------------------------------------|-----------------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------|--------------------------------------------------------------------------------------------------------|
| **RES, TVW (Warmte transitieplannen)**                                        | RES, ETRM, PBL, CBS               | Randvoorwaardelijk voor ET, Inzicht in energieverbruik, Input voor TVW                                      | BZK, EZK                   | VIVET core belang, standaardisatie en afspraken                                                        |
| **EAN-BAG koppeling**                                                         | Netbeheer NL, Kadaster, CBS, EDSN | Energiewet, koppelen verbruik en gebouwen                                                                   | ACM, EZK                   | parallel met Vivet VII; kennis, verbinden, start- / top model aanleveren                               |
| **WEU ( Werkelijk Energieverbruik Utiliteitsgebouwen)**                       | RVO, Platform duurzaam bouwen     | In 2020 werkende 1e versie opleveren                                                                        | BZK, Topsector energie     | In sept / okt start model aanleveren                                                                   |
| **DisGeo**                                                                    | BZK en partners                   | Uitwerken IM mbv use cases                                                                                  | BZK                        | Koppeling Basisregistraties met energiedomein                                                          |
| **Installatieregister**                                                       | TechniekNL                        | Verbinding met ketenpartners en invulling afsprakenstelsel-gedachte                                         | EZK                        | Verbinden installatie domein met DisGeo (o.a. gebouwen) en energiedomein                               |
| **Opstellen van datastandaard energienetten door en voor alle netbeheerders** | Netbeheerders                     | Eigen informatiesystemen ‘tijd-stabiel’ verbinden met ‘buitenwereld’ (basisreg., IMKL, DSO, etc.)           | pm                         | Direct verbonden met Vivet IV, maar ook relatie met bijv. Vivet VII                                    |
| **DSO Digitaal Stelsel Omgevingswet**                                         | Partijen DSO                      | Ow kan gemakkelijk gewijzigde info mbt energie-infra opnemen                                                | Gemeenten, Provincies, BZK | Afstemming DSO en Energiedomein: begrippen, datastandaarden en informatiemodellen                      |
| **ESDL**                                                                      | TNO                               | EDSL vermarkten en uitbreiden                                                                               | Topsector energie          | Harmoniseren ESDL met DisGeo en andere domeinen                                                        |
| **Vivet partners**                                                            | BZK, EZK                          | Creëren en bewaken van samenhang informatie-modellen, Realiseren ontwikkelen en Beheer IM energie-transitie |                            | Initiatief en realiseren samenhang en standaardisatie van informatie in energie en aanpalende domeinen |

Er zijn ook initiatieven die *indirect* gerelateerd zijn aan deze use case; wel
aan het energiesysteem, maar losser aan de gebouwde omgeving. Die zijn in
onderstaande tabel opgenomen:

| **Uitvoerings-initiatieven**                   | **Stakeholders**          | **Belang van stakeholders**                                                                                      | **Bestuurlijk** | **Rol Vivet**                                       |
|------------------------------------------------|---------------------------|------------------------------------------------------------------------------------------------------------------|-----------------|-----------------------------------------------------|
| **Afsprakenstelsel Facilitering Energiemarkt** | Sectoren in energiedomein | Energieverbruiken en opwek verbinden met basisregistraties (proces-aspect marktfacilitering is losser verbonden) | EZK             | afstemming datamodellen energiemarkt                |
| **Energiewet**                                 | EZK, Energiesector        | Data is één van de pijlers in de wet; datastandaarden zorgen voor een fundament                                  | EZK             | data-aspecten van energiewet verwerken in projecten |

Bovengenoemde initiatieven, inclusief alle Vivet-projecten 2020, zijn weergegeven in [Contextdiagram Vivet VIII](20200914-Vivet-VIII-Contextdiagram.png). 

#### Relevante documenten 

##### Bouwwerken in samenhangende objectenregistratie

Binnen het programma [Samenhangende Object Registraties (SOR)](https://www.geobasisregistraties.nl/basisregistraties/doorontwikkeling-in-samenhang/objectenregistratie) is een onderzoek uitgevoerd naar de realisatie van een model voor bouwwerken. Het resulterende model is nog in een 'houtskoolschetsfase'.

Een belangrijke constatering in het onderzoek is dat het BIM-concept als meest belovend uitgangspunt is genomen. Voor het domein van energie en energie-installaties lijkt dat een goed uitgangspunt omdat er een relatie met de (utiliteits)bouw sector is.

![](media/SOR-gebouwenmodel-houtskoolschets.png)
Figuur X: Model voor gebouw in ontwikkeling bij SOR (bron: Eindrapport werkgroep bouwwerken, SOR 25-02-2020)

Een uitgangspunt van het model is dat op elk niveau behalve het kleinste het geheel uit delen is op te bouwen.
Dit model is te vertalen naar de concepten van de IFC standaard. Het model is in ontwikkeling, doorontwikkeling is o.a. naar 3D.

Interessant is het concept Installaties / voorzieningen:
Omschrijving:  
Geheel van een relevantie installatie of andere voorziening in of aan en ten dienste van het Gebouw(blok).
Toelichting:  
Begrip gebaseerd op de fysieke deelobjecten uit de WOZ, de GebouwInstallatie uit NEN.

Het is de vraag of in, op of aan het gebouw aanwezige energie-installatie hier ook onder vallen.

##### Common ground architectuurprincipes

Uitwisselen van gegevens binnen en tussen gemeenten is van groot belang. 
Common Ground zorgt voor een andere, gegevensgerichte, manier van uitwisseling, met behulp van een Gemeentelijk Gegevenslandschap. 
Dit is gebaseerd op het [GEMMA Gegevenslandschap](https://www.gemmaonline.nl/index.php/Gegevenslandschap), waarin processen en gegevens gescheiden zijn door een vijf-lagenstructuur. 
Er wordt gewerkt met een gemeenschappelijke integratielaag. 
Data worden opgehaald met API’s die voldoen aan de [API-standaarden zaakgericht werken](https://www.vngrealisatie.nl/producten/api-standaarden-zaakgericht-werken); er bestaat een [overzicht van API’s binnen de Nederlandse overheid](https://developer.overheid.nl/apis).  
Common ground is gebaseerd op de volgende informatiearchitectuurprincipes: 
![](media/Common-Ground-Informatiearchitectuurprincipes.png)

Figuur X: Een opsomming van de Informatiearchitectuurprincipes die ten grondslag liggen aan Common Ground

De implicaties hiervan zijn beschreven in de [Common Ground Informatiearchitectuurprincipes](https://www.gemmaonline.nl/images/gemmaonline/6/67/20190328_-_Gemeentelijk_Gegevenslandschap_-_Informatiearchitectuurprincipes.pdf). 
Daarnaast hanteert Common Ground een aantal realisatiepricipes: 

![](media/Common-Ground-Realisatieprincipes.png)

Figuur X: Een opsomming van de Realisatieprincipes die ten grondslag liggen aan de Common-Groundbenadering

Van deze principes zijn de implicaties beschreven in ‘CG-realisatieprincipes/docs dat is te vinden op de pagina [Voor architecten bij gemeenten’](https://commonground.nl/cms/view/54476259/wat-is-common-ground/54476518). 
Lees hier méér over [Common Ground](https://www.vngrealisatie.nl/roadmap/common-ground). 

##### Digideal Gebouwde Omgeving

De DigiDealGO kan worden beschouwd als de Nationale Digitaliseringsagenda voor de Gebouwde Omgeving.


Citaat uit document DigiDealGO: *' Voor de circulaire bouweconomie is op termijn een actuele virtuele kopie van
het bouwwerk nodig gekoppeld aan digitale product- en materiaalinformatie Voor Smart Cities,
energietransitie en waterhuishouding moeten we slimme bouwwerken koppelen aan actuele
omgevingsinformatie. Het gaat om informatie-ketens en diensten rondom een virtueel bouwwerk
dat de levenscyclus van dat bouwwerk volgt (van ontwerp tot sloop)' *

![](media/DigiDeal-virtueelBouwwerk.png)

Figuur X: Het virtuele bouwwerk (middelste laag) draagt de informatie over het fysieke bouwwerk gedurende zijn levenscyclus. Verschillende dossiers waaronder energie zijn gekoppeld aan het virtuele bouwwerk. (bron: Digitaal Stelsel Gebouwde Omgeving, versie 0.9 - Concept)

DigiDealGo werkt met 'versnellingsprojecten' die passen binnen de visie.

Het project Datastelsel Energieverbruik Utiliteit is een project met een DigiDealGo stempel.
Dat project heeft o.a. als doel meer data-gedreven verduurzaming.

![](media/DatastelselEnergieverbruikUtiliteit.png)

Figuur X:  Data-gedreven verduurzamingsprojecten kenmerken zich veelal door realistische business-cases en lagere integrale
kosten.  (bron: Project Datastelsel Energieverbruik Utiliteit)

##### Digitaal Gebouwdossier

Min BZK voert (2020) een verkenning uit naar de ontwikkeling van een digitaal gebouwdossier, waarmee eenmaal digitaal ingewonnen data voor hergebruik beschikbaar komt, zonder dat gestreefd wordt naar volledigheid. 
Een groeimodel wordt voorzien, met als belangrijkste eis aan de data dat deze voorzien wordt van een uniek objectidentificatienummer (UOI), dat gekoppeld is aan een gebouw of onderdeel daarvan. 
Voor het overige worden voorlopig geen eisen aan de data gesteld; uit de gebruikspraktijk van het gebouwdossier zal blijken waar de prioriteiten met betrekking tot verdere structurering, standaardisering, formalisering, validatie en metadatering liggen. 
Voor zover bestaande wet- en regelgeving hier niet reeds in voorziet, kunnen hierover naar behoefte op termijn al dan niet wettelijk vastgelegde en afdwingbare eisen opgesteld worden.

De scope is in eerste instantie gericht op de woning- en utiliteitsbouw, en neemt daarom de klasse ‘GEBOUW’ in IMGeo als uitgangspunt: “Vrijstaande overdekte en geheel of gedeeltelijke met wanden omsloten toegankelijke ruimte die direct of indirect met de grond is verbonden.” 
Op termijn zal aansluiting bij de Omgevingswet noodzakelijk zijn en daarin is BOUWWERK ruimer omschreven, omdat deze de grond-, weg- en wegenbouw betreft: “Constructie van enige omvang van hout, steen, metaal of ander materiaal, die op de plaats van bestemming hetzij direct of indirect met de grond verbonden is, hetzij direct of indirect steun vindt in of op de grond, bedoeld om ter plaatse te functioneren, met inbegrip van de daarvan deel uitmakende bouwwerkgebonden installaties.” 

Qua architectuur is ‘data bij de bron’ het uitgangspunt, net zoals bij Common Ground. Het gebouwdossier krijgt dan een fluïde, virtueel karakter: afhankelijk van de vraag van de gebruiker en de beschikbare bronnen wordt het dossier ‘on the fly’ samengesteld. 

Goede afspraken met partijen zowel aan vraag als aan bronzijde zijn noodzakelijk; deze worden tegenwoordig vaak vastgelegd in een z.g. afsprakenstelsel. 

De objectenregistratie, de doorontwikkeling van de huidige geo-basisregistraties, lijkt een geschikt fundament om zowel publieke als private gebouwinformatie aan op te hangen. 
De ontwikkeling van een digitaal gebouwendossier past overigens prima binnen de beleidslijn Digitale Agenda Overheid. Min BZK draagt systeemverantwoordelijkheid voor de bouwsector. 
Vanuit die rol is het logisch dat BZK aandacht heeft voor een gezonde werking van de informatiehuishouding in de bouw, te meer daar niet wordt voorzien dat ‘de markt’ dit op zal pakken. 
BZK geeft daar middels onder meer de introductie van het consumentendossier, het subsidiëren van het BIM-loket en het ondertekenen van de Digitaliseringsdeal Gebouwde Omgeving invulling aan. 
Het digitaal gebouwdossier is een volgende stap in het invulling geven aan de regierol. 

Er zijn verschillende ontwikkelingen waarbnij het bouwdossier groot nut kan bieden: de energietransitie, circulair bouwen, de bouwopgave. 

NB: hier nog verwijzen naar de notitie van Dirk van Barneveld c.s.? 

##### DiSGeo

PM

##### Europa en data-infrastructuur voor fysieke leefomgeving

 “In 2024 is de Nederlandse
INSPIRE-infrastructuur de basis voor het beantwoorden van de pan-Europese vraag naar geo- en milieuinformatie. Hiermee draagt INSPIRE bij aan het versterken van het klimaat- en milieubeleid. Europese en
internationale instanties halen kwalitatief hoogwaardige INSPIRE-data bij de Nederlandse dataproviders (en
vice versa). De vraag naar gegevens wordt daarbij leidend, daarom wordt bij het harmoniseren van
gegevens prioriteit gegeven aan gegevens waar vraag naar is”

INSPIRE is onderdeel van de Europese Green Deal, een nieuwe groeistrategie, die de EU moet omvormen tot een eerlijke en
welvarende samenleving, met een moderne, hulpbronnenefficiënte en concurrerende economie, waar vanaf
2050 netto geen broeikasgassen meer worden uitgestoten en economische groei is losgekoppeld van het
gebruik van hulpbronnen. Het nieuwe Europese beleid kent twee belangrijke pijlers: de vergroening in de Green Deal en digitalisering
oftewel ‘’Shaping Europe’s digital future’. In de Europese Datastrategie promoot de Commissie de ontwikkeling van een gemeenschappelijke Europese
data space om de ontwikkeling van een data economie te ondersteunen en het gegevensgebruik in de hele
EU te vergroten.

![](media/CommonEuropeanDataspace.png)

Figuur X:  Het energiedomein (a Common European energy data space) is een onderdeel van de gedeelde Europese dataspace. (bron: Quick scan Europa en data-infrastructuur fysieke leefomgeving)

![](media/DirectiveForEnergyData.png)

DG ENER omvat nieuw EU beleid rond energie en data.


##### Installatiregister Visie TN

Techniek Nederland beoogt om met samenwerkingspartners te komen tot een samenhangend geheel van informatie rondom installaties, onder de werktitel “Installatieregister Nederland”. 

Informatie uit het Installatieregister is niet voor commerciële en acquisitiedoeleinden bedoeld en is te gebruiken door onder andere dienstverleners, fabrikanten, netbeheerders en bevoegd gezag. 
Dit wordt gerealiseerd vanuit een stelsel van afspraken. 

Met een installatieregister wordt beoogd om een samenhangend geheel te maken, waar op basis van open standaarden en classificatie informatie ontsloten wordt, die nu in veel diverse registraties vast ligt. 
Vanuit deze visie kunnen diverse gebruikers en raadplegers – binnen de wettelijke en afgesproken kaders – toegevoegde waarde bieden én krijgen van informatie over installaties en producten. 

Softwareleveranciers kunnen op basis van marktvraag applicaties ontwikkelen. Fabrikanten van installaties/-onderdelen kunnen gericht eventuele terugroepakties gefaciliteerd krijgen. 

Er bestaan diverse (classificatie-, communicatie-)standaarden (zoals NL-SfB, ETIM e.d.) en TN beoogt hier een samenhangend ecosysteem van te maken in het kader van de Digideal Gebouwde Omgeving. 
Dit kan leiden tot onderdelen van een toekomstig Digitaal Stelsel Gebouwde Omgeving (DSGO). 


##### Landelijke Informatievoorziening Vastgoed - behoeftenonderzoek

De afgelopen jaren hebben het CBS, Kadaster en Geonovum samen gewerkt aan de ontwikkeling van een landelijke informatievoorziening vastgoedgebruik (LIV). De huidige LIV is een unieke databron die een aantal registraties verbindt m.b.v. unieke sleutels. 
De LIV voorziet in landelijke, integrale, en afgestemde gegevens over alle vastgoedobjecten in Nederland. 
![](media/LIV-onderdelen.png)

Figuur X:  De achterliggende databronnen waaruit LIV is opgebouwd. 

Er is onderzocht of deze voorziening tegemoet komt aan de behoefte bij belangrijke maatschappelijke thema’s, zoals de energietransitie. 
Dit behoeftenonderzoek is te vinden bij [Geonovum](https://www.geonovum.nl/uploads/documents/Quick%20scan%20behoefteonderzoek%20LIV-%20defintief%20%283%29.pdf)
Het is een open deur te stellen dat er bij de energietransitie behoefte is aan gegevens over vastgoed. Deels gaat het om direct energierelevante kenmerken, zoals de mate van isolatie, installaties, gevel, bouwhoogte, enzovoorts. Deels heeft de vraag een meer algemene aard: hetgoed afbakenen van typen vastgoed (wat is een kantoor, een winkel?), maar ook bouwjaar, volume en oppervlakte zijn hierbij relevant. 

De achterliggende databronnen bepalen de inhoud van de LIV. Dat zijn primair de basisregistraties BAG, WOZ, HR en BRP. Dezebasisregistraties zijn elk voor een eigen toepassingsterrein ontwikkeld.
Belangrijk uitgangspunt voor de LIV is dat gegevens gekoppeld worden via het BAG-id.De microdatabestandenover energieverbruik beschikken ook over deze sleutel en kunnen dus ook met de LIV gekoppeld worden. Ook informatie over vastgoed op adresniveau kan in principe aan de LIV gekoppeld worden. 

Er kunnen verschillende toepassingen onderkend worden, zoals naast informatie over energieverbruik het verkrijgen van meer inzicht in de locaties van zonne-installaties. 

LIV kan dus faciliteren bij het verbinden van de basisregistraties met datasets in het energiedomein. Een robuuste vorm van informatiemodellering is daartoe noodzakelijk. 

##### PIR/CERES Logisch gegevensmodel

PIR, het ProductieInstallatieRegister bevat gegevens van energie-opwekinstallaties. 
In de loop van 2020 heeft CERES deze taak overgenomen. 
In de studie naar een energie-installatieregister zijn enkele kernenititeiten van CERES gemapt op het IM Smart grids. 
![](media/IMEnergie_en_CIM_Ceres.png)

Figuur X:  De mapping van het IMEnergie op CIM-CERES. 

##### Referentiemodel Stelsel Basisregistraties

PM

##### TNO Data voor TVW en WUP

Inventarisatie van bechikbare data voor het opstellen van Transitievisie Warmte
en Wijkuitoveringsplannen door gemeenten.

##### Unieke Object Identifier

Verkenning in het kader van:

1.regie op bouwgegevens

2.samenhangende objectenregistratie

##### Werkelijke Energieverbruik Utiliteitsgebouwen (WEU)

Het opvragen van verbruiksgegevens door zakelijke energiecontractanten,
vastgoedeigenaren en gebouweigenaren. Andere gebruikers zijn Omgevingsdiensten
(tbv handhaving), ODA’s en beleidsmakers.

##### Data Sharing Coalition

<https://datasharingcoalition.eu/>

Gerelateerd aan Data Deel Afsprakenstelsel?
