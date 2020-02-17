
# Beheren verhuurbare eenheidsinformatie

Binnen dit detailproces wordt informatie over verhuurbare eenheden beheerd.  Dit betreft de volgende soorten informatie: 

 - Basisinformatie  
 - Woningwaardering 
 - Streefhuur 
 - Exploitatievormen 
 - Administratief eigenaren 
 - Contactpersonen 

## Processchema
(Hier komt link naar Mavim of plaatje van proces.)

## Registreren basisinformatie verhuurbare eenheid
In deze stap registreert of wijzigt u de basisinformatie van de verhuurbare eenheid.  

 1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid waarvan basisinformatie moet worden beheerd.  
 3. Klik op het **Nr.** van de OG Eenheid. De pagina **Onroerend goed eenheidkaart** wordt geopend. 
 4. In tabblad **Algemeen** kunt u algemene basisinformatie van de verhuurbare eenheid invullen en wijzigen. De belangrijkste velden zijn: 
	- **Type**: geeft aan tot welk Eenheidstype de OG eenheid behoort. Dit bepaalt o.a. de standaardwaarde voor de velden **Vraagboomsoort**, **Aantal vooropnames**, **Duur vooropname**, **Aantal eindopnames**, **Duur eindopname** en **Termijn eerste vooropname**.  
	- **Woonruimte**: geeft aan of de eenheid een zelfstandige woonruimte is of niet. Een woonruimte is zelfstandig als het toegankelijk is via een eigen voordeur. Dit bepaalt o.a. het soort woningwaardering (d.w.z. de waarderingsmethode) dat van toepassing is voor de OG Eenheid.  
	- **Vraagboomsoort**: geeft aan via welke vraagboomsoort een reparatieverzoek kan worden ingediend op de OG Eenheid. Dit is standaard gelijk aan de vraagboomsoort die is ingesteld bij het **Eenheidstype**, maar kan daarvan afwijken. 
	- **Divisie**: geeft aan tot welke divisie de OG Eenheid behoort. Dit bepaalt o.a. via welk woonruimteverdeelsysteem (WRV-systeem) de OG Eenheid wordt gepubliceerd. 
	- **Betreft**: 
	- **Etagewoning** en **Etage**: geeft aan of de eenheid een etagewoning betreft, en zo ja, op welke etage (de voordeur van) de woning zich bevindt. 
	
 5. In tabblad **Adressen** kunt u het adres van de OG Eenheid zien en wijzigen. U wijzigt het adres door in het veld **Straat** de postcode, het huisnummer en eventueel het toevoegsel in te voeren (zonder spaties, bijvoorbeeld '1234AA33B'). Zodra u het veld verlaat, vult het systeem automatisch de velden **Straat**, **Huisnummer**, **Toevoegsel**, **Postcode** en **Plaats** is op basis van de Postcodetabel. 
 6. De de velden **Gemeente**, **CBS-wijk** en **CBS-buurt** geven aan binnen welke gemeente, CBS-wijk en CBS-buurt de OG Eenheid ligt. De waarden van deze velden worden automatisch bepaald aan de hand van de postcode en het huisnummer van de OG Eenheid (mits de CBS-data is geïmporteerd (zie: '**CBS-data importeren**')). 
 7. De velden **BAG-adres**, **BAG-postcode** en **BAG-plaats** geven het adres, postcode en plaats weer van het BAG-verblijfsobject dat is gekoppeld aan de OG Eenheid (mits een BAG-extractie is geïmporteerd). Om de OG Eenheid aan een BAG-verblijfobject te koppelen klikt u op ***Acties*** - ***BAG*** - **Verblijfobject koppelen**. 
 8. In tabblad **Exploitatie (Alg)** kunt u informatie over de exploitatie van de OG Eenheid beheren. 
 
## Aanpassen woningwaardering
In deze stap past u de woningwaardering van de OG Eenheid aan. Dit doet u door een nieuwe versie van de woningwaardering aan te maken, zodat de historie behouden blijft. Binnen Dynamics Empire worden de volgende twee wettelijke soorten woningwaarderingen ondersteund: 
	 - Woningwaardering voor *zelfstandig woonruimtes* 
	 - Woningwaardering voor *onzelfstandige woonruimtes* 

