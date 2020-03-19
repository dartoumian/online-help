
# Voorbereiden jaarlijkse huurverhoging 
In dit werkproces wordt de jaarlijkse huurverhoging voorbereid. Doel is dat er nieuwe woningwaarderingen zijn aangemaakt voor alle OG Eenheden waarvan de nettohuur moet worden aangepast. De punten van deze nieuwe woningwaarderingen worden berekend op basis van enerzijds de nieuwe parameters die de Rijksoverheid heeft gepubliceerd voor het nieuwe tijdvak, en anderzijds de nieuwe WOZ-waarden die de gemeenten hebben aangeleverd. Op basis van de nieuwe woningwaarderingen wordt vervolgens per eenheid de nieuwe maximale huurprijs bepaald die geldt voor het nieuwe huurverhogingstijdvak. 

## Processchema 

## Aanpassen woningwaarderingparameters 
In deze stap voert u de nieuwe woningwaarderingparameters in die de Rijksoverheid heeft gepubliceerd voor het nieuwe huurverhogingstijdvak. Deze parameters worden vermeld in het *Themadocument jaarlijkse huurverhoging* dat cegeka-dsa jaarlijks actualiseert en publiceert op de servicedesk website  [https://support.cegeka-dsa.nl](https://support.cegeka-dsa.nl). 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Woningwaarderingparametersets**.  Een pagina wordt geopend met een overzicht van de beschikbare parametersets. 
2. Klik op **+ Nieuw** en voer in kolom **Ingangsdatum** de datum in waarop de door de Rijksoverheid gepubliceerde parameters ingaan (doorgaans is dit op 1 juli). Het systeem vult kolom **Type** met de waarde *Handmatig ingevoerd*. 
3. Voer in de verschillende kolommen de waarde van de desbetreffende parameter in die de Rijksoverheid heeft gepubliceerd.  
4. Sluit de pagina. 


## Importeren WOZ-waarden 
In deze stap importeert u de nieuwe WOZ-waarden die de gemeenten hebben aangeleverd voor de verschillende OG Eenheden. Deze WOZ-waarden vormen een belangrijke input voor het berekenen van de punten voor de nieuwe woningwaardering. Voordat de WOZ-gegevens kunnen worden ingelezen, moet het ontvangen bestand worden omgezet naar het formaat dat door Dynamics Empire kan worden verwerkt. In het * Themadocument jaarlijkse huurverhoging* is gespecificeerd wat het formaat van het bestand moet zijn.  

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **OGE exploitatie (Fin.)-import**.  Een pagina wordt geopend. 
2. Klik op **Acties** en kies voor **Functies** en **Importeren**.  
3. Klik op **Kiezen** en selecteer het importbestand met de door de gemeente aangeleverde WOZ-waarden. 
4. De geïmporteerde gegevens worden getoond in het tabblad **WOZ**. 
5. Klik op  **Acties** en kies voor **Functies** en **Verwerken**. De geïmporteerde gegevens worden verwerkt in Dynamics Empire. Daarbij wordt per OG Eenheid de geïmporteerde WOZ-waarde toegevoegd aan de lijst met **WOZ-gegevens** van de betreffende OG Eenheid. 
6. Controleer aan de hand van kolom **Verwerkt** of er geïmporteerde gegevens niet konden worden verwerkt. Bekijk per geval in kolom **Reden niet verwerkt** waardoor de gegevens niet konden worden verwerkt. Onderneem daar waar nodig actie m de gegevens alsnog te kunnen verwerken. 
7. Sluit de pagina. 


## Importeren maximale huurprijzen 
In deze stap importeert u de nieuwe maximale huurprijzen die de Rijksoverheid heeft gepubliceerd voor het nieuwe huurverhogingstijdvak. Hiertoe kunt u gebruik maken van de importbestanden met maximale huurprijzen voor zelfstandige woningen en onzelfstandige woningen, die cegeka-dsa jaarlijks publiceert op de website van de servicedesk [https://support.cegeka-dsa.nl](https://support.cegeka-dsa.nl).  
 
1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Import maximale huurprijzen**.  Een pagina wordt geopend. 
2. Selecteer het **Woningtype** *Zelfstandige woning*. 
3. Selecteer het **Jaar** waarvoor u de maximale huurprijzen wil importeren. 
4. Klik op **OK**. 
5. Klik op **Kiezen**, selecteer het juiste importbestand en klik op **Open**. De maximale huurprijzen worden geïmporteerd. 
6. Navigeer een tweede keer naar de genoemde taak en herhaal de stappen voor het **Woningtype** *Onzelfstandige woning*.  


## In bulk aanmaken woningwaardering 
In deze stap maakt u in bulk nieuwe woningwaarderingen aan voor alle OG Eenheden waarvan u de nettohuur wil aanpassen. De punten van deze nieuwe woningwaarderingen worden berekend op basis van de nieuwe WOZ-waarden en de nieuwe parameters. Binnen elke nieuwe woningwaardering wordt automatisch de nieuwe maximale huurprijs van de desbetreffende OG Eenheid vastgelegd die behoort bij het aantal berekende woningwaarderingspunten. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Woningwaardering maken**.  Een pagina wordt geopend.
2. Selecteer in optie **Ingangsdatum** de ingangsdatum van de nieuwe woningwaarderingen. Voor de jaarlijkse huurverhoging met deze ingangsdatum gelijk zijn aan de huurverhogingsdatum (bijvoorbeeld: 1-7-2020). 
3. Stel eventueel filters in tabblad **Filter: OG Eenheid** in. Als u hier geen filter instelt, dan wordt een nieuwe woningwaardering aangemaakt voor alle OG Eenheden. 
4. Klik op **OK**. Het systeem maakt in bulk een nieuwe woningwaardering met de geselecteerde ingangsdatum aan voor alle OG Eenheden die voldoen aan het ingestelde filter. 

Deze nieuwe woningwaarderingen bevatten per OG Eenheid de WOZ-waarde uit een regel van de WOZ-gegevens van de OG Eenheid. Hierbij wordt de regel geselecteerd waarbij het veld **Jaar vanaf** het jaartal bevat waarbinnen de ingangsdatum van de woningwaardering valt. In het geval er meerdere regels voldoen aan dit criterium, dan wordt de regel geselecteerd met de hoogste **WOZ-peildatum**. 
De punten van deze nieuwe woningwaarderingen worden berekend op basis van de nieuwe WOZ-waarde en de nieuwe woningwaarderingparameters die u hiervoor heeft aangemaakt. 
Deze nieuwe woningwaarderingen bevatten per OG Eenheid de maximale huurprijs die behoort bij het nieuwe aantal punten en bij het jaartal waarbinnen de ingangsdatum van de woningwaardering valt. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDY5MzIwMDgxLDEzOTIyNTE1M119
-->