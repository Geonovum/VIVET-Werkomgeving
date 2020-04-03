## Conclusies en aanbevelingen

In dit hoofdstuk worden de belangrijkste conclusies uit de voorgaande hoofdstukken uitgelicht, en wordt een aantal aanbevelingen gedaan voor een eventuele vervolg.

<r>(todo: Aan de hand van hoofdstuk analyse en informatiemodel) bevindingen nalopen en omzetten in conclusies en aanbevelingen.)</r>

### Conclusies

#### Er is al veel data, maar niet beschikbaar

Uit de voorgaande hoofdstukken blijkt dat er al veel data en bijbehorende datamodellen beschikbaar is/zijn. Deze data is en wordt verzameld vanuit verschillende invalshoeken. Zo wordt door de installatiebranche data verzameld die alles te maken heeft met het beheer en onderhoud van installaties bij klanten. Het C-AR (Centraal aansluitregister) bevat opwek en verbruiksdata op aansluitingen niveau, De Netbeheerder hebben informatie over de netwerken. Er zijn registraties over energielabels van gebouwen, waar zonnepanelen liggen, waar windmolens staan.

#### er ontbreekt ook nog veel data

expliciet warmte data benoemen

#### Er zijn veel verschillende partijen betrokken 

Uit het hoofdstuk Landschapsverkenning blijkt dat er veel verschillende partijen betrokken zijn bij het verzamelen en gebruiken van 
data en informatie van de waarin een energie-component zit. De verschillende partijen hebben vaak ook een verschillende reden voor het vastleggen en gebruiken van die informatie.  

#### Er zit overlap in de datamodellen

Kijkend naar de datamodellen ontstaat een zelfde beeld. De datamodellen zijn gemaakt voor het doel dat zij dienen. Ook is er een overlap te zien, wat heel logisch is omdat dezelfde objecten (installaties, meetwaarden, leeftijden) in beschouwing worden genomen. 
Ook wil een zelfde naam voor iets niet zeggen dat er ook hetzelfde mee bedoeld wordt...

#### Er zit verschil in de datamodellen

Ook zit er verschil in de datamodellen, en in de data en informatie. Zo zijn vastleggingsmodellen anders dan de informatiemodellen. 
Ergens tussen data en informatie vindt een bewerking of berekening plaats.

#### Welke informatievraag is er eigenlijk?

Belangrijk is het om te werken vanuit een informatievraag waar use-cases onder liggen. Als je dat niet doet 
ontstaat het gevaar dat er aanbod-gedeven gewerkt gaat worden, waarbij het niet duidelijk is of de vraag 
naar het aanbod er eigenlijk wel is.... In het speelveld "energietransitie" leven verschillende 
informatievragen bij verschillende organisaties. Zo zullen netbeheerders geinteresseerd zijn in 
de (geplande) capaciteitsvraag voor hun netwerken, zodat zij daarop kunnen anticiperen. Installateurs 
zijn waarschijnlijk geinteresseerd in de vervangingsvraag voor installaties bij klanten, zodat zij daarop 
kunnen inspelen. Overheidsorganisaties zullen vooral willen weten of zij aan de CO2 doelstellingen voldoen.

### Aanbevelingen

### Voorstel voor doorontwikkeling informodel energie-installaties
<r>(Jan todo: Voorstel uitwerken conform werkplan VIII VIVET 2020)
a) Een voorstel hoe een breed gedragen informatiemodel voor energie-installaties tot stand kan komen om de huidige en toekomstige informatie-uitwisseling te faciliteren voor versnelling van de energietransitie.</r

#### Werk vanuit Use-Cases

Het is belangrijke om de juiste informatievraag te beantwoorden, en werken vanuit een usecase zorgt ervoor 
dat die inormatievraag helder wordt. Ook wordt de doelgroep voor de informatievraag duidelijk. Werken vanuit use-cases zorgt er ook voor dat er vraaggedreven gewerkt in plaats van aanbod gedreven.

#### Harmoniseer de begrippen

Juist omdat er zoveel partijen betrokken zijn bij de energietransitie, en er zoveel verschillende
informatievragen zijn, en er al zoveel verschillende data- en uitwissel modellen zijn, is het aan te 
bevelen om te werken vanuit een centraal begrippenkader, en vanuit een centrale data (model) repository. Dit voorkomt begripsverwarring, en het voorkomt het opnieuw uitvinden van het wiel. De definties en begrippen in de centrale repository moeten dan wel worden geharmoniseerd, met andere woorden de definite van een begrip is eenduidig, en wordt gedragen door alle betrokken partijen.

