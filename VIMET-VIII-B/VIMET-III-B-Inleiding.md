TIPS VOOR VERDERE AFRONDING

Op veel plekken telegramstijl
\@\@ = vraagtekens – nog uit te werken.
Bron van de afbeeldingen: ‘*Verzameling afbeeldingen eindrapport.pptx*’ op
U-schijf / map Eindrapport 
De plaatjes hebben per sheet een naamgeving (onderin notitie van elke sheet).  
De afbeeldingen worden bij een wijziging vanuit deze .pptx als afbeelding (.png)
in de map ‘media’ gezet. Deze .png’s krijgen de naam zoals in de notitie van
elke sheet staat. En dat is ook de naam die in dit rapport gebruikt wordt. 

Hoofdstuk Inleiding
-------------------

-   Context

Energietransitie / versnipperd energielandschap / Vivet / Use case Warmte
gekozen vanwege grote diversiteit van sector en informatiebronnen.

-   Punt op de horizont

Plaatje *Lagen Nationaal Metamodel
(https://www.noraonline.nl/wiki/Modellering_van_gegevens)*
<figure id="Metamodel">
<img src="media/Lagen_Nationaal_Metamodel.png" alt="">
<figcaption>Metamodel</figcaption>
</figure>

Toelichting: informatie onderdeel van informatiesystemen die deel uitmaken van
organisaties. Informatielandschap versnipperd, maar ingrijpend om hier in te
grjpen omdat je dan aan organisatie komt. Hoe meer versnippering, hoe
ingrijpender.

Begrippen zijn minder verankerd in informatiesystemen, begrippen slaan op de
taal die men spreekt. Informatiemodellering zorgt voor vertaalslag van begrippen
naar informatiesystemen.


-   Waarom begrippenkader

Geen gevestigde informatiemodellen gevonden in warmtedomein. Wel grote behoefte
aan uniformiteit qua taal. Begrippenkader: minder belangen en breed ecosysteem:
ook wetgeving, subsidies. De basis voor informtiemodellering

Proces: inventariseren en relateren van begrippen / vaststellen van begrippen en
hun relaties / harmoniseren van begrippen / beheer en onderhoud.

-   Terugblik op Vimet 2019

Waar zit de verbinding met Vimet 2019 precies? Use case Installaties /
Gebouwen - Domein in Vivet Conceptueel InformatieModel

-   BegrippenCatalogus warmte 2020

Het idee bij het inrichten van een begrippencatalogus: toegankelijk / verbindend / ...

-   Doel met deze aanpak

Ambitie: alle herkomstbronnen van begripsdefinities in het warmtedomein

-   Resultaat

Een rijkdom aan bronnen en goede kansen om deze brede verzameling aan
elkaar te relateren en in de toekomst te harmoniseren.

-   Doelgroep

Partijen met herkomstbronnen benoemen. Doelgroep volgende stap: beleidsmakers,
materiedeskundigen warmtesector, wetgeving, informatiespecialisten, partij die
autoriteit / governance op zich wil nemen.

-   Leeswijzer

Hoofdstuk *Methodiek en techniek* beschrijft achtergrond van begrippencatalogus,
MIM, selectie van tooling, en ‘spoorzoeken’ naar warmtebegrippen, opsomming van
bronnen, opsomming van benaderde partijen.

Hoofdstuk *Begrippencatalogus* geeft een beschrijving van het resultaat: de
geïnventariseerde begripen, de linkjes naar de herkomstbronnen van
begripsdefinities, de gemaakte keuzen bij het bouwen van de hiërachie van
begrippen.

Hoofdstuk *Bevindingen, Conclusies en Aanbevelingen* doet in grote lijnen verslag van wat we tijdens dit
project zijn tegengekomen, en zet deze in Vivet-perspectief van Vivet.

Hoofdstuk Samenvatting
----------------------

Dit schrijven wanneer hoofdstuk bevindingen, conclusies, aanbevelingen gereed is.
Of deze samenvatting weglaten als deze beperkt blijft. 

Hoofdstuk Aanleiding en opdracht
--------------------------------

Hoofdstuk Methodiek en techniek
-------------------------------

*dit hoofdstuk: Joeri*  
### Begrippencatalogus

Een begrippencatalogus is méér dan een opsomming van begrippen: het beschrijft ook – op structurele wijze – de wijze waarop de begrippen met elkaar samenhangen. 
Zo is een energienet een bredere term van warmtenet, is een kleinverbruiker een smallere term van verbruiker en is consument een geletateerde term aan verbruiker. 
Synoniemen voor begrippencatalogus zijn *thesaurus* en *vocabulaire*. 

De begrippencatalogus wordt stapsgewijs opgebouwd, en de bouwstenen krijgen ook deze benaming: Begrippencatalogus Warmte, Begrippencatalogus Hernieuwbare Energie. 
Deze bouwstenen worden later opgenomen in de Begrippencatalogus Energievoorziening. 
De begrippen zijn in doorgaans niet zelfstandig gedefinieerd in de begrippencatalogus, maar verwijzen naar Herkomstbronnen begripsdefinities, waarin de definities beschreven zijn. Dit kunnen wetten zijn, normen, documenten met subsidie-voorstellen, artikelen op websites, etc. Maar ook kan verwezen worden naar andere begrippencatalogi. 
Bij voorkeur gebeurt dat met Linked Data-technieken, zodat begrippen en definities machinaal vindbaar zijn. 
Door de overzichtelijke zoekfunctie op term, definitie en bron helpt de Begrippencatalogus Energie de leesbaarheid en toepassing van deze bronnen te vergroten. 
De begrippencatalogus is het woordenboek, waaruit geput kan worden bij de beschrijving van de informatie, en dat gebeurt in informatiemodellen. We onderkennen twee lagen: het Conceptueel informatiemodel en het Logisch informatie of -gegevensmodel. Het conceptuele niveau is onafhankelijk van de operationele informatiesystemen, de beschrijving van hoe informatie door deze systemen worden vastgelegd en gebruikt gebeurt op het niveau van de logische informatiemodellen. 

### Conceptueel Informatiemodel Energietransitie 
Overgenomen uit https://docs.geostandaarden.nl/mim/mim/#wat-is-een-informatiemodel:  
Wanneer we informatie over bepaalde onderwerpen willen inwinnen, registreren of uitwisselen, dan is het van belang om deze informatie eerst goed te beschrijven. We doen dit zodat het voor eenieder die met de informatie aan de slag gaat helder en eenduidig is:
* waarover de informatie gaat, bv. informatie over een persoon of een gebouw, we noemen dit de objecten, de onderwerpen van gesprek
* de eigenschappen/kenmerken zelf, waarvan we informatie bijhouden, bv. de naam van een persoon of het bouwjaar van een gebouw
* wat de betekenis is van die informatie, de semantiek
* hoe deze informatie qua structuur in elkaar zit, qua onderlinge relaties en qua interne structuur van de data
We doen dit door een model te maken van de informatie. Een Informatiemodel beschrijft daarom de structuur, semantiek en de eigenschappen van informatie over dingen in de werkelijkheid. De beschrijving van de informatie heeft de vorm van een model dat een gestructureerde weergave is van die werkelijkheid. Een dergelijk model is noodzakelijk om deze informatie te kunnen beheren en gebruiken (door mensen en machines) bij het communiceren over deze werkelijkheid, in registraties of anderszins, zoals het specificeren van de tussen registraties uit te wisselen gegevens of van de te bevragen informatie uit een registratie.
Het beschrijven vindt plaats door de informatie van de objecten die we beschouwden te modelleren, met hun kenmerken en hun onderlinge relaties. We gebruiken daarvoor termen als objecten, objecttype, atttribuut, attribuutsoort, relatie, relatiesoort. Hiermee kunnen we de werkelijke data beschrijven. 

<figure id="Vivet Conceptueel Informatiemodel Framework">
<img src="media/Vivet_CIM_Framework.png" alt="">
<figcaption>Vivet Conceptueel Informatiemodel Framework</figcaption>
</figure>
 
Het Vivet Conceptueel InformatieModel (CIM) framework heeft een gelaagde structuur, en hiermee is het verbonden met de informatiemodellen van de Nederlandse overheid (de bovenste laag van dit model). Een belangrijk onderdeel hiervan zijn de basisregistraties, die zich baseren op (of: de eigenschappen overnemen van) de bovenste laag. 
Het z.g. Generiek Informatiemodel Energietransitie op zijn beurt is gebaseerd op de eigenschappen van de basisregistraties. 
In de praktijk betekent dit, dat de eigenschappen van begrippen die bekend zijn in de basisregistraties (zoals ‘Adres’, ‘Persoon’) ook in het Generiek Informatiemodel Energietransatie worden gebruikt. De eigenschappen worden ‘overerfd’. Het generieke aspect doelt op het overerven van de eigenschappen naar de informatiemodellen van specifieke energietransitie-toepassingen of -projecten (zoals hierboven bij voorbeeld Informatieportalen). 
Op deze manier ontstaat een bouwwerk met samenhangende onderdelen dat een deel van de versplintering van het informatrielandschap opheft en robuustheid voor de toekomst creëert. Met nadruk moet hier genoemd worden dat de dynamiek van de energietransitie betekent dat dit gebouw onderhoud behoeft en voortdurend aangepast moet worden aan nieuwe eisen die gesteld worden aan de energie-informatievoorziening. 
Het Vivet Conceptueel InformatieModel (CIM) Framework heeft een gelaagde structuur, en hiermee is het verbonden met de informatiemodellen van de Nederlandse overheid (de bovenste laag van dit model). Een belangrijk onderdeel hiervan zijn de basisregistraties, die zich baseren op (of: de eigenschappen overnemen van) de bovenste laag.

### Methodologisch framework

Datastandaarden zorgen voor de consistentie en uitwisselbaarheid van data. Met datastandaarden kunnen verschillende informatieproducten elkaar begrijpen en tegen elkaar praten. Zoals omschreven in de withpaper  "Vinden en verbinden met taal" [REFERENTIE Paper Danny], wordt de betekenis van data steeds belangrijker. De betekenis van data komt voort uit taal en taal bestaat uit begrippen met definities. Om taal te kunnen definiëren moet men gebruik maken van een taalinfrastructuur. Centraal binnen een taalinfrastrctuur, staat het woordenboek. 

<figure id="Taalnfrastructuur_Vinden_en_verbinden_met_taal">
<img src="media/Taalnfrastructuur%20Vinden%20en%20verbinden%20met%20taal.png" alt="">
<figcaption> Taalnfrastructuur zoals omschreven in "Vinden en verbinden met taal"</figcaption>
</figure>

Om de taal uit een domein consistent en uitwisselbaar te maken, zijn taalstandaarden noodzakelijk. Veelboorkomende keuzes voor standaarden zijn UML, zoals MIM [REFERENTIE], of het gebruik van Linked Data standaarden zoals SKOS [REFERENTIE]. De samenhang tussen deze standaarden valt terug te vinden op het niveau van begrippen. MIM maakt onderscheid in 4 verschillende niveaus van informatiemodellen, waarbij niveau 1 een model van begrippen is. Een model van begrippen beschrijft de werkelijkheid binnen het beschouwde domein  door middel van de daarin gehanteerde begrippen en hun relaties tot elkaar. Wanneer de taal die deze werkelijkheid omschrijft niet is gedefinieerd, dan is het ook lastig om een informatiemodel van een hoger niveau te maken, dat dichter bij een digitale registratie staat. MIM kan niet worden toegepast op een model van niveau 1 volgens [IM 1.1 specificatie](https://docs.geostandaarden.nl/mim/mim/#typen-informatiemodellen), maar Linked Data wel.

<figure id="informatiemodel_plaatje_MIM">
<img src="media/informatiemodel%20plaatje%20MIM.png" alt="">
<figcaption> Omschrijving van de samenhang tussen de werkelijkheid, informatiemodellen en Digitale registraties zoals omschreven door MIM.</figcaption>
</figure>

De belangrijkste Linked Data standaard voor het definiëren van woordenboeken is SKOS (Simple Knowledge Organization System). Het is een standaard van het W3C waarmee woorden in een thesaurus worden gedefinieerd. Het staat ook op de “pas toe, leg uit” lijst van standaarden van Forum Standaardisatie en is daarmee verplicht voor overheidsorganisaties. Een thesaurus is te zien als een woordenboek waaraan meer structuur is gegeven door ook relaties tussen begrippen aan te brengen. Begrippen kunnen meer specifiek of meer algemeen zijn dan andere begrippen of een meer algemene relatie hebben tot andere begrippen. Begrippen worden uniek geïdentificeerd door een URI (uniform Resource Identifier). Dat ziet er uit als het adres van een website en de definitie van een begrip is idealiter ook echt als zodanig toegankelijk via een web browser. 

De internationale Findable, Accessible, Interoperable, and Re-usable [(FAIR)-principes](https://www.pldn.nl/wiki/FAIR) zijn richtlijnen voor de manier van beschrijven, opslag en publicatie van wetenschappelijke data. De principes dienen als richtlijn om wetenschappelijke data geschikt te maken voor hergebruik onder duidelijk beschreven condities, door zowel mensen als machines. Het idee is dat de verschillende domeinen op basis van de FAIR principes eigen standaarden ontwikkelen. Sinds de publicatie van de FAIR-principes worden deze inmiddels ook gezien als toepasbaar op software, workflows en wetenschappelijke diensten. Dit maakt de fair principes ook toepasbaar op de software die gebruikt wordt om taalstandaarden te ontsluiten, zoals bijvoorbeeld het Begrippenmodel Warmte.

<figure id="FAIR_Principes">
<img src="media/FAIR.jpg" alt="">
<figcaption> Visualisatie van de FAIR principes</figcaption>
</figure>

    DiSGeo en visie architectuur zie ppt Ruud van Rossem (op U-schijf)  


Vraag van Jeroen: refereren aan <https://www.noraonline.nl/wiki/Gegevensbeschrijvingen/Handreiking>?



### Onderzoekmethode

Het doel van VIVET project VIII Data ontsluiten houdt in:
```
 Basiscondities scheppen om op een efficiënte manier en zonder exponentiële kostenstijging, gemeenschappelijk data te kunnen delen voor de energietransitie en hiermee de Vivet projecten te ondersteunen en te verbinden. Ook legt het de basis voor samenwerking inzake toekomstig onderhoud en beheer van de informatieverbindingen binnen het energiedomein en met andere domeinen of aandachtsgebieden als de bouw- en installatiewereld. Het realiseren van een community van energie informatie-experts van de stakeholders is hiervan een essentieel onderdeel.
 ```
Uit het "Methodologisch framework", staat omschreven dat taalstandaarden aan de basis liggen van datastandaarden. Één van de meest basale basiscondities om op een efficiënte manier en zonder exponentiële kostenstijging, gemeenschappelijk data te kunnen delen, zou dus kunnen liggen bij taalstandaarden. Het onderzoek om te komen tot de meest basale basisconditie valt op te delen in 3 fases:

1. De eerste fase is een verkenning van het domein. 
2. Vervolgens zijn de bevindingen uit de verkenning geanalyseerd om zo tot een kernprobleem te komen.
3. De oplossing is iteratief en in samenwerking met het werkveld uitgewerkt.

#### Verkenning domein

<figure id="Situatieschets_samenvatting">
<img src="media/situatieschetsStap1.PNG" alt="">
<figcaption>Een samenvatting van de verkenning van het energiedomein.</figcaption>
</figure>

In de eerste fase ging het om het vormen van een zo helder mogelijke schets van de situatie. Door de versnippering en omvang van het energielandschap, bleek dat er meer focus nodig was om tot de zoektocht naar de meest basale basisconditie te kunnen identificeren. 

<figure id="Focusgebied_samenvatting">
<img src="media/scopeAfbakeningStap2.PNG" alt="">
<figcaption>Focus werd gelegd op de warmtesector.</figcaption>
</figure>

Aangezien de warmtesector naar voren kwam als het meest ongegonnen gebied, werd hier de focus op gelegd. De eerste verdiepingsslag binnen de warmtesector, bestond uit het van opvragen van informatiemodellen. Dit leidde tot weinig resultaten er bleek nog weinig materiaal te zijn op het gebied van datastandaarden binnen de warmtesector. Vervolgens heeft Geonovum gesproken met partijen uit het werkveld om de schets te verhelderen. Er zijn onder andere gesprekken gevoerd met Stichting warmtenetwerk, de Warmtesector via Energie Nederland, CBS en Overheidspartijen zoals: RVO, ECW en PBL. 

#### Samenvatting bevindingen uit de verkenning: analyse van het kernprobleem

<figure id="Bevindingen_samenvatting">
<img src="media/probleemschetsStap3.PNG" alt="">
<figcaption>Analyse van de meest basale basisconditie voor standaardisatie binnen de warmtesector.</figcaption>
</figure>

Uit gesprekken met verschillende partijen die opereren binnen de warmte sector is gebleken dat het ontbreken van een eenduidige taalstandaard kan worden aangewezen als de meest basale basisconditie om op een efficiënte manier en zonder exponentiële kostenstijging, gemeenschappelijk data te kunnen delen. De bevindingen worden verder toegelicht in [hoofdstuk 2](https://geonovum.github.io/VIVET-Werkomgeving/VIMET-VIII-B/#hoofdstuk-resultaten-landschapsverkenning-warmtewereld). Binnen het warmtedomein bleek er een grote bereidheid tot medewerking, Het probleem werd door alle parijen erkend en gezien als een grote taak.

Aan de verschillende partijen binnen de warmtesector, heeft Geonovum gevraagd wat de reeds bestaande taalstandaarden zijn binnen het Warmtedomein, zodat deze konden worden geanaliseerd. Het doel van de analyse was om verschillen tussen verschillende taalstandaarden zichtbaar te maken. Om dit doel te bereiken moest een passende methodiek worden gekozen. Deze methodiek moet aansluiten op het methodologische framework van Geonovum, zodat gebruik kon worden gemaakt van de bestaande infrastructuur om begrippen iteratief met het werkveld te kunnen delen. Het Geonovum VIVET team koos daarom om aan te sluiten bij de methodiek van Doorontwikkeling in Samenhang van de Geo Basisregistraties (DiS GEO). Op basis van deze methodiek werd besloten een Begrippencatalogus voor de Warmtesector te ontwikkelen, waarin alle verschillen tussen bestaande taalstandaarden zichtbaar worden. Een aantal voorbeelden van bestaande taalstandaarden zijn: de Warmtewet, de Europese regelgeving en de NEN7125.

#### Iteratief en samen met het werkveld werken naar een oplossing

<figure id="Iteratief_samenwerken_samenvatting">
<img src="media/planNaarCommunityStap4.PNG" alt="">
<figcaption>De weg naar een actieve warmtecommunity met een gemeenschappelijke taal.</figcaption>
</figure>

Om het werkveld zo dicht mogelijk te betrekken bij de onwikeling, was het belangrijk de ontwikkeling van de Begrippencatalogus Warmte voor het werkveld zo transparant en tastbaar mogelijk te organiseren. Een eerste versie van de Begrippencatalogus werd sinds begin januari 2021 beschikbaar gesteld aan het werkveld. De Begrippencatalogus Warmte wordt sinds toen in een iteratief proces in samenwerking met het werkveld uitgebreid. In dit stadium wil Geonovum verschillende belanghebbende bij elkaar brengen, pilots doen met bestaande informatieproducten binnen het werkveld.

In de toekomst wil Geonovum dit iteratieve proces voortzetten. Bij dit proces horen stappen richting harmonisatie van begrippen en zullen vragen rondom de governance van de Begrippencatalogus worden beantwoord. Door deze cyclische verbeteringen door te zetten, hoopt Geonovum de vorming van een actieve warmte-begrippencommunity te stimuleren. Deze community zou in de toekomst kunnen evalureren naar een warmte-standaardisatiecommunity. Deze community zou kunnen bijdragen aan de ontwikkeling van informatiestandaarden binnen het warmtedomein.

### Applicatie voor de Begrippencatalogus Warmte

Er zijn allerlei tools beschikbaar voor het werken met SKOS. Voor het Begrippenmodel Warmte heeft het VIVET Team ervoor gekozen om de methodiek van DiS Geo te volgen, zodat gebruik kon worden gemaakt van bestaande infrastructuur. Deze infrastructuur bestaat uit een Beheer- en ontwikkelomgeving en een publicatieomgeving.

#### Beheer- en ontwikkelomgeving

TO DO:
Kort beschrijven welke typen tools hievoor bestaan? Waarom gekozen voor vocbench?
#### Publicatieomgeving

TO DO:
Voor het uitwisselen van data is het tegenwoordig logisch om deze via API’s te ontsluiten. Dat geldt ook voor woordenboeken. Een woordenboek API kan in allerlei applicaties worden gebruikt om woorden en hun definitie op te halen.
Aanwezige functionaliteit, gemaakte keuzen

-   beheeromgeving

Aanwezige functionaliteit, gemaakte keuzen
