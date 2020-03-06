# Publiceren eenheid

Xxxxx.   


## Processchema

## Voorbereiden publicatie  

Xxxxx. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Zoek de OG Eenheid op waarvan de publicatie moet worden voorbereid.
3. Klik op **Navigeren** en kies voor **Verhuuraanbieding**.  Een pagina met de details van de verhuuraanbieding verschijnt. 
4. Klik op . 
5. . 
 

## Publiceren eenheid 

In deze stap publiceert u daadwerkelijk de eenheid, zodat woningzoek). 

1.  Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Passendheidstoets verhuring**. 
2. Vul de optie **Ingangsdatum huurcontract** in met de criteria waaraan de ingangsdatum van de nieuwe verhuurcontracten moet voldoen, willen de bijbehorende passendheidstoetsen worden meegenomen in de rapportage. Bijvoorbeeld: **>31-12-2019** 
3. Geef aan met optie **Incompleet dossiers weergeven** of u de verantwoordingen verhuringen waarbij de indicatie **Incompleet dossier** van toepassing is voor de laatste versie van de verantwoording verhuring, al dan niet wil meenemen in de rapportage. 
4. Klik op **Voorbeeld** of **Afdrukken**. Het rapport wordt gegenereerd.  
5. Het rapport toont alle *definitieve* verantwoordingen verhuringen die behoren bij een *geaccepteerde* verantwoording verhuring waarvan de ingangsdatum voldoet aan het ingegeven criterium. Let op: dit betekent dat zolang de verhuuraanbieding niet is geaccepteerd, de bijbehorende verantwoording verhuring niet wordt meegenomen in de rapportage. Let op: per verantwoording verhuring wordt alleen de laatste versie die is gemarkeerd als zijnde definitief meegenomen in de rapportage. 
6. Elke verantwoording verhuring wordt getoond in één van de categorieën, waarbij er drie soorten categorieën zijn: niet-getoetst, passend en de gepubliceerde eenheid kunnen zien en kunnen reageren op de eenheid. niet-passend. Op het rapport wordt het totaal aantal niet-getoetste verhuringen, het totaal aantal passende verhuringen en het totaal aantal niet-passende verhuringen getoond. 
7. Onderaan het rapport wordt het percentage passende verhuringen en het percentage niet-passende verhuringen getoond. 

Herhaal dit voor het rapport **Toets staatssteunregeling verhuringen**. Onderaan het rapport wordt het percentage verhuringen binnen de toewijzingsruimte (met onderscheid tussen toewijzing aan huishoudens met lage inkomens (80% groep) en toewijzingen aan huishoudens met midden inkomens (10% groep) en het percentage verhuringen buiten de toewijzingsruimte getoond.


## Controle door accountant 

In deze stap controleert de account de verantwoordingen verhuringen van het voorgaande kalenderjaar. 


## Opschonen privacy gevoelige gegevens 

In deze stap schoont u de privacy gevoelige gegevens uit de verantwoordingen verhuringen van het voorgaande kalenderjaar. 

1.  Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Onr. Goed-Eenhedenoverzichttaak **Personen en huishoudinkomen van verhuringsverantwoordingen opschonen**. 
2. Zoek de OG Eenheid Vul in veld **Accountantscontroledatum** de datum in waarop die moet worden gepubliceerd. 
3. Xxxxxx 


## Verwerken reacties  

In deze stap verwerkt u de reacties van woningzaccountantscontrole heeft plaatsgevonden. 
3. Vul in veld **Opschoningspeildatum** de datum in die door het systeem wordt gebruikt als peildatum voor het selecteren van de verantwoordingen die moekten worden op de gepubliceerde eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem. 


## Bepalen rangorde  

In deze stap bepaalt u de rangorde van de kandidaten die hebben gereageerd op de gepubliceerde eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteemgeschoond. Alle verantwoordingen worden opgeschoond waarvan de laatste versie als zijnde definitief is gemarkeerd en waarvan de huurcontractingangsdatum <= de ingevulde opschoningspeildatum. 
4. Geef aan of u de verantwoordingen verhuringen waarvan de laatste versie is aangemerkt als zijnde incompleet dossier, ook moeten worden opgeschoond. 
5. Klik op **OK**. 
6. Het systeem selecteert alle verantwoordingen die voldoen aan de genoemde criteria. Bij deze selectie kijkt het systeem per verantwoording alleen naar de laatste versie van die verantwoording. Als de *laatste* versie voldoet aan de selectiecriteria, dan schoont het systeem *alle* versies van die verantwoording op. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUwMzMzMDAwNiwtMTE3NDU3MTI0Nl19
-->