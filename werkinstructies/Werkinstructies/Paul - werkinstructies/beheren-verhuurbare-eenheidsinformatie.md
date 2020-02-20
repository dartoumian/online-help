
# Beheren verhuurbare eenheidsinformatie

Binnen dit detailproces wordt informatie over verhuurbare eenheden beheerd.  Dit betreft de volgende soorten informatie: 

 - Basisinformatie  
 - Woningwaardering 
 - Streefhuur 
 - Exploitatievormen 
 - Administratief eigenaren 
 - Contactpersonen 

## Processchema

## Registreren basisinformatie verhuurbare eenheid
In deze stap registreert of wijzigt u de basisinformatie van de verhuurbare eenheid.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid waarvan basisinformatie moet worden beheerd.
 3. Klik op het **Nr.** van de OG Eenheid. De pagina **Onroerend goed eenheidkaart** wordt geopend.
 4. Open een tabblad en wijzig de velden waarin de te wijzigen basisinformatie is vastgelegd.

De belangrijkste velden op tabblad **Algemeen** zijn: 

 - **Type**: Geeft aan tot welk Eenheidstype de OG eenheid behoort. Dit bepaalt o.a. de standaardwaarde voor de velden **Vraagboomsoort**, **Aantal vooropnames**, **Duur vooropname**, **Aantal eindopnames**, **Duur eindopname** en **Termijn eerste vooropname**.
 - **Woonruimte**: Geeft aan of de eenheid een zelfstandige woonruimte is of niet. Een woonruimte is zelfstandig als het toegankelijk is via een eigen voordeur. Dit bepaalt o.a. het soort woningwaardering (d.w.z. de waarderingsmethode) dat van toepassing is voor de OG Eenheid.
 - **Vraagboomsoort**: Geeft aan via welke vraagboomsoort een reparatieverzoek kan worden ingediend op de OG Eenheid. Dit is standaard gelijk aan de vraagboomsoort die is ingesteld bij het **Eenheidstype**, maar kan daarvan afwijken.
 - **Divisie**: Geeft aan tot welke divisie de OG Eenheid behoort. Dit bepaalt o.a. via welk woonruimteverdeelsysteem (WRV-systeem) de OG Eenheid wordt gepubliceerd.
 - **Etagewoning** en **Etage**: Geeft aan of de eenheid een etagewoning betreft, en zo ja: op welke etage (de voordeur van) de woning zich bevindt. 
	
Op tabblad **Adressen** kunt u het adres van de OG Eenheid als volgt invoeren of wijzigen:

1. Voer in het veld **Straat** de postcode, het huisnummer en eventueel het toevoegsel in (zonder spaties, bijvoorbeeld '1234AA33B').
2. Zodra u het veld verlaat, vult het systeem automatisch de velden **Straat**, **Huisnummer**, **Toevoegsel**, **Postcode** en **Plaats** is op basis van de Postcodetabel. 

Toelichting op de overige velden op tabblad **Adressen**: 
 - De velden **Gemeente**, **CBS-wijk** en **CBS-buurt** geven aan binnen welke gemeente, CBS-wijk en CBS-buurt de OG Eenheid ligt. De waarden van deze velden worden automatisch bepaald aan de hand van de postcode en het huisnummer van de OG Eenheid (mits de CBS-data is geïmporteerd (zie: 'CBS-DATA IMPORTEREN')). 
 - De velden **BAG-adres**, **BAG-postcode** en **BAG-plaats** geven het adres, de postcode en de plaats weer van het BAG-verblijfsobject dat is gekoppeld aan de OG Eenheid (mits een BAG-extractie is geïmporteerd). Om de OG Eenheid aan een BAG-verblijfobject te koppelen klikt u op **Verblijfobject koppelen**.  