#### Maak waar mogelijk gebruik van reeds bestaande registers

Een heel belangrijke aanbeveling is om de verschillende datasets en registraties die er al zijn te koppelen aan het stelsel van  basisregistraties zoals BAG en BGT. 
Door aan te haken en aan te sluiten op die registers, worden de objecten die gerelateerd zijn aan de
energietransitie meteen voorzien van een goede locatie, een goed adres, en voorzien van een uniek ID. 
Dit unieke ID wordt ook reeds in andere registraties (bijvoorbeeld bij netbeheerders) gebruikt. Daarmee 
wordt het mogelijk om de informatie uit die andere registraties meteen te gebruiken of aan te koppelen. Belangrijk is 
wel om het juiste object uit BAG/GBT te kiezen waarop wordt aangesloten 
(BAG-ID of Pand-ID, ob VerblijfsObject-ID)

#### Maak waar mogelijk gebruik van bestaande interfaces

Hetzelfde als voor bestaande registers geldt ook voor bestaande interfaces. Het is beter te starten met 
iets dat er al is, dan helmaal opnieuw te beginnen. Een goede kandidaat is ESDL, omdat dit een simpel 
model is, bestaande uit een vijftal uitwissel objecten. Getoetst moet worden of het model niet te simpel 
is, immmers alle benodigde data moet wel uitgewisseld kunnen worden. Voor de interfaces van en naar BAG 
en BGT is het aan te raden om gebruik te maken van de reesds bestaande API's zoals hier beschreven.

#### Think Big, Act Small

Begin klein, maar denk wel aan het grotere geheel. Neem 1 of 2 objecten, werk die uit, en leer en doe 
ervaring op gedurende dat traject. De "energietransitie" is een dermate groot onderwerp dat het gevaar 
bestaat om teveel tegelijk op te pakken. Aanbevolen wordt om klein te beginnen, liefst met de belangrijkste informatievraag, en van daaruit verder te bouwen aan het informatiemodel en de onderliggende datamodellen.

#### Doe een vervolgonderzoek

Doe, om de vorige paragraaf handen en voeten te geven, een vervolgonderzoek of een PoC. Maakt die zo 
concreet mogelijk.


### Vervolgonderzoek

Deze eerste fase op weg naar een informatiemodel voor energie-installaties heeft
deels het het karakter van sporenonderzoek: een bepaald spoor leidt een onbekend
pad in en in dat pad vind je soms wel en soms niet zaken die van belang zijn.
Ook vind je er onderwerpen die mogelijkerwijs van belang kunnen zijn of in een
vervolgfase. Een aantal daarvan worden hieronder beschreven.

#### PBL Systematiek Monitoring RES (Regionale Energiestrategieën):

Op 23 maart 2020 heeft PBL de hoofdlijnen gepubliceerd van de wijze waarop de
voortgang van de RESsen gemonitord zullen worden. De opgave van de RES bestaat
uit twee onderdelen: de productie van een minimale hoeveelheid hernieuwbare
elektriciteit in 2030 en het opstellen van regionale structuur voor de
warmtevoorziening. Dit laatste onderdeel zal vooral kwalitatief worden getoetst
en is hier minder interessant, maar monitoring van de elektriciteitsplannen kent
een aanmerkelijke kwantitatieve component. Productie van elektriciteit gebeurt
uiteraard met energie-installaties en de planning en realisatie kan met
verschillende eenheden gebeuren (capaciteit, productie) en om daarmee te kunnen
werken zijn vollasturen noodzakelijk, die verschillen per type installatie en
per locatie. Deze cijfers kennen ook verschillende kwalificaties: realisatie,
prognose, actualisering van schattingen, e.d. Het aantal betrokken partijen is
hier fors: de 30 RESsen rapporteren aan het Nationaal Programma RES, die de
cijfers consolideren voor beleid, daarbij voor monitoring ondersteund door PBL.
Ook zullen de RES-cijfers door netbeheerders, gemeenten en hun adviseurs
gebruikt worden voor allerlei exercities in het kader van de energietransitie.
De systematiek gaat uitgebreid in op de gewenste kwantiteiten en beschrijft deze
ook.

Een prima basis dus om deze datastromen te modelleren. Het rapport en
bijbehorende achtergrond-documentatie is beschikbaar op de site van PBL:
<https://www.pbl.nl/publicaties/systematiek-monitor-res>

