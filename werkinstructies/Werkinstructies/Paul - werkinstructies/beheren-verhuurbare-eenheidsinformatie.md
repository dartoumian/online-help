
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
	 - Woningwaardering voor *zelfstandig woonruimtes*, conform het beleidsboek waarderingsstelsel zelfstandige woonruimte; 
	 - Woningwaardering voor *onzelfstandige woonruimtes*, conform het beleidsboek waarderingsstelsel onzelfstandige woonruimte. 

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
	 - **Beschermd stads- of dorpsgezicht**: indicatie of voor de OG Eenheid beschermd stads- of dorpsgezicht van toepassing is. Zo ja, dan wordt de maximale huurprijs van de OG Eenheid verhoogd met het percentage dat is ingesteld in de **Woningwaarderingparameterset** die van toepassi is op de ingangsdatum van de Woningwaardering. 
	 - **Oppervlakte van vertrekken**: oppervlakte van de ruimtes van de zelfstandige woonruimte die conform het beleidsboek mogen worden beschouwd als vertrekken. Klik op de drie puntjes in het veld **Totale opp. vertrekken**, selecteer één of meer vertrekken en vul per vertrek de oppervlakte van het vertrek conform het beleidsboek in. In het geval van een badkamer waarin een toilet aanwezig is, vink dan de indicatie **Toilet in vertrek** aan.   
	 - **Oppervlakte overige ruimtes**: oppervlakte van de ruimtes van de zelfstandige woonruimte die conform het beleidsboek moeten worden beschouwd als overige ruimtes. Klik op de drie puntjes in het veld **Totale opp. ruimtes**, selecteer één of meer overige ruimtes en vul per overige ruimte de oppervlakte van de ruimte conform het beleidsboek in. 
	 - **Verwarming**: aantal verwarmde vertrekken en overige ruimtes. In het geval van aansluiting op een warmtenet geldt een andere puntentelling. Vul het aantal verwarmde vertrekken en het aantal verwarmde overige ruimtes in. Vink indicatie armewet vanpassingn** is als de woonruimte is aangesloten op een warmtenet.En 
	 - **Energieprestatie**:  de energieprestatie van de woonruimte uitgedrukt in termen van een energie-index of EPA-label. Als de energieprestatie is afgemeld na 1-1-2015, selecteer dan de energiewaardering **Energie-index** en vul de waarde in het veld **Energie-index** in. In het geval de corporatie een energieprestatievergoeding in rekening brengt aan de huurder, selecteer dan de indicatienergie-.prestatievergoeding**. In dat geval krijgt de zelfstandige woonruimte het aantal energiepunten dat conform de wet van toepassing en dat in Dynamics Empire is ingesteld in de **Woningwaarderingparameatersets** 
	 - **Keuken**: het aantal punten voor de keuken wordt bepaald door de lengte van het langste aanrechtblad en eventueel aangevuld met extra kwaliteitspunten. Klik op de drie puntjes in het veld **Langste aanrecht (m)** en selecteer de waarde die van toepassing is op de keuken van de zelfstandige woonruimte. Klik op de drie puntjes in het veld **Kwaliteitspunten keuken** en selecteer de kwaliteitsaspecten die van toepassing zijn op de keuken van de zelfstandige woonruimte. 
	 - **Sanitair**: het aantal punten voor het sanitair wordt bepaald door het aantal  sanitairgelegenheden en eventueel aangevuld met extra kwaliteitspunten. Vul het aantal toiletten, wastafels, douches en baden in dat aanwezig is in de zelfstandige woonruimte. Klik op de drie puntjes in het veld **Kwaliteitspunten sanitair** en selecteer de kwaliteitsaspecten die van toepassing zijn op het sanitair van de zelfstandige woonruimte. 
	 - **Woonvoorziening voor gehandicapten**:  het aantal punte
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
eyJoaXN0b3J5IjpbMTc5NTIzODIwNywtNzEyMjY4NTA1LDQ4MD
Q4MTY2NSw0MDg0NTkyMjYsMTg0MDcwODMyMCw1MTEyNjQ3NjIs
LTE2NTI5ODE5ODFdfQ==
-->