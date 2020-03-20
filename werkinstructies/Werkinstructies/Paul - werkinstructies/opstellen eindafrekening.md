# Opstellen eindafrekening 
In dit proces wordt de eindafrekening opgesteld voor een klant van wie een huurcontract is beëindigd. De eindafrekening geeft een overzicht van de openstaande facturen van de betreffende klant. De facturen kunnen betrekking hebben op o.a.: 
 - Kosten met betrekking tot mutatieonderhoud die de corporatie doorbelast aan de vertrekkende huurder; 
 - Nog niet betaalde huur van vorige prolongatieperioden; 
 - Terugbetaling van vooruitbetaalde huur; 
 - Terugbetaling van de waarborgsom. 


## Processchema 


## Genereren afrekening 
In deze stap genereert u de eindafrekening voor de vertrekkende huurder. Om de eindafrekening te kunnen genereren, moeten alle contractregels van de OG Eenheid zijn geprolongeerd tot en met de einddatum van het opgezegde huurcontract en moeten alle overige (credit)facturen van de vertrekkende huurder zijn geboekt. Zie ook de opmerking hieronder. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Verhuurmutatieoverzicht**.
2. Zoek de verhuurmutatie op waarvan de eindafrekening moet worden opgesteld.
3. Open de detailpagina van de verhuurmutatie. 
4. Klik op **Navigeren** en kies voor **Huuropzegging**. De pagina met de details van de huuropzegging van de OG Eenheid wordt geopend. 
5. Klik op **Proces** en kies voor **Eindafrekening**. Een pagina met verschillende opties wordt geopend. Zie opmerking hieronder. 
6.  Geef in veld **Specificatie** aan of u al dan niet een specificatie van de openstaande facturen afgedrukt wil hebben op de eindafrekening. Als u deze optie niet aanvinkt, dan wordt alleen een te betalen bedrag per categorie (bijvoorbeeld *Huur* en *Waarborgsom*) vermeld op de eindafrekening. Per categorie wordt de som van het openstaande bedrag van de daartoe behorende openstaande klantposten vermeld. In de specificatie wordt het openstaande bedrag per openstaande klantpost vermeld. 
7. Geef in het veld **Automatische waarborgsom** aan of u een creditfactuur voor de terugbetaling van de waarborgsom wil laten aanmaken en meenemen in de eindafrekening. 
8. Geef in veld **Interactie registreren** aan of u wil dat het systeem al dan niet een interactie registreert voor de vertrekkende huurder. 
9. Klik op **Afdrukken**. 

Mocht u de melding krijgen dat de eenheid nog niet volledig is geprolongeerd, navigeer dan naar de pagina **Prolongatierunoverzicht**, klik op **Nieuw**, selecteer de OG Eenheid in het veld **OGE filter**, selecteer de prolongatieperiode in het veld **Prol. periodenaam** en klik op **Uitvoeren / boeken**. Probeer daarna opnieuw de eindafrekening te genereren.


## Verzenden afrekening 
In deze stap verstuurt u de gegenereerde eindafrekening naar de vertrekkende huurder. Deze stap vindt plaats buiten Dynamics Empire. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTczMTgxMDEwNF19
-->