# Verwerken inkoopfacturen


## Omschrijving:
In dit werkproces worden de ontvangen inkoopfacturen gecontroleerd, gecodeerd en geboekt.

## Processchema


## Boeken verplichting
Zodra de algemene factuurgegevens in uw systeem geregistreerd zijn kan de betalingsverplichting geboekt worden. Voorafgaand aan deze boeking kunnen de gegevens op de factuurkop gecontroleerd en aangevuld worden. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Inkoopfacturen**. Stel een filter in op het veld **Boekstatus** = '**Ongeboekt'**. De pagina toont nu een overzicht van de facturen waarvoor de verplichting nog niet geboekt is.
2. Open één van de facturen door op het nummer te klikken. De pagina **Inkoopfactuur** opent. Klik op **Factuur tonen** om de factuur te openen in DMS. De factuur wordt geopend in DMS. 
3. Controleer de volgende velden en pas waar nodig de gegevens aan:
	- **Leverancier**
	- **Boekingsdatum**: **LET OP!** Wanneer u de boekingsdatum aanpast wordt ook de documentdatum aangepast. De documentdatum dient u weer terug te zetten naar de op de factuur vermelde datum. 
	- **Documentdatum**
	- **Factuurnr. leverancier**
	- **Omschrijving**: **LET OP!**. Dit is niet de omschrijving die mee komt op de grootboekposten. Deze omschrijving wordt opgegeven in de factuurregels. 
	- **Factuurbedrag**
	- **Verl. BTW-productboekingsgroep**: De betalingsverplichting van de factuur wordt geboekt o.b.v. de gegevens op de factuurkop. Wanneer verlegde BTW van toepassing is wordt bij het boeken van de verplichting al af te dragen BTW geboekt. In dit veld geeft u aan met welke BTW-productboekingsgroep de verlegde BTW o.b.v. de factuurkop geboekt dient te worden.  Het BTW- bedrag dat geboekt wordt is het bedrag uit het veld **Factuur BTW-bedrag**.  Als zowel hoog als laag tarief BTW van toepassing is op de factuur selecteert u hier de BTW-productboekingsgroep voor hoog tarief. Nadat de BTW per factuurregel gespecificeerd is en de factuur definitief geboekt is, wordt de BTW-post o.b.v. de verplichting tegengeboekt en worden nieuwe BTW-posten aangemaakt o.b.v. de factuurregels. 
	- **Factuur BTW-bedrag**: Wanneer het veld **Verl. BTW-productboekingsgroep** gevuld is wordt dit bedrag aan verlegde BTW geboekt wanneer u de verplichting boekt. 
	- **Bedrag naar G-rekening**
 4. Nadat u bovenstaande gegevens gecontroleerd en aangevuld heeft boekt u de verplichting door op **Boeken verplichting** te klikken. De **boekstatus** van de factuur wijzigt naar '**Verplichting geboekt'**.
