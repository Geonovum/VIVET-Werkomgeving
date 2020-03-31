## Conclusies en aanbevelingen

In dit hoofdstuk worden de belangrijkste conclusies uit de voorgaande hoofdstukken uitgelicht, en wordt een aantal aanbevelingen gedaan voor een eventuele vervolg.

### Conclusies

De belangrijkste conclusies

#### Er is al veel data beschikbaar

Uit de voorgaande hofdstukken blijkt dat er al heel veel data beschikbaar is. Deze data is en wordt verzameld vanuit verschillende invalshoeken. Zo wordt door de installatiebranche data verzameld die alles te maken heeft met het beheer en onderhoud van installaties bij klanten. En wordt vanuit andere organisaties  weer met een heel andere bril naar de data gekeken. Er is data over de installaties zelf, maar ook data die meetwaarden bevat 

#### Er zijn veel verschillende partijen betrokken

Uit het hoofstuk [Landschapsverkenning](#landschapsverkenning) blijkt dat er veel verschillende partijen betrokken zijn bij het verzamelen en gebruiken van data en informatie van de installaties. Sommige partijen hebben de data nodig voor hun dagelijkse werk, en andere partijen gebruiken de ingewonnen data van andere partijen voor het afleiden van statistieken en trends.

#### Er zit overlap in de datamodellen

Kijkend naar de datamodellen ontstaat een zelfde beeld. De datamodellen zijn gemaakt voor het doel dat zij dienen. Ook is er een overlap te zien, wat heel logisch is omdat dezelfde objecten (installaties, meetwaarden, leeftijden) in beschouwing worden genomen. Ook wil een zelfde naam voor iets niet zeggen dat er ook hetzelfde mee bedoeld wordt...

#### Er zit verschil in de datamodellen

Ook zit er verschil in de datamodellen, en in de data en informatie. Zo zijn vastleggingsmodellen anders dan de informatiemodellen. Ergens tussen data en informatie vindt een bewerking of berekening plaats.

#### Welke informatievraag is er eigenlijk?

Belangrijk is het om te werken vanuit een informatievraag waar use-cases onder liggen. Als je dat niet doet ontstaat het gevaar dat er aanbod-gedeven gewerkt gaat worden, waarbij het niet duidelijk is of de vraag naar het aanbod er eigenlijk wel is.... In het speelveld "energietransitie" leven verschillende informatievragen bij verschillende organisaties. Zo zullen netbeheerders geinteresseerd zijn in de (geplande) capaciteitsvraag voor hun netwerken, zodat zij daarop kunnen anticiperen. Installateurs zijn waarschijnlijk geinteresseerd in de vervangingsvraag voor installaties bij klanten, zodat zij daarop kunnen inspelen. Overheidsorganisaties zullen vooral willen weten of zij aan de CO2 doelstellingen voldoen.  

### Aanbevelingen

#### Werk vanuit Use-Cases

Het is belangrijke om de juiste informatievraag te beantwoorden, en werken vanuit een usecase zorgt ervoor dat die inormatievraag helder wordt. Ook wordt de doelgroep voor de informatievraag duidelijk.
als ..... - wil ik .... - zodat ik ....

#### Harmoniseer de begrippen en datamodellen

Juist omdat er zoveel partijen betrokken zijn bij de energietransitie, en er zoveel verschillende informatievragen zijn, en er al zoveel verschillende data- en uitwissel modellen zijn, is het aan te bevelen om te werken vanuit een centraal begrippenkader, en vanuit een centrale data (model) repository. Dit voorkomt begripsverwarring, en het voorkomt het opnieuw uitvinden van het wiel. De definties en begrippen in de centrale repository moeten dan wel worden geharmoniseerd, met andere woorden de definite van een begrip is eenduidig, en wordt gedragen door alle betrokken partijen.  

#### Maak waar mogelijk gebruik van reeds bestaande registers

Een goede basis om te starten zijn de reeds bestaande registers, en dan meer specifiek, de BAG en de BGT. Door aan te haken en aan te sluiten op die registers, worden de objecten die gerelateerd zijn aan de energietransitie meteen voorzien van een goede locatie, een goed adres, en voorzien van een uniek ID. Dit unieke ID wordt ook reeds in andere registraties (bijvoorbeeld bij netbeheerders) gebruikt. Daarmee wordt het mogelijk om de informatie uit die andere registraties meteen te gebruiken. Belangrijk is wel om het juiste object uit BAG/GBT te keizen waarop wordt aangesloten (BAG-ID of Pand-ID, ob VerblijfsObject-ID)

#### Maak waar mogelijk gebruik van bestaande interfaces

Hetzelfde als voor bestaande registers geldt ook voor bestaande interfaces. Het is beter te starten met iets dat er al is, dan helmaal opnieuw te beginnen. Een goede kandidaat is ESDL, omdat dit een simpel model is, bestaande uit een vijftal uitwissel objecten. Getoetst moet worden of het model niet te simpel is, immmers alle benodigde data moet wel uitgewisseld kunnen worden. Voor de interfaces van en naar BAG en BGT is het aan te raden om gebruik te maken van de reesds bestaande API's zoals [hier](https://bag.basisregistraties.overheid.nl/restful-api/-/article/basisregistraties-adressen-en-gebouwen-bag-#/paths/~1panden/get) beschreven. 

#### Think Big, Act Small

Begin klein, maar denk wel aan het grotere geheel. Neem 1 of 2 objecten, werk die uit, en leer en doe ervaring op gedurende dat traject. De "energietransitie" is een dermate groot onderwerp dat het gevaar bestaat om teveel tegelijk op te pakken. Aanbevolen wordt om klein te beginnen, liefst met de belangrijkste informatievraag, en van daaruit verder te bouwen aan het informatiemodel en de onderliggende datamodellen.

#### Doe een vervolgonderzoek

Doe, om de vorige paragraaf handen en voeten te geven, een vervolgonderzoek of een PoC. Maakt die zo concreet mogelijk.
