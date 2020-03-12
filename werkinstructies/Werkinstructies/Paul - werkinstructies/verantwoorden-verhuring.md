# Verantwoorden verhuring

Elke toewijzing van een verhuurbare eenheid aan een nieuwe huurder moet worden verantwoord. Hiermee wordt bedoeld dat van elke toewijzing moet worden bepaald of de toewijzing voldoet aan de wettelijke eisen die zijn gesteld in de passendheidstoets en staatssteunregeling. 

Gedurende het kalenderjaar moet worden gemonitord of het percentage passende toewijzingen die gedurende het jaar zijn verantwoord, nog voldoet aan de daarvoor geldende wettelijke normen. 

Na afloop van het kalenderjaar moeten de verantwoordingen verhuringen worden gecontroleerd door de accountant. Nadat deze controle is afgerond, moeten de privacy-gevoelige gegevens worden opgeschoond uit de verantwoording verhuringen van het voorgaande kalenderjaar.   


## Processchema

## Registreren huishoudgegevens  

In deze stap registreert u de huishoudgegevens van een individuele toewijzing van een eenheid in de verantwoording verhuring. Op basis van de ingevulde huishoudgegevens enerzijds en de eigenschappen van de eenheid en de aanbiedhuur anderzijds, bepaalt het systeem automatisch of de toewijzing voldoet aan de wettelijke criteria van de passendheidstoets en staatssteunregeling. 
Hierbij wordt ervan uitgegaan dat in de Empire-instellingen (tabblad Verantwoording verhuring) is ingesteld dat de huishouddetails voor de verantwoording verhuring *niet* handmatig worden bepaald, d.w.z. dat de huishouddetails automatisch worden bepaald op basis van de informatie per persoon. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Verhuurmutatieoverzicht**.
 2. Zoek de verhuurmutatie op waarvoor de huishoudgegevens moeten worden geregistreerd in de verantwoording verhuring.
 3. Kies voor **Verhuringverantwoording**.  Een pagina met de details van de verantwoording verhuring verschijnt. Mocht u in plaats daarvan een foutmelding krijgen, kies dan eerst voor **Verhuuraanbieding** en klik daarna op **Verantwoording verhuring**.  Dan verschijnt de genoemde pagina alsnog. 
 4. Op tabblad **OGE-gegevens** worden gegevens over de OG Eenheid en de aanbiedhuur getoond die bepalen of de passendheidstoets en staatssteunregeling van toepassing zijn. Is dat het geval, dan hebben deze invloed op het resultaat van beide toetsen. Als de passendheidstoets en/of de staatssteunregeling niet van toepassing zijn, dan wordt dat in dit tabblad weergegeven. 
 5. Op tabblad **Betrokken personen** worden automatisch die personen getoond die onderdeel zijn van het huishouden met een rol waarbij is ingesteld dat de rol gebruikt wordt voor de verantwoording verhuring. Per persoon zijn contactnummer, naam, rol, geboortedatum en inkomen automatisch overgenomen vanuit het huishouden.
 6. Controleer de gegevens van de getoonde betrokken personen. Als er gegevens onjuist zijn of ontbreken, pas respectievelijk vul deze dan aan.
>Gegevens aanpassen kunt u op twee plekken doen: hier (binnen de verantwoording verhuring) of bij de desbetreffende persoon (contact) binnen het huishouden.
>**Let op:** de aanpassingen of aanvulling die u hier doorvoert, worden *niet* automatisch overgenomen bij de desbetreffende persoon in het huishouden. Andersom geldt dit *wel*. 
 7. Voeg eventueel één of meer extra betrokken personen toe binnen de verantwoording verhuring. Doe dit voor elke persoon die wel betrokken is bij de verantwoording verhuring, maar die u niet als contact binnen het huishouden wilt registreren. Een persoon is betrokken bij de verantwoording verhuring als diens inkomen moet meetellen in de berekening van het **Getoetst huishoudinkomen** en/of als de persoon de oudste persoon binnen het huishouden is.  
 8. Voeg eventueel één of meer extra contacten toe binnen het huishouden. Doe dit voor elke persoon die zowel betrokken is bij de verantwoording verhuring als die u als contact binnen het huishouden wilt registreren. Een extra contact dat wordt toegevoegd binnen het huishouden wordt automatisch ook als betrokken persoon binnen de verantwoording verhuring toegevoegd (mits de persoon binnen het huishouden is toegevoegd met een rol waarbij is ingesteld dat de rol gebruikt wordt voor de verantwoording verhuring). 
 9. Selecteer een **Toetsingsgrondslag** bij elke betrokken persoon met een inkomen > 0,00 euro. 
 10. Op tabblad **Extra betrokken personen** kunt u het aantal extra personen invullen dat moet meetellen in de berekening van de **Huishoudengrootte**.  Als u hier een aantal > 0 invult, selecteer dan ook een reden in veld **Extrapersonenreden**. 
 11. Op basis van de gegevens van alle betrokken personen en het aantal extra betrokken personen berekent het systeem automatisch de waarde van de volgende velden: 
 