De belangrijkste velden op tabblad **Exploitatie (Fin)** zijn: 
- **WOZ-objectnummer**: Geeft aan tot welk WOZ-objectnummer de OG Eenheid behoort.  De corporatie ontvangt jaarlijks van de gemeente per WOZ-objectnummer de nieuwe WOZ-waarde van het WOZ-object.
- **Clusterstreefhuurbepaling**, **Streefhuurmethode** en **Code streefhuur t.o.v. max huurprijs**: zie **[Aanpassen streefhuur](#aanpassen-streefhuur)**. 
- **Huurbeleid**: Dit is het beleid via welke de nieuwe nettohuur berekend wordt als onderdeel van de aanbiedhuur, d.w.z. de huurprijs die een nieuwe huurder initieel gaat betalen.
- **Huurverhogingsbeleidstype**: Het beleidstype via welke de huidige nettohuur wordt aangepast tijdens de jaarlijkse huurverhoging. Dit bepaalt o.a. per huurverhogingstijdvak met welk percentage de nettohuur wordt verhoogd. 
- **Nettohuuraftopping**: De aftopping via welke de nieuwe nettohuur wordt afgetopt tijdens de jaarlijkse huurverhoging. 

 
## Aanpassen woningwaardering
In deze stap past u de woningwaardering van de OG Eenheid aan. Dit doet u door een nieuwe versie van de woningwaardering aan te maken, zodat de historie behouden blijft. Binnen Dynamics Empire worden de volgende twee wettelijke soorten woningwaarderingen ondersteund: 
	 - woningwaardering voor *zelfstandige woonruimten*, wordt ingevuld en berekend conform het beleidsboek waarderingsstelsel zelfstandige woonruimte; 
	 - woningwaardering voor *onzelfstandige woonruimten*, wordt ingevuld en berekend conform het beleidsboek waarderingsstelsel onzelfstandige woonruimte. 

Welke soort woningwaardering van toepassing is voor de OG Eenheid, wordt bepaald door het veld **Woonruimte**. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de juiste OG Eenheid.
 3. Klik op **Woningwaardering**.  Een pagina wordt geopend met details van de bestaande versie van de woningwaardering die momenteel actief is (op basis van de ingangsdatum van deze en andere versies). 
 4. Klik op **Nieuw**, selecteer een datum in het veld **Ingangsdatum** en verlaat het veld. Een nieuwe versie van de woningwaardering wordt aangemaakt met exact dezelfde details als de versie die tot nog toe actief was op de geselecteerde ingangsdatum. Als gevolg van het aanmaken van de nieuwe versie is de vorige versie actief *tot* de ingangsdatum van de nieuwe versie. Als de ingangsdatum van de nieuwe versie gelijk is aan de ingangsdatum van de vorige versie, dan krijgt de nieuwe versie een volgnummer dat 1 hoger is dan het volgnummer van de vorige versie en is de vorige versie op geen enkele datum meer actief. 
 5. Pas daar waar nodig details van de nieuwe versie aan. 

Voor elk soort woningwaardering zijn andere soorten details van toepassing. De details van de woningwaardering hebben betrekking op die eigenschappen van de OG Eenheid die van invloed zijn op de berekening van het aantal **Totaal aantal punten afgerond**. Het aantal punten op zijn beurt bepaalt de maximale huurprijs van de OG Eenheid. 

Binnen de woningwaardering van een *zelfstandige woonruimte* kunt u de volgende details aanpassen: 
 - **Beschermd stads- of dorpsgezicht**: Zo ja, dan wordt de maximale huurprijs van de OG Eenheid automatisch verhoogd met het percentage dat is ingesteld in de **Woningwaarderingparameterset** die van toepassing is op de ingangsdatum van de Woningwaardering. 
 - **Oppervlakte van vertrekken**: oppervlakte van de ruimtes van de zelfstandige woonruimte die conform het beleidsboek mogen worden beschouwd als vertrekken. Per m2 wordt een aantal punten gerekend conform het beleidsboek. Klik op de drie puntjes in het veld **Totale opp. vertrekken**, selecteer één of meer vertrekken en vul per vertrek de oppervlakte van het vertrek conform het beleidsboek in. In het geval van een badkamer waarin een toilet aanwezig is, vink dan de indicatie **Toilet in vertrek** aan.   
 - **Oppervlakte overige ruimtes**: oppervlakte van de ruimtes van de zelfstandige woonruimte die conform het beleidsboek moeten worden beschouwd als overige ruimtes. Per m2 wordt een aantal punten gerekend. Klik op de drie puntjes in het veld **Totale opp. ruimtes**, selecteer één of meer overige ruimtes en vul per overige ruimte de oppervlakte van de ruimte conform het beleidsboek in. 
 - **Verwarming**: aantal verwarmde vertrekken en overige ruimtes. In het geval van aansluiting op een warmtenet geldt een andere puntentelling. Vul het aantal verwarmde vertrekken en het aantal verwarmde overige ruimtes in. Vink indicatie armewet vanpassingn** is als de woonruimte is aangesloten op een warmtenet.En 
 - **Energieprestatie**:  de energieprestatie van de woonruimte uitgedrukt in termen van een energie-index of EPA-label. Als de energieprestatie is afgemeld na 1-1-2015, selecteer dan de energiewaardering **Energie-index** en vul de waarde in het veld **Energie-index** in. In het geval de corporatie een energieprestatievergoeding in rekening brengt aan de huurder, selecteer dan de indicatie **Energieprestatievergoeding**. In dat geval krijgt de zelfstandige woonruimte het aantal energiepunten dat conform de wet van toepassing en dat in Dynamics Empire is ingesteld in de **Woningwaarderingparametersets** 
 - **Keuken**: het aantal punten voor de keuken wordt bepaald door de lengte van het langste aanrechtblad en eventueel aangevuld met extra kwaliteitspunten. Klik op de drie puntjes in het veld **Langste aanrecht (m)** en selecteer de waarde die van toepassing is op de keuken van de zelfstandige woonruimte. Klik op de drie puntjes in het veld **Kwaliteitspunten keuken** en selecteer de kwaliteitsaspecten die van toepassing zijn op de keuken van de zelfstandige woonruimte. 
 - **Sanitair**: het aantal punten voor het sanitair wordt bepaald door het aantal  sanitairgelegenheden en eventueel aangevuld met extra kwaliteitspunten. Vul het aantal toiletten, wastafels, douches en baden in dat aanwezig is iKlik op de drie puntjes in het veld **Langste aanrecht (m)** en selecteer de waarde die van toepassing is op de keuken van de zelfstandige woonruimte. Klik op de drie puntjes in het veld **Kwaliteitspunten sanitairkeuken** en selecteer de kwaliteitsaspecten die van toepassing zijn op het sanitairde keuken van de zelfstandige woonruimte. 
 - **Woonvoorziening voor gehandicapten**:  het aantal punten wordt bepaald door de investering die de verhuurder heeft besteed aan het geschikt maken van de zelfstandige woonruimte voor bewoning door gehandicapten. Vul de investering in het veld **Investering voorzieningen** in.   
- **Buitenruimte**:  het aantal punten wordt bepaald door de totale oppervlakte van de privé buitenruimten. Zie het beleidsboek voor de definitie van buitenruimte en voor de regels via welke de oppervlakte moet worden bepaald. Vul de oppervlakte van de verschillende buitenruimten in de desbetreffende velden in.  
 - **WOZ-waardering**: het aantal punten op basis van de WOZ-waarde van de zelfstandige woonruimte. Dit aantal punten is niet alleen afhankelijk van de WOZ-waarde van de woonruimte, maar ook van de totale oppervlakte van de vertrekken en overige ruimten, van de vraag of de woonruimte in een COROP-gebied ligt en van de wettelijke **Woningwaarderingsparameters**. Het veld **WOZ-waarde voor WWD** wordt standaard gevuld met de waarde van het veld **WOZ-waarde uit WOZ-gegevens**, welke standaard wordt gevuld met de WOZ-waarde uit de **WOZ-gegevens** van de OG Eenheid die gelden voor het jaar waarin de ingangsdatum van de woningwaardering valt. U kunt een afwijkende WOZ-waarde voor WWD invullen, mits u een **WOZ-afwijkingsreden** selecteert. 
 - **Renovatie**: punten voor renovatie worden bepaald door de hoogte van de investeringen die de verhuurder heeft gedaan. Hiervoor geldt een minimum investeringsbedrag en een maximaal aantal kalenderjaren gedurende welke punten voor renovatie mogen worden gerekend (zie hoofdstuk 10 van het beleidsboek). U vult het aantal punten voor renovatie in het veld **Punten renovatie-investering**. 
 - **Bijzondere voorzieningen**: In het geval van een zorgwoning worden conform het beleidsboek extra punten gerekend mits voldaan is aan bepaalde voorwaarden. U geeft in het veld **Zorgwoning** aan of de OG Eenheid al dan niet een zorgwoning is. Dynamics Empire rekent dan automatisch extra punten mits de OG Eenheid voldoet aan de wettelijke voorwaarden. 


Binnen de woningwaardering van een *onzelfstandige woonruimte* kunt u de volgende details aanpassen: 
	 - **Beschermd stads- of dorpsgezicht**: indicatie of voor de OG Eenheid beschermd stads- of dorpsgezicht van toepassing is. Zo ja, dan wordt de maximale huurprijs van de OG Eenheid verhoogd met het percentage dat is ingesteld in de **Woningwaarderingparameterset** die van toepassing is op de ingangsdatum van de Woningwaardering. 
	 - **Oppervlakte**:  Oppervlakte van kamers behorende uitsluitend tot de onzelfstandige woonruimte en oppervlakte van gemeenschappelijke verblijfsruimten. Per m2 wordt een aantal punten berekend conform het beleidsboek. Klik op de drie puntjes in het veld **Totaal eigen vertrekken**, selecteer één of meer vertrekken en vul per vertrek de oppervlakte van het vertrek conform het beleidsboek in. Vul de totale oppervlakte van de gemeenschappelijke ruimten in in veld **Gem. verblijfsruimte(n) (verwarmd)**. Vul het totaal aantal onzelfstandige woonruimtes die gebruik maken van de gemeenschappelijke ruimte(n) in in het veld **Per ## kamers (factor 5/##)**. 
	 - **Verwarmingsmogelijkheden**:  het aantal punten voor dit aspect wordt bepaald door de totale oppervlakte van de verwarmde eigen vertrekken, aangevuld met extra punten voor een gasaansluiting. Vul het totaal aantal m2 van de verwarmde eigen vertrekken van de onzelfstandige woonruimte in in veld **Eigen vertrekken (factor 3/4)**. Selecteer indien van toepassing de indicatie **Gasaansluiting (factor 3)**. 
	 - **Kookgelegenheid**:  het aantal punten voor dit aspect wordt bepaald door het soort en de oppervlakte van de keuken. Selecteer de waarde die van toepassing is voor de keuken van de onzelfstandige woonruimte. 
	 - **Toilet**: het aantal punten voor dit aspect wordt bepaald door de vraag of het toilet al dan niet wordt gedeeld met andere onzelfstandige woonruimten. Selecteer de waarde die van toepassing is voor het toilet van de onzelfstandige woonruimte.
	 - **Wasgelegenheid**: het aantal punten voor dit aspect wordt bepaald door de vraag of de douche of bad respectievelijk de wastafel al dan niet wordt gedeeld met andere onzelfstandige woonruimten. Selecteer de waarde die van toepassing is voor de douche/het bad resp. de wastafel van de onzelfstandige woonruimte. 
	 - **Kwaliteitsfactoren**: dit aspect heeft betrekking op de aanwezigheid van thermostatische regelknoppen op de radiatoren, buitenruimten en fietsenberging. Selecteer de waarde die van toepassing is voor de onzelfstandige woonruimte. 
	 - **Beschermd monument**:  extra punten indien de onzelfstandige woonruimte deel uitmaakt van een beschermd monument. Selecteer deze indicatie inden van toepassing. 
	 - **Aftrekpunten**: selecteer daar waar van toepassing de aspecten van de onzelfstandige woonruimte waarvoor aftrekpunten worden gerekend. 


## Aanpassen streefhuur
In deze stap past u de streefhuurmethode van de OG Eenheid aan van *Statisch* naar *Dynamisch* of andersom. Als de streefhuurmethode is ingesteld op *Dynamisch*, kunt u het streefhuurpercentage aanpassen. Als de streefhuurmethode is ingesteld op *Statisch*, kunt u het streefhuurbedrag aanpassen. 

De streefhuur van een OG Eenheid kan worden bepaald op het niveau van de individuele OG Eenheid of op het niveau van het PMC-cluster waartoe de OG Eenheid behoort. In dat laatste geval stelt u de streefhuurmethode, het streefhuurpercentage en/of het streefhuurbedrag in bij een PMC-cluster, waarna het systeem deze instellingen automatisch toepast bij alle OG Eenheden die tot dat cluster behoren. 

Per OG Eenheid bepaalt u met het veld **Clusterstreefhuurbepaling** of de streefhuur van de OG Eenheid wordt bepaald door de instellingen bij het PMC-cluster waartoe de OG Eenheid behoort, of door de instellingen bij de OG Eenheid zelf. 

U kunt als volgt de streefhuur van een OG Eenheid aanpassen: 
 1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid
 3. Open tabblad **Exploitatie (Fin.)**.  
 4. Als de indicatie **Clusterstreefhuurbepaling** is aangevinkt, dan wordt de streefhuur van de OG Eenheid bepaald door de instellingen bij het PMC-cluster waartoe de OG Eenheid behoort. Als deze indicatie is uitgevinkt, kunt u de instellingen bij de OG Eenheid zelf aanpassen. 
 5. Indien u de streefhuur van de OG Eenheid dynamisch wilt laten bepalen, selecteer dan de waarde **Dynamisch** in het veld **Streefhuurmethode** en een waarde in het veld **Code streefhuur t.o.v. max. huurprijs (%)**. Het systeem berekent automatisch de waarde van het veld **Streefhuur jjjj**, waarbij 'jjjj' het lopende kalenderjaar is. 
 6. Indien u de streefhuur van de OG Eenheid statisch wilt bepalen, selecteer dan de waarde **Statisch** in het veld **Streefhuurmethode**.  Selecteer dan ook de waarde **Bedrag** in het veld **Streefhuurberekening** en vul het streefhuurbedrag in het veld **Streefhuur jjjj** in, waarbij 'jjjj' het lopende kalenderjaar is. 

<hr>

### Aanpassen exploitatievorm
In deze stap past u de exploitatievorm van de OG Eenheid aan. Via de exploitatievorm van de OG Eenheid bepaalt u of, en zo ja, op welke manier, de OG Eenheid kan worden verhuurd of verkocht.  U kunt een exploitatievorm toevoegen of juist verwijderen bij de OG Eenheid. Elke exploitatievorm is van een bepaald soort (*Verhuur*, *Verkoop* of *Uit beheer*) en bestaat uit een combinatie van **Aanbiedingssoort** en **Aanbiedingsvorm**. 

U kunt als volgt een exploitatievorm toevoegen aan of verwijderen van een OG Eenheid: 
 1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid
 3. Klik op **Exploitatievormen**.  Een pagina wordt geopend met de exploitatievormen die momenteel zijn gekoppeld aan de OG Eenheid. 
 4. Om een extra exploitatievorm toe te voegen aan de OG Eenheid, klik op **+Nieuw**, selecteer een **Soort**,  klik op de drie puntjes in de kolom **Aanbiedingssoort**, selecteer een regel en klik op **OK**. 
 5. Om een bestaande exploitatievorm te verwijderen van de OG Eenheid, selecteer een regel en klik op **Verwijderen**. 

<hr>

### Aanpassen administratief eigenaar
In deze stap past u de administratief eigenaar van de OG Eenheid aan. Met de administratief eigenaar van de OG Eenheid bepaalt u of de OG Eenheid tot het DAEB-bezit of het niet-DAEB-bezit behoort. Deze DAEB-aanduiding heeft enerzijds invloed op de financiële boekingen van kosten en opbrengsten die gemaakt worden op de OG Eenheid en anderzijds invloed op de verantwoording verhuring (staatssteunregeling) van toewijzingen van de OG Eenheid aan nieuwe huurders. 

Een OG Eenheid kan in verloop van tijd verschillende administratief eigenaren hebben, maar op elk moment in de tijd maximaal één administratief eigenaar. Om die reden heeft elke administratief eigenaar van een OG Eenheid een ingangsdatum en eventueel ook een einddatum. In Empire wordt onderscheid gemaakt tussen twee soorten ingangsdata: 
- De *financiële ingangsdatum*, d.w.z. de ingangsdatum die bepalend is voor de financiële boekingen van kosten en opbrengsten; en 
- De *verhuringsingangsdatum*. d.w.z. de ingangsdatum die bepalend is voor de verantwoording verhuring (staatssteunregeling). 

Beide ingangsdata zijn standaard gelijk aan elkaar, maar u kunt de verhuringsingangsdatum desgewenst eerder laten ingaan dan de financiële ingangsdatum. 

Het wijzigen van de administratief eigenaar van ene OG Eenheid gaat in twee stappen: 
1. Aanvraag voor wijziging van administratief eigenaar invullen 
2. Aanvraag voor wijziging van administratief eigenaar goedkeuren 

U vraagt als volgt een wijziging van de administratief eigenaar aan: 
1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid
 3. Klik op **Administratief eigenaar**.  Een pagina genaamd **Administratief eigenaren per OG Eenheid** wordt geopend. 
 4. Klik op **Administratief eigenaar wijzigen** .  Een pagina genaamd **Wijzigen administratief eigenaren** wordt geopend waarop een lege regel met het eenheidsnummer en het adres van de geselecteerde OG Eenheid wordt getoond. 
 5. Vul in de **Ingangsdatum wijziging**. Let op: deze datum moet ná vandaag liggen en op of ná de datum t/m wanneer de OG Eenheid is geprolongeerd. 
 6. In kolom **Nieuwe dimensiewaarde** selecteert u de nieuwe administratief eigenaar. 
 7. De regel krijgt automatisch de **Status** *Voorlopig*. 


U keurt als volgt een wijziging van de administratief eigenaar goed: 
1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid
 3. Klik op **Administratief eigenaar**.  Een pagina genaamd **Administratief eigenaren per OG Eenheid** wordt geopend. 
 4. Klik op **Administratief eigenaar wijzigen** .  Een pagina genaamd **Wijzigen administratief eigenaren** wordt geopend waarop een gevulde regel met de **Status** *Voorlopig* wordt getoond. 
 5. Klik op **Goedkeuren**.  
 6. De regel krijgt automatisch de **Status** *Goedgekeurd*. 
 7. Klik op **Sluiten**. De pagina genaamd **Administratief eigenaren per OG Eenheid** wordt weer geopend, nu met een extra regel met de nieuwe administratief eigenaar. 
 8. Pas desgewenst de **Verhuring ingangdatum** aan in een datum die eerder ingaat dan de **Financiële ingangsdatum**. 


<hr>

### Aanpassen contactpersonen
In deze stap past u de contactpersonen van de OG Eenheid aan. Elke contactpersoon behoort tot een functiegroep, zoals huismeester.  Eén OG Eenheid kan per functiegroep maximaal één contactpersoon hebben. 

1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via
    het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**.
 2. Selecteer de OG Eenheid
 3. In het tabblad **Contactbeheer** worden de huidige contactpersonen van de OG Eenheid getoond.  
 4. Om een nieuwe contactpersoon toe te voegen selecteert u een lege regel en selecteert u op deze regel een **Functie**  en een **Contactnr.**. 
 5. Om de functie van een bestaande contactpersoon te wijzigen, selecteert u de desbetreffende regel en wijzigt u de **Functie**. 
 6. Om een bestaande contactpersoon te verwijderen van de OG Eenheid selecteert u de desbetreffende regel en klikt u op **Regel verwijderen**.

<hr>


## Zie ook (links naar andere detailprocessen uit dezelfde procesgroep)
Werkinstructie X  
Werkinstructie Y  
Werkinstructie Z

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg4Njc5Mjg1NywtMTYwODIwMzM3NiwtNT
g1NDc5MDcwLDEyMTA1MjU2NDMsLTE1ODMzNDM4ODYsLTU3NzIw
ODQyMSw1NDY0MjAyMDUsLTE2NDg2NDMxNCwtNjc0MTQwMzMyLD
IxMTM3MjA3MzYsMTQ5NjYyMzQwNCwxMDA0NzIxNjQ2LDIyNDc2
OTIyNSwxMzMxODM2NzMsMTkzNTM3NDI0MiwtMTU1MDU3ODI1Ny
wyMDcwNDE3MzcsLTc0NjQwOTkzLDExNjQ5MTU4NTQsLTYzMDQ4
Mzc5M119
-->