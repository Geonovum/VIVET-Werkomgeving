## Bevindingen, conclusies en aanbevelingen

### Scoping 
Een installatieregister (concept) is onderdeel van cross-sectoraal landschap (bouw, energie, installatie-onderhoud,
assetmanagement, basisregistraties). Het realiseren van slimme koppelingen op informatie-technisch gebied is effectiever 
dan een nieuw fysiek register opzetten. Goed gedragen usecases kunnen hier de richting aangeven.
In deze voorstudie is besloten om de scope van 'installatie' niet te beperken, juist omdat bij de uitwerking van VIVET-project E is besloten om de scoping van het 'installatieregister concept' vraaggestuurd te laten plaatsvinden. Aanbeveling bij doorontwikkeling van het informatiemodel is om een onderscheid te maken tussen installaties die gerelateerd zijn aan een energienetwerk vóór de meter en installaties die gerelateerd zijn aan een energienetwerk áchter de meter en er zijn vijf functies die gebruikt kunnen worden om installaties te identificeren: productie, opslag, conversie, transport en gebruik.

### Landschapsverkenning
Op energiegebied en bouw zijn veel digitaliserings- en data-initiatieven, ook in relatie tot installaties. Qua governance
bestaat weinig samenhang tussen Thema Digitalisering binnen Topsector Energie, VIVET, DigiDealGO, CBS, DiSGeo, WKB, 
Klimaatakkoord en Energiewet 1.0. Meer concreet is informatiekundige samenhang nodig (voor energieinstallaties) tussen
de projecten: EAN-BAG koppeling, Datastelsel Utiliteit, InstallatieRegister Techniek NL, Digitaal Bouwdossier en unieke
object identificatie.

### Analyse
VIVET heeft als doel om te werken aan het versnipperde data-landschap in het energiedomein; de versnippering heeft niet alleen
betrekking op de datasets, maar ook op de infotools (informatiemodellen, classificaties, e.d.), die vaak niet beschikbaar zijn,
slechts betrekking hebben op één dataset en verschillende niveaus van volwassenheid kennen.  
Er is behoefte aan generieke infotools die ervoor zorgen dat er één taal gesproken wordt in de verschillende domeinen;
de verduurzaming van 8 miljoen panden vraagt daarom. In deze voorstudie zijn een aantal ervan in beeld gebracht; bijvoorbeeld ESDL (TNO). 
ESDL kan hier een goede bijdrage leveren.

### Projecten en Kernentiteiten
Belangrijke kernentiteiten als Pand/Gebouw, Installatie en Meetwaarde zijn cruciaal voor uitwisseling van data over
energie-installaties en met basisregistraties en zijn nog niet geborgd in lopende projecten.

### Informatiemodellering(1)
Deze voorstudie heeft op basis van de belangrijkste informatiemodellen een globaal model opgeleverd om gegevens op het gebied
van energie en energie-installaties te verbinden. Dit framework is bruikbaar om breder binnen VIVET en de omgeving toe te passen
en om te beginnen de VIVET-projecten informatietechnisch integraal te kunnen ondersteunen en daarmee de kwaliteit van de 
informatie te verbeteren en te borgen.  
Besteed veel aandacht om informatiekundige samenhang aan te brengen in hetgeschetste landschap op het gebied van energie, bouw 
en installaties. 
[zie de aanbevelingen voor doorontwikkeling van het informatiemodel](#aanbevelingen-voor-doorontwikkeling)
    
### Informatiemodellering(2)
Het domein kan samengevat worden als het verbinden van de werelden ‘vóór de aansluiting’ en ‘achter de aansluiting’, m.a.w. 
het energiesysteem (netten, grootschalige productie) en de installatiewereld (cv-ketels, warmtepompen, elektrische installaties).
Ook datasets van bijvoorbeeld subsidieverstrekkers maken hier overigens deel van uit, zoals ook beschreven in het ‘zusterproject’
VIVET E1). Koppelvlakken tussen beide werelden lopen via gebouw(pand), adres en fysiek(topografisch) object. 
Realisatie van deze koppeling is voor een gedeelte te bereiken via brede implementatie van de Basisregistraties BAG en BGT in 
het energiedomein.
[zie de aanbevelingen voor doorontwikkeling van het informatiemodel](#aanbevelingen-voor-doorontwikkeling)
    
### Informatiemodellering(3)
De oplossing voor een toegankelijk installatieregister zal gezocht worden in een intelligente mapping van de informatiemodellen 
die de onderscheiden datasets beschrijven. De globale mapping in deze voorstudie zal daartoe verder gedetailleerd moeten worden.
Voor deze mapping zijn goede semantiekgerichte technieken beschikbaar en deels al beschikbaar, bijv. beschikbare linked data 
definities in IEC-CIM (C-AR) en CB-NL.  
Hierbij behoort ook het concretiseren van voor de hand liggende verbindingen, zoals het gebruik van BAG-ID als verbinding 
tussen verschillende datasets en domeinen.
[zie de aanbevelingen voor doorontwikkeling van het informatiemodel](#aanbevelingen-voor-doorontwikkeling)
    
### Use cases
Het bleek niet mogelijk om usecases uit te werken in het kader van deze voorstudie. Het nadenken hierover heeft echter zeker 
bijgedragen aan het resultaat omdat het de scope heeft bepaald. Het vervolg op deze studie zal gedetailleerder zijn en daarvoor
is ondersteuning bij opstellen van een goede usecase noodzakelijk. Gezien de resultaten van deze voorstudie is 
(o.a. door NP RES en PBL aan te geven) uitbreiding van de informatie voor opstellen van de TransitieVisie Warmte een goede kandidaat.

### Stakeholders
De kennismaking tussen stakeholders van verschillende domeinen (energie, installaties, overheid) verliep zeer open, betrokkenen
zagen veel kansen om verbindingen te valoriseren en zijn bereid om in de samenwerking te investeren. Voor wat betreft het 
energiedomein geldt, dat kennis en ervaringen benut kunnen worden uit de informatievoorziening in de installatiewereld waar
veel ervaring is met bijv. internationale standaardisatie en classificatiestelsels. Daarom verdient het aanbeveling om te
investeren in duurzame samenwerkingsrelaties.

### Governance
Geef aandacht aan het governance-vraagstuk: acceptatie van standaarden, classificatie en informatiemodellen is niet vanzelfsprekend.
Daartoe is actieve participatie in de in ontwikkeling zijnde afsprakenstelsels en datastelsels van groot belang.
Zorg dat er ook sturing en beheer op de samenhang van standaarden wordt belegd. In dit kader kan gedacht worden aan de publicatie
van ontwikkelde standaarden op de overheidslijst van open-standaarden ([Forum Standaardisatie: pas-toe of leg-uit-lijst](https://www.forumstandaardisatie.nl/open-standaarden))