**Aantal contractpartners** =  aantal betrokken personen van wie **Rol** = *Contractant*. 
 **Huishoudengrootte** =  aantal betrokken personen + aantal extra betrokken personen 
 14. **Geboortedatum oudste bewoner** = kleinste (d.w.z. verst in het verleden) geboortedatum van alle betrokken personen 
 15. **AOW-gerechtigd** =  indicatie of de oudste bewoner op de ingangsdatum van het contract de AOW-gerechtigde leeftijd heeft bereikt. 
 16. **Getoetst huishoudinkomen** =  som van het **Getoetste inkomen** van alle betrokken personen. 
 17. Als de OG Eenheid wordt toegewezen een rechtspersoon of aan een speciale doelgroep, kunt u dat registreren in de desbetreffende velden in tabblad **Huurdergegevens**. 
 18. Op basis van de gegevens die zijn geregistreerd of berekend in tabbladen **OGE-gegevens** en **Huurdergegevens** bepaalt het systeem automatisch per toets (passendheidstoets en staatssteunregeling) of toewijzing al dan niet moet worden getoetst, en zo nee, waarom niet, en zo ja, wat het resultaat is van de toets: passend of niet. Als de toewijzing passend is, dan toont het systeem de categorie op grond waarvan de toewijzing passend is. Als de toewijzing niet passend is, dan toont het systeem de reden waarom hij niet passend is. 
 19. Zolang niet alle gegevens zijn geregistreerd die nodig zijn om het resultaat van de toetsing te kunnen bepalen, dan toot het systeem het veld genaamd **Aantal fouten** met daarachter het aantal fouten. Klik op dit aantal en het systeem toont een popup pagina met een nadere beschrijving van de ontbrekende gegevens. Zolang er nog fouten aanwezig zijn, kunt de verantwoording niet definitief maken (tenzij u de indicatie **Incompleet dossier** aanvinkt). 
 20. Zodra u alle gegevens heeft geregistreerd en op juistheid heeft gecontroleerd, markeert u de verantwoording verhuring als zijnde definitief in veld **Verantwoording definitief**. Let op: zolang de verantwoording niet definitief is, kan de verhuuraanbieding niet worden geaccepteerd. 
 21. Mocht het zo zijn dat nog niet alle benodigde gegevens beschikbaar zijn maar de verhuuraanbieding al wel geaccepteerd moet worden, dan kunt u de indicatie **Incompleet dossier** aanvinken en een **Reden incompleet dossier** selecteren. Vervolgens kunt u - ondanks de aanwezigheid van fouten - de verantwoording toch als zijnde definitief markeren in veld **Verantwoording definitief**. 
 
Nadat de **verhuuraanbieding** is geaccepteerd, kunt u de gegevens van de definitieve **verantwoording verhuring** niet meer wijzigen. Indien het toch noodzakelijk is deze gegevens aan te passen of aan te vullen (bijvoorbeeld omdat de indicatie incompleet dossier is aangevinkt), dan moet u een *nieuwe versie* van de verantwoording verhuring aanmaken. Dit doet u als volgt: 
 22. Open de definitieve **verantwoording verhuring** (alle velden zijn grijs en kunnen niet meer worden gewijzigd en een notificatie bovenin de pagina wordt getoond). 
 23. Klik op de knop **Nieuwe verantwoording**. Het systeem maakt een nieuwe versie van de verantwoording verhuring aan en kopieert alle beschikbare gegevens uit de vorige versie naar de nieuwe versie. Het systeem actualiseert ook het lijstje met betrokken personen op basis van de personen (contacten) binnen het huishouden.  
 24. Pas of vul daar waar nodig de gegevens in de nieuwe versie van de verantwoording verhuring aan. 
 25. Markeer de nieuwe versie als zijnde definitief in veld **Verantwoording definitief**. 
 