#### Warmte

Gefragmenteerde sector. Nu woningbestand wordt aangepakt, komen er nieuwe
samenwerkingsverbanden, bijv. in kader van MMIP-programma van de TKI Energie:
WarmingUP (MMIP4 collectieve warmte) en IETBB (MMIP3 en MMIP4 gebouw-gebonden
warmte). Hierbij zijn vele partijen betrokken it de hele warmteketen en dat
geeft nieuwe mogelijkheden om met de warmtesector te werken aan inzicht in de
desbetreffende informatievoorziening.

Een uitvraag bij de (Vattenfall, HVC, Ennatuurlijk) naar hun gehanteerde
informatiemodellen zou geïnitieerd kunnen worden.

ACM is een andere bron. ACM vraagt veel informatie op van warmtebedrijven voor
handhaving reguleringsregime. Dit is uitgewerkt in bijv. het Warmtebesluit
(<https://wetten.overheid.nl/BWBR0033940/2020-01-01>), waarin gespecificeerd is
over welke temperatuur- en aansluitcategorieën de warmtebedrijven moeten
rapporteren. Ook in het Tarievenbesluit Warmte is veel te vinden over de
informatie-uitvraag door ACM:
<https://www.acm.nl/sites/default/files/documents/2019-12/tarievenbesluit-warmteleveranciers-2020.pdf>.

Deze classificaties kunnen dienen bij informatiemodellering van
warmte-installaties. Ook dit is overigens een dynamisch veld, omdat de
regulering van het warmtesysteem de komende jaren zich nog sterk zal
ontwikkelen.

#### Energy Data Repository

Informatiemodellen bevatten verwijzingen naar in het universum geaccepteerde
definities, classificaties e.d. die vastgelegd zijn in thesauri of repositories.
De taal ESDL is verbonden met een z.g. Energy Data Repository, die nu nog
slechts verwijzingen bevat naar SBI-codes (CBS) en Energiedragers (RVO). Het
verdient aanbeveling om dit concept uit te breiden, en de geïnventariseerde
classificaties in dit onderzoek kunnen daar een goede bron voor zijn. Voor het
warmtedomein kan hier gedacht worden aan definities voor verschillende typen
biomassa en biofuels-installaties. Experts van CBS, NVWA, SDE-registratie en het
Team Biomassa van RVO kunnen hiertoe kennis inbrengen, bij voorkeur gerelateerd
aan internationale geaccepteerde normen.

Het is belangrijk om hier de juiste governance voor te ontwikkelen, zodat
repositories ook de noodzakelijke statuur krijgen.

#### EFI Energy Flexibility Interface

FAN (Flexible Power Alliance Network) heeft EFI ontwikkeld, de Energy
Flexibility Interface. EFI is een communicatieprotocol dat het mogelijk maakt
voor een eindgebruiker om diverse slimme apparatuur te besturen, zoals
wasmachines, airco, zonnepanelen, opladen van de auto en daarmee flexibele
energie te ontsluiten. In dit protocol zijn ook diverse typen
energie-installaties gedefinieerd. De specificatie van EFI is beschikbaar op
<https://github.com/flexiblepower/efi>.

#### Internationaal perspectief 

Op dit moment wordt uiteraard ook internationaal gewerkt aan
informatiestandaarden in het energiedomein en open source-ontwikkelingen. De
inbreng hiervan kan zorgen voor een meer toekomstvaste informatievoorziening.
Andersom kunnen ontwikkelingen in NL (te denken is dan aan ESDL) ook
internationaal ingebracht worden. Expertise van RVO/ECW, zowel inhoudelijk als
kennis van ontwikkelingen bij de EU kan hier ingezet worden.

#### Invoering begrip Standaardjaarafname (SJA) en Standaardjaarinvoeding (SJI) 

Het standaardjaarverbruik (SJV) is een kernvariabele in energiedata. Kort gezegd
is het het voor temperatuurseffecten gecorrigeerd verbruik van gas door een
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

-   TNO:
    [https://energy.nl](https://energy.nl/en/search/?fwp_content_type=factsheets&fwp_paged=2)

-   CE Delft: <https://www.ce.nl/warmtetechnieken>

-   Expertise Centrum Warmte:
    [https://expertisecentrumwarmte.nl/kennis/factsheets/](https://expertisecentrumwarmte.nl/kennis/factsheets/default.aspx)