5. Nadat de verplichting geboekt is dienen de factuurregels aangemaakt te worden:
	-  Als er al **factuurregels aanwezig** zijn, ga dan verder met **[Controleren factuurregels](#controleren-factuurregels)**.
	- Als er een **ordernummer vermeld** staat op de factuur, ga dan verder met **[Regels ophalen](#regels-ophalen)**.
	- AIs er **geen ordernummer vermeld** staat op de factuur:
		- Had er wel een ordernummer op de factuur moeten staan, ga dan verder met **[Toewijzen factuur](#toewijzen-factuur)**.
		- Wanneer er geen order als basis voor de factuur nodig is dient u de factuur handmatig te coderen. Ga in dat geval verder met **[Coderen factuurregel(s)](#coderen-factuurregel(s))**.
		
## Regels ophalen
 
1. Heeft de order betrekking op reparatie- of mutatieonderhoud, ga dan verder met **[Ophalen orderregels reparatie- en mutatieonderhoud](#ophalen-orderregels-reparatie--en-mutatieonderhoud)**.
 2. Dienen er voor de order ontvangstregels opgehaald te worden, ga dan verder met **[Ophalen ontvangstregels](#ophalen-ontvangstregels)**.
 3. Betreft het een order die geen betrekking heeft op reparatie- of mutatieonderhoud en hoeven er ook geen orderregels opgehaald te worden voor de order (bijvoorbeeld voor orders uit de projecten- en planmatigonderhoud administrate), ga dan verder met **[Ophalen overige orderregels](#ophalen-overige-orderregels)**.

### Ophalen orderregels reparatie- en mutatieonderhoud

Voor facturen die betrekking hebben op reparatie- en mutatieonderhoud en die niet verwerkt zijn via de KOVRA- koppeling of via het leveranciersportaal, dient de kostenspecificatie via de factuur gevuld te worden. Op basis van de kostenspecificatie worden de factuurregels aangemaakt. 

1. Klik op de pagina **Inkoopfactuur** op **Onderhoudsorders zonder kostenspecificatie ophalen**. De pagina **Te factureren onderhoudsorders** opent. 
2. Zoek het ordernummer dat op de factuur vermeld staat. Wanneer dit nummer niet op te halen is, betekent dit in veel gevallen dat de onderhoudsorder nog niet gereed gemeld is. Ga verder met **[Toewijzen factuur](#toewijzen-factuur)** om de factuur toe te wijzen aan de persoon die actie dient te ondernemen.  
3. Selecteer de regel met het juiste ordernummer en klik op **Kosten-/taakspecificatie**. De pagina **Kostenspecificatie** opent. U kunt in dit scherm de benodigde informatie aanvullen (BTW- type, bedragen en/of aantallen). 
4. Klik op **OK** om de kostenspecificatie definitief te maken.  U keert terug naar de pagina **Te factureren onderhoudsorders**. Hier wordt een melding getoond die aangeeft dat de orderregels opgehaald zijn in de factuur. Klik op **Sluiten.**
5. U keer terug naar de pagina inkoopfactuur. Ga verder naar processtap **[Controleren factuurregels](#controleren-factuurregels)**.


### Ophalen ontvangstregels

Voor orders waarvoor ontvangstregels geboekt moeten worden dienen de ontvangstregels opgehaald te worden in de factuur. 

1. Klik op de pagina **Inkoopfactuur** op **Ontvangstregels ophalen**. U vind deze knop onder de FastTab **Regels**. De pagina **Ontvangstregels ophalen** opent. 
2. Zoek het ordernummer dat op de factuur vermeld staat op. Wanneer het ordernummer op de factuur niet op te halen is betekent dit in veel gevallen dat de ontvangst nog niet geboekt is. Ga verder met **[Toewijzen factuur](#toewijzen-factuur)** om de factuur toe te wijzen aan de persoon die actie dient te ondernemen.  
3.  Selecteer de ontvangstregel(s) met het juiste ordernummer(s) en klik op **OK**. De factuurregels worden aangemaakt op basis van de ontvangstregels. Ga verder naar **[Controleren factuurregels](#controleren-factuurregels)**.

### Ophalen overige orderregels

Voor orders waarvoor geen ontvangstregels geboekt hoeven te worden dienen 'reguliere' orderregels opgehaald te worden. 

1. Klik op de pagina **Inkoopfactuur** op **Orderregels ophalen**. De gelijknamige pagina opent. 
2. Zoek het ordernummer op dat op de factuur vermeld staat. Als dit niet lukt kan dit betekenen dat het werk nog niet gereed gemeld is. Ga verder met de stap **[Toewijzen factuur](#toewijzen-factuur)** om de factuur toe te wijzen aan de persoon die actie dient te ondernemen.  
3.  Selecteer de orderregel(s) met de juiste ordernummer(s) en klik op **OK**. De factuurregels worden aangemaakt op basis van de orderregels. Ga verder naar processtap **[Controleren factuurregels](#controleren-factuurregels)**.

## Coderen factuurregel(s)

Als er geen order beschikbaar is voor de factuur en er had ook geen order aangemaakt hoeven te worden, kan de factuurregel handmatig aangemaakt en ingevuld worden. Wanneer er vragen zijn over de te selecteren waarden, bijvoorbeeld op welke grootboekrekening de factuur geboekt dient te worden of welke afdelingsdimensie geselecteerd dient te worden, verzamel dan eerst deze informatie door de factuur toe te wijzen aan de persoon die de informatie kan verschaffen, via **[Toewijzen factuur](#toewijzen-factuur)**. 

> Wanneer u meerdere factuurregels aan wilt maken kunt u de factuurregels ook bewerken in Excel. 
> 1. Selecteer één of meer factuurregels. Kopieer de regels (met Ctrl+C) en plak deze (Ctrl+V) regels in een Excel-bestand.
> 2. Voer onderstaande stappen uit voor alle regels.
> 3. Selecteer de regels in het Excel-bestand (zonder de kopregel). Selecteer een lege factuurregel in de factuur, kopieer en plak de regels en plak ze terug in de factuur.

1. Wanneer alle benodigde informatie beschikbaar is kan de factuurregel gevuld worden. Vul de volgende velden:
	- **Soort**: Kies in geval van S&V-facturen voor 'Kostencode'. In geval van reguliere kosten kiest u 'Grootboekrekening'.
	- **Nr.**: Selecteer het grootboekrekening nummer of de kostencode (in geval van S&V-facturen). 
	- **Omschrijving**
	- **Btw-productboekingsgroep** 
	- **Clusternummer**: Vullen wanneer van toepassing. Als 'Kostencode' geselecteerd is in het veld **Soort** is dit veld verplicht. 
	- **Eenheidsnummer**: Vullen wanneer van toepassing.
	- **S&V afrekenbatch**: Selecteer de afrekenbatch waar de S&V-service en verbruikskosten op van toepassing zijn (alleen invullen bij S&V-facturen).
	- **Directe kostprijs Excl. btw**: Regelprijs zonder BTW.
	- **Dimensie waarden velden**: Velden die eindigen met het woord 'code' zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld kunnen worden. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen. 
2. Wanneer de gegevens in de factuurregel gevuld zijn kan de factuur gematcht en geboekt worden via **[Match en boek factuur](#match-en-boek-factuur)**.

## Controleren factuurregels

Wanneer factuurregels aangemaakt zijn op basis van KOVRA, vanuit het leveranciersportaal, op basis van orderregels of op basis van ontvangstregels, kunnen de factuurregels gecontroleerd worden. 

1. Het kan zijn dat er al factuurregels aanwezig zijn omdat de factuur al ter goedkeuring is aangeboden en is geweigerd is. Dit kunt u zien door op **Goedkeuringen** te klikken. U ziet of er goedkeuringsposten aanwezig zijn en of deze geweigerd zijn. Is dit het geval, ga dan naar de processtap **[Behandelen geweigerde documenten ](#behandelen-geweigerde-documenten)**.
2. Controleer of het totaal bedrag van de factuurregels (**Bedrag incl. BTW** op de factuurkop) en het totaal factuurbedrag (**Factuurbedrag**)  overeenkomen:
	- **Ja**: Ga verder naar stap 3. 
	- **Nee (paar cent verschil)**: Ga verder naar stap 3.
	- **Nee (meer dan paar cent verschil)**: 
		- Is het binnen de door de organisatie vastgestelde kaders toegestaan om bedragen in de factuurregels aan te passen? Ga dan verder naar stap 3 en volg daarna naar de processtap **[Aanpassen factuurregels](#aanpassen-factuurregels)**.
		- Is het binnen de door de organisatie vastgestelde kaders niet toegestaan om bedragen in factuurregels aan te passen, bijvoorbeeld omdat er een meer- of minderwerkorder aangemaakt moet worden? Wijs de factuur in dit geval toe aan de persoon die de meer- of minderwerkorder aan dient te maken, via **[Toewijzen factuur](#toewijzen-factuur)**.
3. Controleer de volgende gegevens in de factuurregels:
	- **Nr.**: Dit betreft het grootboekrekeningnummer of de kostencode.
	- **Omschrijving**
	- **Btw-productboekingsgroep** 
	- **Directe kostprijs Excl. btw**
	- **Dimensie waarden velden**: Velden die eindigen met het woord 'code' zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld zijn. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.  
4. Wanneer alle velden gecontroleerd zijn en er zijn geen aanpassingen nodig, ga dan verder metbij de processtap **[Match en boek factuur](#match-en-boek-factuur)**.
5. Zijn er wel aanpassingen nodig, ga dan verder met de processtap **[Aanpassen factuurregels](#aanpassen-factuurregels)**. 

## Aanpassen factuurregels

Blijkt uit de voorgaande stap dat gegevens op de factuurregel aangepast mogen en moeten worden, pas dan de waarden in de desbetreffende velden aan. 

1. De volgende velden zijn nog muteerbaar nadat ze o.b.v. een order zijn aangemaakt:. 
	- **Omschrijving**
	- **Btw-productboekingsgroep**
	- **Directe kostprijs Excl. btw**
	- **Dimensie waarden velden**: Velden die eindigen met het woord 'code' zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld zijn. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.
2. Zijn andere waardes niet juist, bijvoorbeeld de grootboekrekening, kostencode of projectnummer, dan kan dit niet gecorrigeerd worden in de factuurregel maar zal de order aangepast moeten worden of moet er een nieuwe order aangemaakt worden. Wijs de factuur in dit geval toe aan de persoon die de order aan dient te passen/een nieuwe order aan dient te maken (**[Toewijzen factuur](#toewijzen-factuur)**).

## Toewijzen factuur

Wanneer er vragen zijn over een factuur, of er zijn vragen met betrekking tot (de status van) de order die ten grondslag ligt aan de factuur, of iemand dient een actie uit te voeren, dan kan er op de factuur een notitie toegevoegd worden met de vraag of verzoek tot actie. Vervolgens kan de factuur toegewezen worden aan de gebruiker die de vraag dient te beantwoorden of de actie dient uit te voeren. 

1. Klik op de pagina **Inkoopfactuur** aan de rechterkant van het scherm op **Bijlagen**. 
2. Om een vraag of verzoek toe te voegen, klik op het + -teken naast **Notities**. Het scherm **Een opmerking toevoegen** opent. Vul in dit scherm de notitie en klik op **OK** om de notitie toe te voegen. 
3. Vul op de pagina **Inkoopfactuur** in het veld **Toegewezen gebruikers-ID** de gebruiker in aan wie u de factuur toe wilt wijzen. De factuur wordt nu toegevoegd aan het bakje 'toegewezen facturen' van de desbetreffende gebruiker. 

## Behandelen toegewezen factuur

Wanneer een factuur aan u toegewezen is betekend dit dat er een vraag of verzoek tot actie is die betrekking heeft op deze factuur. 

1. Navigeer naar uw Rolcenterum (startpagina van Dynamics Empire). Klik op de tegel **Toegewezen facturen**.  De pagina toont de facturen die aan u toegewezen zijn en waarop u actie dient te ondernemen. 
2. U opent de factuur door op het factuurnummer te klikken. De pagina **Inkoopfactuur** opent. 
3. Klik op de pagina **Inkoopfactuur** aan de rechterkant van het scherm op **Bijlagen**.  De notitie(s) wordt (worden) getoond. Hier vindt u de vraag of het verzoek. 
4. Wanneer u wordt gevraagd iets te doen, bijvoorbeeld het gereed melden van een order of het boeken van ontvangsten, voer dan eerst deze acties uit. 
5. Heeft u de actie uitgevoerd of wilt u een vraag beantwoorden, klik op het + -teken naast **Notities**. Het scherm **Een opmerking toevoegen** opent. Vul in dit scherm de notitie en klik op **OK** om de notitie toe te voegen. 
6. Maak op de pagina **Inkoopfactuur** het veld **Toegewezen gebruikers-ID** leeg. Hiermee wordt de factuur weer toegewezen aan de afdeling die de inkoopfacturen verwerkt. Heeft u een vervolgvraag aan een specifiek iemand of dient iemand anders een actie uit te voeren, vul dan in het veld **Toegewezen gebruikers-ID** de desbetreffende gebruiker. De factuur wordt nu toegevoegd aan het bakje 'toegewezen facturen' van de desbetreffende gebruiker. 

## Match en boek factuur

Wanneer de factuurregels aangemaakt zijn kan het document gematcht en geboekt worden. 

1. Klik op **Match en Boek**. Eventueel wordt er een goedkeuringspost toegewezen aan een gebruiker. Dit is niet alleen afhankelijk van het overeenkomen van de factuurregels met de order- of ontvangstregels, maar ook van de steekproefinstellingen.Blijkt op basis van de instellingen dat de factuur niet meer goedgekeurd hoeft te worden, dan wordt de factuur direct geboekt. 

## Goedkeuren document

Wanneer het document goedgekeurd dient te worden verloopt dit via het werkproces GOEDKEUREN DOCUMENTEN.

## Behandelen geweigerde documenten 

Wanneer een document geweigerd is dient u de weigeringsreden te beoordelelden.

1. Vanaf de pagina **Inkoopfacturen** klikt u op **Goedkeuringen** om de geweigerde goedkeuringsposten te tonen. 
2. Klik op **Opmerkingen**. De pagina **Opmerkingen bij goedkeuring** opent. U ziet hier de reden van weigeren en wie de aanvraag geweigerd heeft.
3. Dient een andere order gekoppeld te worden, ga dan verder met stap **[Regels ophalen](#regels-ophalen)**.
4. Dient de codering van de factuurregels aangepast te worden, ga dan verder met stap **[Controleren factuurregels](#controleren-factuurregels)**.


## Boeken factuur

Wanneer het document door alle personen die het document goed moeten keuren goedgekeurd is, kan de factuur geboekt worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Inkoopfacturen**. Stel een filter in op het veld **Status** = **Vrijgegeven**. De pagina toont nu een overzicht van de facturen die vrijgegeven zijn en geboekt kunnen wordnen. 
2. Klik op **Batchboeken (verplichting)**. De pagina **Batchboeken verplichting inkoopfacturen** opent. 
3. Zet het veld **Boekstatus** op **Verplichting geboekt** e. En zet het veld **Status** op **Vrijgegeven**. 
4. Klik op **OK**. Alle facturen waarvoor dit mogelijk is worden definitief geboekt. 
5. Facturen waarbij de boekingsdatum in een afgesloten periode valt worden niet geboekt. Om deze facturen toch in batch te kunnen boeken kan bij stap 3  in het veld **Boekingsdatum** de aangepaste boekingsdatum ingevuld worden. Alle facturen binnen het filter worden dan met deze nieuwe boekingsdatum geboekt. 




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY2NzE0ODg5LDkzODYyMjY2NCwtMjA0ND
I3OTQ0MywxNDg3NjI4NTE5LDE5OTkzMTMzNDYsLTg0OTEyNjQx
NiwtNjQ1NTIwMTksNjE3Mjc4NjgwLDE5OTA0MTUxMTYsMTk1NT
g4NDk5MiwtNjgzNjcyNDcwLC0yODYwODEwNDksOTk5ODMxMDIw
LDQyMDQwMDg4Niw0ODk5ODE2NjIsMTE0OTE4MzQ5NywxNzAwOT
A1MTUyLC03ODU5NjI2NzksMTg4NTA5OTc4MywxMjA0MjY1Njgx
XX0=
-->