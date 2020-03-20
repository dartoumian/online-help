
 12. **Aantal contractpartners** =  aantal betrokken personen van wie **Rol** = *Contractant*. 
 **Huishoudengrootte** =  aantal betrokken personen + aantal extra betrokken personen 
 13. **Geboortedatum oudste bewoner** = kleinste (d.w.z. verst in het verleden) geboortedatum van alle betrokken personen 
 14. **AOW-gerechtigd** =  indicatie of de oudste bewoner op de ingangsdatum van het contract de AOW-gerechtigde leeftijd heeft bereikt. 
 15. **Getoetst huishoudinkomen** =  som van het **Getoetste inkomen** van alle betrokken personen. 
 16. Als de OG Eenheid wordt toegewezen een rechtspersoon of aan een speciale doelgroep, kunt u dat registreren in de desbetreffende velden in tabblad **Huurdergegevens**. 
 17. Op basis van de gegevens die zijn geregistreerd of berekend in tabbladen **OGE-gegevens** en **Huurdergegevens** bepaalt het systeem automatisch per toets (passendheidstoets en staatssteunregeling) of toewijzing al dan niet moet worden getoetst, en zo nee, waarom niet, en zo ja, wat het resultaat is van de toets: passend of niet. Als de toewijzing passend is, dan toont het systeem de categorie op grond waarvan de toewijzing passend is. Als de toewijzing niet passend is, dan toont het systeem de reden waarom hij niet passend is. 
 18. Zolang niet alle gegevens zijn geregistreerd die nodig zijn om het resultaat van de toetsing te kunnen bepalen, dan toot het systeem het veld genaamd **Aantal fouten** met daarachter het aantal fouten. Klik op dit aantal en het systeem toont een popup pagina met een nadere beschrijving van de ontbrekende gegevens. Zolang er nog fouten aanwezig zijn, kunt de verantwoording niet definitief maken (tenzij u de indicatie **Incompleet dossier** aanvinkt). 
 19. Zodra u alle gegevens heeft geregistreerd en op juistheid heeft gecontroleerd, markeert u de verantwoording verhuring als zijnde definitief in veld **Verantwoording definitief**. Let op: zolang de verantwoording niet definitief is, kan de verhuuraanbieding niet worden geaccepteerd. 
 20. Mocht het zo zijn dat nog niet alle benodigde gegevens beschikbaar zijn maar de verhuuraanbieding al wel geaccepteerd moet worden, dan kunt u de indicatie **Incompleet dossier** aanvinken en een **Reden incompleet dossier** selecteren. Vervolgens kunt u - ondanks de aanwezigheid van fouten - de verantwoording toch als zijnde definitief markeren in veld **Verantwoording definitief**. 
 
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


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcyMjY2NTE1MF19
-->