## Monitoren wettelijke normen 

In deze stap monitort u of het percentage passende toewijzingen die gedurende het jaar zijn verantwoord, nog voldoet aan de daarvoor geldende wettelijke normen (95-5 norm voor de passendheidstoets en 80-10-10 voor de staatssteunregeling). 

1.  Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Passendheidstoets verhuring**. 
2. Vul de optie **Ingangsdatum huurcontract** in met de criteria waaraan de ingangsdatum van de nieuwe verhuurcontracten moet voldoen, willen de bijbehorende passendheidstoetsen worden meegenomen in de rapportage. Bijvoorbeeld: **>31-12-2019** 
3. Geef aan met optie **Incompleet dossiers weergeven** of u de verantwoordingen verhuringen waarbij de indicatie **Incompleet dossier** van toepassing is voor de laatste versie van de verantwoording verhuring, al dan niet wil meenemen in de rapportage. 
4. Klik op **Voorbeeld** of **Afdrukken**. Het rapport wordt gegenereerd.  
5. Het rapport toont alle *definitieve* verantwoordingen verhuringen die behoren bij een *geaccepteerde* verantwoording verhuring waarvan de ingangsdatum voldoet aan het ingegeven criterium. Let op: dit betekent dat zolang de verhuuraanbieding niet is geaccepteerd, de bijbehorende verantwoording verhuring niet wordt meegenomen in de rapportage. Let op: per verantwoording verhuring wordt alleen de laatste versie die is gemarkeerd als zijnde definitief meegenomen in de rapportage. 
6. Elke verantwoording verhuring wordt getoond in één van de categorieën, waarbij er drie soorten categorieën zijn: niet-getoetst, passend en niet-passend. Op het rapport wordt het totaal aantal niet-getoetste verhuringen, het totaal aantal passende verhuringen en het totaal aantal niet-passende verhuringen getoond. 
7. Onderaan het rapport wordt het percentage passende verhuringen en het percentage niet-passende verhuringen getoond. 

Herhaal dit voor het rapport **Toets staatssteunregeling verhuringen**. Onderaan het rapport wordt het percentage verhuringen binnen de toewijzingsruimte (met onderscheid tussen toewijzing aan huishoudens met lage inkomens (80% groep) en toewijzingen aan huishoudens met midden inkomens (10% groep) en het percentage verhuringen buiten de toewijzingsruimte getoond.


## Controle door accountant 

In deze stap controleert de account de verantwoordingen verhuringen van het voorgaande kalenderjaar. 


## Opschonen privacy gevoelige gegevens 

In deze stap schoont u de privacy gevoelige gegevens uit de verantwoordingen verhuringen van het voorgaande kalenderjaar. 

1.  Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Personen en huishoudinkomen van verhuringsverantwoordingen opschonen**. 
2. Vul in veld **Accountantscontroledatum** de datum in waarop de accountantscontrole heeft plaatsgevonden. 
3. Vul in veld **Opschoningspeildatum** de datum in die door het systeem wordt gebruikt als peildatum voor het selecteren van de verantwoordingen die moeten worden opgeschoond. Alle verantwoordingen worden opgeschoond waarvan de laatste versie als zijnde definitief is gemarkeerd en waarvan de huurcontractingangsdatum <= de ingevulde opschoningspeildatum. 
4. Geef aan of u de verantwoordingen verhuringen waarvan de laatste versie is aangemerkt als zijnde incompleet dossier, ook moeten worden opgeschoond. 
5. Klik op **OK**. 
6. Het systeem selecteert alle verantwoordingen die voldoen aan de genoemde criteria. Bij deze selectie kijkt het systeem per verantwoording alleen naar de laatste versie van die verantwoording. Als de *laatste* versie voldoet aan de selectiecriteria, dan schoont het systeem *alle* versies van die verantwoording op. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MTAwNDc1MDIsLTE3MzkxOTM0NDksMT
IwMDg0MDAwOCwtMTU0MzQ5MzIzMiwtMTAxMTUwMTIxMSw3NTEx
OTMwMzEsLTE2NTAxMzA4MzQsMzEzODQ0ODY4LC0xNzMzODI2Mz
EzLC0yODQxNDg1MjUsLTYxMzA2NDc3LC0zNzQwMjkyOTcsMTIz
ODQ1MDg3MywyMTI0ODQ5ODI5LC0xNDY4NzE3NjM1LC0yMDg2MD
gzMjcyLDU5NzgxOTA0OF19
-->