# Overboeken categoriaal naar functioneel

In dit proces worden de categoriaal geboekte kosten in de 4-rubriek overgeboekt naar de functionele indeling in de 8-rubriek.

## Raadplegen rapportageschema directe toewijzing

Als eerste worden de kosten uit de 4-rubriek die direct toe te wijzen zijn aan één van de functionele rubrieken, overgeboekt naar de 8-rubriek. De eerste stap is het bepalen van de over te boeken kosten. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar rapport **Rapportageschema's**. Selecteer het rapportageschema dat betrekking heeft op direct toe te wijzen categoriale kosten en kies voor **Overzicht**. 
2. Kies op de pagina **Rapportageschemaoverzicht** bij het veld **Weergeven per** voor 'Boekingsperiode'. Zet in het **Datumfilter** de periode waarover u de directe kosten wilt boeken (bijvoorbeeld voor de maand april 01-04-2020..30-04-2020). De kolom **Mutatie in periode** toont het over te boeken bedrag. 
3. Selecteer alle rijen en kopieer en plak deze naar Excel. 

## Verwerken dagboek directe toewijzing

Nadat u bepaald heeft welke kosten overgeboekt dienen te worden kunt u deze kosten overboeken via een standaard dagboek. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **diversendagboek**. Selecteer in het scherm wat open het dagboek waarmee u de directe kosten over wilt boeken. 
2. Klik op **Standaarddagboekregels ophalen**. Selecteer het sjabloon voor het overboeken van directe kosten en klik op **OK ** om de standaard regels toe te voegen aan het dagboek. 
3. Vul of controleer de volgende velden:
	- **Boekingsdatum**
	- **Bedrag**: De regels in het standaarddagboek hebben dezelfde volgorde als de regels die u in de voorgaande stap geëxporteerd hebt naar Excel. Neem de bedragen uit het rapportageschema over in de regels van het dagboek. U kunt dit één voor één doen of door het memoriaal naar Excel te exporteren, de bedragen in de juiste kolom te plannen en de Excel regels terug te plakken in het dagboek. 
4. Verwijder de regels met een 0 bedrag uit het dagboek. 
5. Voordat u het memoriaal kunt boeken dient deze goedgekeurd te worden. Klik op **Goedkeuringsaanvraag verzenden** en dan op **Dagboekbatch** om het memoriaal goed te laten keuren. Het goedkeuren vind plaats binnen het proces GOEDKEUREN DOCUMENTEN. 
6. Nadat het memoriaal goedgekeurd is keert u terug naar het dagboek en klikt u op **Boeken**

## Raadplegen rapportageschema indirecte toewijzing

Nadat de direct toe te wijzen kosten overgeboekt zijn dienen de indirecte toe te wijzen kosten overgeboekt worden. Als eerste moet bepaald worden welke kosten nog overgeboekt moeten worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Rapportageschema's**. Selecteer het rapportageschema dat betrekking heeft op indirect toe te wijzen categoriale kosten en klik op **Overzicht**. 
2. Kies in de pagina **Rapportageschema overzicht** bij het veld **Weergeven per** voor boekingsperiode. Stel het datumfilter altijd in vanaf 1 januari van het jaar waarin de periode ligt waarover u kosten over wilt boeken om er voor te zorgen dat na-boekingen ook meegenomen worden. (bijvoorbeeld voor de maand april 01-01-2020..30-04-2020). De kolom **Mutatie in periode** toont het over te boeken bedrag. 
3. Selecteer alle rijen en kopieer en plak deze naar Excel. 

## Verwerken periodiek dagboek indirecte toewijzing

