# Verantwoorden verhuring

Elke toewijzing van een verhuurbare eenheid aan een nieuwe huurder moet worden verantwoord. Hiermee wordt bedoeld dat van elke toewijzing moet worden bepaald of de toewijzing voldoet aan de wettelijke eisen die zijn gesteld in de passendheidstoets en staatssteunregeling. 

Gedurende het kalenderjaar moet worden gemonitord of het percentage passende toewijzingen die gedurende het jaar zijn verantwoord, nog voldoet aan de daarvoor geldende wettelijke normen. 

Na afloop van het kalenderjaar moeten de verantwoordingen verhuringen worden gecontroleerd door de accountant. Nadat deze controle is afgerond, moeten de privacy gevoelige gegevens worden opgeschoond uit de verantwoording verhuringen van het voorgaande kalenderjaar.   


## Processchema

## Registeren huishoudgegevens  

In deze stap registreert u de huishoudgegevens van een individuele toewijzing van een eenheid in de verantwoording verhuring. Op basis van de ingevulde huishoudgegevens enerzijds en de eigenschappen van de eenheid en de aanbiedhuur anderzijds, bepaalt het systeem automatisch of de toewijzing voldoet aan de wettelijke criteria van de passendheidstoets en staatssteunregeling. 
Hierbij wordt ervan uitgegaan dat in de Empire-instellingen (tabblad Verantwoording verhuring) is ingesteld dat de huishouddetails voor de verantwoording verhuring *niet* handmatig worden bepaald, d.w.z. dat de huishouddetails automatisch worden bepaald op basis van de informatie per persoon. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Zoek de OG Eenheid op waarvoor de huishoudgegevens moeten worden geregistreerd in de verantwoording verhuring.
3. Klik op **Navigeren** en kies voor **Verhuuraanbieding**.  Een pagina met de details van de verhuuraanbieding verschin. 
4. Klik op **Navigeren** en kies voor **Verantwoording verhuring**.  Een pagina met de details van de verantwoording verhuring verschijnt. 
5. In tabblad **OGE-gegevens** worden gegevens over de OG Eenheid en de aanbiedhuur getoond die bepalen of de passendheidstoets en staatssteunregeling van toepassing zijn, en zo ja, van invloed zijn op het resultaat van beide toetsen. Als de passendheidstoets en/of de staatssteunregeling niet van toepassing zijn, dan wordt dat in dit tabblad weergegeven. 
6. In tabblad **Betrokken personen** worden automatisch die personen getoond die onderdeel zijn van het huishouden met een rol waarbij is ingesteld dat de rol gebruikt wordt voor de verantwoording verhuring. Per persoon zijn diens contactnummer, naam, rol, geboortedatum en inkomen automatisch overgenomen vanuit het huishouden. 
7. Controleer de gegevens van de getoonde betrokken personen. Als er gegevens onjuist zijn of ontbreken, pas respectievelijk vul deze da aan. Let op: u kunt dat op twee plekken doen: hier (binnen de verantwoording verhuring) of bij de desbetreffende persoon (contact) binnen het huishouden. Let op: de aanpassingen of aanvulling die u hier doorvoert, worden *niet* automatisch overgenomen bij de desbetreffende persoon in het huishouden. Andersom wel, dat wil zeggen de aanpassingen of aanvullingen die u bij de persoon (contact) binnen het huishouden doorvoert, worden *wel* automatisch doorgevoerd binnen de verantwoording verhuring. 
8. Voeg eventueel één of meer extra betrokken personen toe binnen de verantwoording verhuring. Doe dit voor elke persoon die wel betrokken is bij de verantwoording verhuring maar die u niet als contact binnen het huishouden wil registreren. Een persoon is betrokken bij de verantwoording verhuring als diens inkomen moet meetellen in de berekening van het **Getoetst huishoudinkomen** en/of als de persoon de oudste persoon binnen het huishouden is.  
 - Voeg eventueel één of meer extra contacten toe binnen het huishouden. Doe dit voor elke persoon die zowel betrokken is bij de verantwoording verhuring als die u als contact binnen het huishouden wil registreren. Een extra contact die wordt toegevoegd binnen het huishouden wordt automatisch ook als betrokken persoon binnen de verantwoording verhuring toegevoegd (mits de persoon binnen het huishouden is toegevoegd met een rol waarbij is ingesteld dat de rol gebruikt wordt voor de verantwoording verhuring). 
