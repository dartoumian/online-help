
# Vastleggen huurverhogingsbeleid 
In dit werkproces wordt het door de directie vastgestelde huurverhogingsbeleid voor het nieuwe tijdvak van de jaarlijkse huurverhoging vastgelegd in Dynamics Empire. 


## Processchema


## Aanmaken / herijken beleidstypes 
In deze stap maakt u beleidstypes aan voor de verschillende delen van het bezit van de corporatie waarvoor verschillende beleidskeuzes t.a.v. de jaarlijkse huurverhoging van toepassing zijn. Mocht u in een vorig tijdvak al beleidstypes hebben aangemaakt, dan herijkt u deze op bruikbaarheid voor het nieuwe tijdvak. 

Geadviseerd wordt elk beleidstype een code en omschrijving te geven die iets zegt over het gedeelte van het bezit (bijvoorbeeld: 'sloopwoningen' of 'wisselwoningen' of 'huidige huur < 70% van streefhuur'), en dus geen code en omschrijving die iets zegt over de huurverhoging die u voor dat gedeelte van het bezit wilt toepassen in het nieuwe tijdvak (dus bijvoorbeeld niet: 'Plus 2,0%)'. Dit heeft twee voordelen: 1: u vergroot de kans dat de beleidstypes ook volgend tijdvak nog bruikbaar zijn, en 2: de naam van het beleidstype geeft een verklaring voor het feit waarom de nettohuur van een bepaalde eenheid met een bepaald percentage is aangepast in het betreffende tijdvak (bijvoorbeeld: omdat het een sloopwoning is, wordt de nettohuur met slechts 0,2% verhoogd). 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Huurverhogingsbeleidstypes**.  Een pagina wordt geopend met een overzicht met de bestaande beleidstypes. 
2. Controleer of alle benodigde beleidstypes beschikbaar zijn. Er moet tenminste één beleidstype beschikbaar zijn voor elk gedeelte van het bezit waarvan de nettohuur met een ander verhogingspercentage moet worden aangepast. 
3. Klik op **+ Nieuw** als er een beleidstype moet worden toegevoegd en voer een **Code** en **Omschrijving** in die aangeven welk gedeelte van het bezit het betreft. 
4. Controleer de overige eigenschappen van de beleidstypes en pas deze daar waar nodig aan. 

## Vastleggen verhogingspercentage 
In deze stap voert u een nieuw tijdvak in en legt u per beleidstype het verhogingspercentage vast dat van toepassing is voor het nieuwe tijdvak. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Huurverhogingstijdvakken**.  Een pagina wordt geopend met een overzicht met de bestaande tijdvakken. 
 2. Klik op **+ Nieuw** en voer in de kolommen **Code** en **Omschrijving** een betekenisvolle code en omschrijving van het nieuwe tijdvak in (bijvoorbeeld '2020-2021' en '1-7-2020 t/m 30-6-2021'). 
 3. Selecteer in kolom **Ingangsdatum** de huurverhogingsdatum van het nieuwe tijdvak. Let op: deze datum moet op 1 juli liggen. Het systeem bepaalt automatisch de einddatum van het tijdvak. 
 4. Voer in kolom **Maximale basishuurverhogingspercentage** het verhogingspercentage in dat de Rijksoverheid heeft gepubliceerd als zijnde het maximum percentage waarmee de nettohuur van een individuele eenheid binnen het betreffende tijdvak mag worden verhoogd, als er geen inkomensafhankelijke huurverhoging wordt toegepast. 
 5. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Huurverhogingsbeleidstypes**.  Een pagina wordt geopend met een overzicht met de bestaande beleidstypes. 
 6. Selecteer een beleidstype waarvoor u een verhogingspercentage wilt vastleggen en navigeer naar **Verhogingspercentages voor beleidstypen**. Een pagina wordt geopend met een overzicht met verhogingspercentages per tijdvak per beleidstype. 
 7. Klik op **+ Nieuw**, selecteer in kolom **Tijdvakcode** de code van het nieuwe tijdvak en in kolom **Beleidstypecode** de code van het beleidstype waarvoor u een verhogingspercentage wil vastleggen. 
 8. Voer in kolom **Verhogingspercentage** het verhogingspercentage in dat in het huurverhogingsbeleid van het tijdvak is vastgesteld voor het betreffende gedeelte van het bezit. 
 9. Selecteer in kolom **Batchcode** de code van de indexeringsbatch die gebruikt moet worden voor het genereren van de huurverhogingsbrief. 
 10. Geef in kolom **Ingesteld verhogingspercentage is maximum** aan of het effectieve verhogingspercentage door afronding al dan niet boven het ingestelde verhogingspercentage mag uitkomen. 
 11. Sluit de pagina. Herhaal de vorige stappen voor elk beleidstype waarvoor u een verhogingspercentage wil vastleggen. 
 12. Selecteer een beleidstype waarvoor u een verhogingspercentage voor huishoudverklaringen wil vastleggen (t.b.v. inkomensafhankelijke huurverhoging) en klik op **Navigeren** en kies voor **Verhogingspercentages voor huishoudverklaringen**. Een pagina wordt geopend met een overzicht met verhogingspercentages per tijdvak per beleidstype per huishoudverklaringscode. 
 13. Klik op **+ Nieuw**, selecteer in kolom **Tijdvakcode** de code van het nieuwe tijdvak, in kolom **Beleidstypecode** de code van het beleidstype waarvoor u een verhogingspercentage wil vastleggen en in kolom **Huishoudverklaringscode** de code van de huishoudverklaring waarvoor u een verhogingspercentage wil vastleggen (let op: in de praktijk mag alleen voor code *'J'* (*'Hoog huishoudinkomen'*) een verhogingspercentage groter dan 0,0 worden vastgelegd).
 14. Voer in kolom **Verhogingspercentage** het extra verhogingspercentage in dat in het huurverhogingsbeleid van het tijdvak is vastgesteld die eenheden die binnen het betreffende gedeelte van het bezit zijn verhuurd aan een huishouden met ene hoog inkomen. 
 16. Indien er in het geval van inkomensafhankelijke huurverhoging een andere huurverhogingsbrief moet worden verstuurd, selecteer dan in kolom **Batchcode** de code van de indexeringsbatch die gebruikt moet worden voor het genereren van de huurverhogingsbrief. Als u deze kolom leeg laat, dan wordt de indexeringsbatch gebruikt die is ingesteld bij het beleidstype. 
 17. Indien de nettohuur in het geval van inkomensafhankelijke huurverhoging via een andere aftopping moet worden afgetopt, selecteer dan in kolom **Aftoppingscode**  de code van de aftopping die gebruikt moet worden. 
 18. Sluit de pagina. 
 19. Herhaal de vorige stappen voor elk beleidstype waarvoor u een verhogingspercentage voor huishoudverklaringen wil vastleggen. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbODYyNjcwMDE1LDYwMDgyMzEwMCwxNTQ5NT
U3Mzg2XX0=
-->