Nadat u bepaald heeft welke kosten overgeboekt dienen te worden kunt u deze kosten overboeken via een periodiek dagboek. In dit periodieke dagboek zijn de verdeelsleutels per functionele rubriek opgenomen.  

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **periodieke dagboeken**. Selecteer in het scherm wat open in het veld **Batchnaam** de batch voor het overboeken van indirecte kosten naar de functionele werkgebieden. 
2. De regels in het dagboek tonen de overboekingsrekeningen in de 4-rubriek. Controleer de **boekingsdatum** van de regels.
3. De regels in het dagboek hebben dezelfde volgorde als de regels die u in de voorgaande stap geëxporteerd hebt naar Excel. Neem de bedragen uit het rapportageschema over in de regels van het dagboek. U kunt dit één voor één doen of door het memoriaal naar Excel te exporteren, de bedragen in de juiste kolom te plannen en de Excel regels terug te plakken in het dagboek. 
4. Wanneer er regels zijn met een waarde 0 dient u een filter in te stellen voordat u het dagboek kunt boeken. Zet het filter veld op **Bedrag** en vul als filterwaarde <>0 in. De regels met bedrag 0 worden nu uitgefilterd. 

> LET OP! verwijder geen regels uit het dagboek. Wanneer u dit doet wordt de verdeling op de achtergrond ook verwijderd. 

4. Periodieke dagboeken hoeven niet goedgekeurd te worden en kunnen direct geboekt worden. Klik op **Boeken** om het periodieke dagboek te boeken. 

## Raadplegen rapportageschema toewijzen aan cluster

Nadat  zowel de directe als de indirecte kosten toegewezen zijn aan de functionele werkgebieden dienen de kosten die nu in de 8-rubriek staan nog op een algemeen cluster geboekt worden om de kosten te splitsen in DAEB en niet-DAEB. Hiervoor dient eerst bepaald te worden welke kosten nog dimensie hebben voor administrative eigenaar. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Rapportageschema's**. Selecteer het rapportageschema dat betrekking heeft functionele boekingen die op cluster geboekt moeten worden en klik op **Overzicht**. 
2. Kies in de pagina **Rapportageschema overzicht** bij het veld **Weergeven per** voor boekingsperiode. Stel het datumfilter altijd in vanaf 1 januari van het jaar waarin de periode ligt waarover u kosten over wilt boeken om er voor te zorgen dat n- boekingen ook meegenomen worden. (bijvoorbeeld voor de maand april 01-01-2020..30-04-2020).  De kolom **Te Boeken** toont het over te boeken bedrag. 
3. Selecteer alle rijen en kopieer en plak deze naar Excel. 

## Verwerken dagboek toewijzen cluster

Nadat u bepaald heeft welke kosten nog op een cluster geboekt dienen te worden kunt u deze kosten overboeken via een standaard dagboek. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **diversendagboek**. Selecteer in het scherm wat open het dagboek waarmee u de directe kosten over wilt boeken. 
2. Klik op **Standaarddagboekregels ophalen**. Selecteer het sjabloon voor het overboeken van kosten op cluster en klik op **OK ** om de standaard regels toe te voegen aan het dagboek. 
3. Vul of controleer de volgende velden:
	- **Boekingsdatum**
	- **Bedrag**: De regels in het standaarddagboek hebben dezelfde volgorde als de regels die u in de voorgaande stap geëxporteerd hebt naar Excel. Neem de bedragen uit het rapportageschema over in de regels van het dagboek. U kunt dit één voor één doen of door het memoriaal naar Excel te exporteren, de bedragen in de juiste kolom te plannen en de Excel regels terug te plakken in het dagboek. 
4. Verwijder de regels met een 0 bedrag uit het dagboek. 
5. Voordat u het memoriaal kunt boeken dient deze goedgekeurd te worden. Klik op **Goedkeuringsaanvraag verzenden** en dan op **Dagboekbatch** om het memoriaal goed te laten keuren. Het goedkeuren vind plaats binnen het proces GOEDKEUREN DOCUMENTEN. 
6. Nadat het memoriaal goedgekeurd is keert u terug naar het dagboek en klikt u op **Boeken**. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE0NjkxNDgyMV19
-->