9. Selecteer een **Toetsingsgrondslag** bij elke betrokken persoon met een inkomen > 0,00 euro. 
10. In tabblad **Extra betrokken personen** kunt u het aantal extra personen invullen dat moet meetellen in de berekening van het **Huishoudengrootte**.  Als u hier een aantal > 0 invult, selecteer dan ook een reden in veld **Extrapersonenreden**. 
11. Op basis van de gegevens van alle betrokken personen en het aantal extra betrokken personen berekent het systeem automatisch de waarde van de volgende velden: 
   - **Aantal contractpartners** =  
   - **Huishoudengrootte** =  
   - **Geboortedatum oudste bewoner** = 
   - **AOW-gerechtigd** =  
   - **Getoetst huishoudinkomen** =  
12. Als de OG Eenheid wordt toegewezen een rechtspersoon of aan een speciale doelgroep, kunt u dat registreren in de desbetreffende velden in tabblad **Huurdergegevens**. 
13. Op basis van de gegevens die zijn geregistreerd of berekend in tabbladen **OGE-gegevens** en **Huurdergegevens** bepaalt het systeem automatisch per toets (passendheidstoets en staatssteunregeling) of toewijzing al dan niet moet worden getoetst, en zo nee, waarom niet, en zo ja, wat het resultaat is van de toets: passend of niet. Als de toewijzing passend is, dan toont het systeem de categorie op grond waarvan de toewijzing passend is. Als de toewijzing niet passend is, dan toont het systeem de reden waarom hij niet passend is. 
14. Zolang niet alle gegevens zijn geregistreerd die nodig zijn om het resultaat van de toetsing te kunnen bepalen, dan toot het systeem het veld genaamd **Aantal fouten** met daarachter het aantal fouten. Klik op dit aantal en het systeem toont een popup pagina met een nadere beschrijving van de ontbrekende gegevens. Zolang er nog fouten aanwezig zijn, kunt de verantwoording niet definitief maken (tenzij u de indicatie **Incompleet dossier** aanvinkt). 
15. Zodra u alle gegevens heeft geregistreerd en op juistheid heeft gecontroleerd, markeert u de verantwoording verhuring als zijnde definitief in veld **Verantwoording definitief**. Let op: zolang de verantwoording niet definitief is, kan de verhuuraanbieding niet worden geaccepteerd. 
16. Mocht het zo zijn dat nog niet alle benodigde gegevens beschikbaar zijn maar de verhuuraanbieding al wel geaccepteerd moet worden, dan kunt u de indicatie **Incompleet dossier** aanvinken en een **Reden incompleet dossier** selecteren. Vervolgens kunt u - ondanks de aanwezigheid van fouten - de verantwoording toch als zijnde definitief markeren in veld **Verantwoording definitief**. 
 
Nadat de **verhuuraanbieding** is geaccepteerd, kunt u de gegevens van de definitieve **verantwoording verhuring** niet meer wijzigen. Indien het toch noodzakelijk is deze gegevens aan te passen of aan te vullen (bijvoorbeeld omdat de indicatie incompleet dossier is aangevinkt), dan moet u een *nieuwe versie* van de verantwoording verhuring aanmaken. Dit doet u als volgt: 
1. Open de definitieve **verantwoording verhuring** (alle velden zijn grijs en kunnen niet meer worden gewijzigd en een notificatie bovenin de pagina wordt getoond). 
2. Klik op de knop **Nieuwe verantwoording**. Het systeem maakt een nieuwe versie van de verantwoording verhuring aan en kopieert alle beschikbare gegevens uit de vorige versie naar de nieuwe versie. Het systeem actualiseert ook het lijstje met betrokken personen op basis van de personen (contacten) binnen het huishouden.  
3. Pas of vul daar waar nodig de gegevens in de nieuwe versie van de verantwoording verhuring aan. 
4. Markeer de nieuwe versie 
 

## Monitoren wettelijke normen 

In deze stap . 

1. Bla bla 


## Controle door accountant 
In deze stap ... 

1. Bla bla . 


## Opschonen privacy gevoelige gegeens 

In deze stap  . 

1. . Bla bla. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0OTYzNzY3MzAsLTE3MzM4MjYzMTMsLT
I4NDE0ODUyNSwtNjEzMDY0NzcsLTM3NDAyOTI5NywxMjM4NDUw
ODczLDIxMjQ4NDk4MjksLTE0Njg3MTc2MzUsLTIwODYwODMyNz
IsNTk3ODE5MDQ4XX0=
-->