Welke soort woningwaardering van toepassing is voor de OG Eenheid, wordt bepaald door het veld **Woonruimte**. 

U kunt als volgt een nieuwe versie van de woningwaardering aanmaken voor een OG Eenheid: 
 1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid
 3. Klik op **Woningwaardering**.  Een pagina wordt geopend met details van de bestaande versie van de woningwaardering die momenteel actief is (op basis van de ingangsdatum van deze en andere versies). 
 4. Klik op **+Nieuw**, selecteer een datum in het veld **Ingangsdatum** en verlaat het veld. Een nieuwe versie van de woningwaardering wordt aangemaakt met exact dezelfde details als de versie die tot nog toe actief was op de geselecteerde ingangsdatum. Als gevolg van et aanmaken van de nieuwe versie is de vorige versie actief *tot* de ingangsdatum van de nieuwe versie. Als de ingangsdatum van de nieuwe versie gelijk is aan de ingangsdatum van de vorige versie, dan krijgt de nieuwe versie een volgnummer dat 1 hoger is dan het volgnummer van de vorige versie en is de vorige versie op geen enkele datum meer actief. 
 5. Pas daar waar nodig details van de nieuwe versie aan. 

Voor elk soort woningwaardering zijn andere soorten details van toepassing. De details van de woningwaardering hebben betrekking op die eigenschappen van de OG Eenheid die van invloed zijn op de berekening van het aantal **Totaal aantal punten afgerond**. Het aantal punten op zijn beurt bepaalt de maximale huurprijs van de OG Eenheid (zie pagina **Maximale huurprijzen**). 

Binnen de woningwaardering van een *zelfstandige woonruimte* kunt u de volgende details aanpassen: 
	 - **Beschermd stads- of dorpsgezicht**: indicatie of voor de OG Eenheid beschermd stads- of dorpsgezicht van toepassing is. Zo ja, dan wordt de maximale huurprijs van de OG Eenheid verhoogd met het percentage dat is ingesteld in de **Woningwaarderingparameterset** die van toepassing is op de ingangsdatum van de Woningwaardering. 
	 - **Oppervlakte van vertrekken**: oppervlakte van de ruimtes die conform het hand
	 - **Oppervlakte overige ruimtes**: 
	 - **Verwarming** 
	 - **Energieprestatie**: 
	 - **Keuken** 
	 - **Sanitair** 
	 - **Woonvoorziening voor gehandicapten**: 
	 - **Buitenruimte**: 
	 - **WOZ-waarde** 
	 - **Renovatie**: 
	 - **Bijzondere voorzieningen**: 

## Aanpassen streefhuur
In deze stap past u de streefhuurmethode van de OG Eenheid aan van **Statisch** naar **Dynamisch** of andersom. Als de streefhuurmethode is ingesteld op Dynamisch, kunt u het streefhuurpercentage aanpassen. Als de streefhuurmethode is ingesteld op Statisch, kunt u het streefhuurbedrag aanpassen.

1. Bla bla  

<hr>

### Aanpassen exploitatievorm
In deze stap past u de exploitatievorm van de OG Eenheid aan. U kunt een exploitatievorm koppelen of juist ontkoppelen van de OG Eenheid. Via de exploitatievorm van de OG Eenheid bepaalt u of, en zo ja, op welke manier, de OG Eenheid kan worden verhuurd of verkocht.  

1. Bla bla  

<hr>

### Aanpassen administratief eigenaar
In deze stap past u de administratief eigenaar van de OG Eenheid aan. De administratief eigenaar van de OG Eenheid bepaalt of de OG Eenheid tot het DAEB-bezit of het niet-DAEB-bezit behoort. 

1. Bla bla  

<hr>

### Aanpassen contactpersonen
In deze stap past u de contactpersonen van de OG Eenheid aan. Elke contactpersoon behoort tot een functiegroep, zoals huismeester.  

1. Bla bla  

<hr>


## Zie ook (links naar andere detailprocessen uit dezelfde procesgroep)
Werkinstructie X  
Werkinstructie Y  
Werkinstructie Z

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMzI1NzI5MjgsNTExMjY0NzYyLC0xNj
UyOTgxOTgxXX0=
-->