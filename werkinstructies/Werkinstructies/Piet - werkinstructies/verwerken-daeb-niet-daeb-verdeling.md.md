# Verwerken DAEB/niet-DAEB-verdeling

In dit werkproces worden de niet-DAEB-gerelateerde posten overgeboekt naar het niet-DAEB-bedrijf.

## Verdelen gemengde posten

Als eerste dienen alle posten die met de administratiefeigenaar-dimensie 'Gemengd' geboekt zijn en die nog niet eerder verdeeld zijn, verdeeld te worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icoLampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Verdeelsleuteltoepassingenoverzicht** en klik op **Nieuw**. De kaart voor een nieuwe verdeelsleuteltoepassing opent.
2. Klik op **Grootboekposten verzamelen**. 
	- Vul in het veld **Begindatum** 1 januari van het jaar waarin u wilt verdelen in.
	- Vul in het veld **Einddatum** de einddatum van de periode waarvan u de posten wilt verdelen in. 
	- Klik op **OK**. De te verdelen posten worden verzameld. 
3. Klik op **Grootboekposten verdelen**. De grootboekposten worden verdeeld. 
4. Klik op **Verdeelsleuteltoepassing verwerken**. 
	- Vul in het veld **Boekingsdatum** de einddatum van de te verdelen periode in. 
	- Vul in het veld **Omschrijving** de omschrijving in die meegegeven moet worden aan de grootboekposten. 
	- Klik op **OK** om de verdeling te boeken. 

## Overboeken niet-DAEB-posten (binnen TI)

Nadat alle posten verdeeld zijn in DAEB en niet-DAEB kunt u de niet-DAEB-posten in de TI overboeken naar het niet-DAEB-bedrijf. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icoLampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Rekening courant afrekeningenoverzicht** en klik op **Nieuw**. De pagina voor een nieuwe rekening-courantafrekening opent.
2. Klik op **Grootboekposten verzamelen**.
	- Selecteer in het veld **Administratief eigenaar** de administratieve eigenaar waarvoor u de posten over wilt boeken. 	
	- Vul in het veld **Begindatum** 1 januari van het jaar waarin u wilt overboeken in.
	- Vul in het veld **Einddatum** de einddatum van de periode waarvan u de posten wilt overboeken in. 
	- Klik op **OK** om de over te boeken posten op te halen. 
3. Klik op **Grootboekposten comprimeren** om de posten te comprimeren. 
4. Klik op **Rekening-courantafrekening verwerken**. 
	- Vul in het veld **Boekingsdatum** de einddatum van de over te boeken periode in. 
	- Vul in het veld **Omschrijving** de omschrijving in die meegegeven moet worden aan de grootboekposten. 
	- Klik op **OK** om de overboeking te boeken. 

## Boeken niet-DAEB-posten

Nadat de niet-DAEB-posten in de TI overgeboekt zijn naar de rekening-courant dient de rekening-courantboeking ook uitgevoerd te worden in het niet-DAEB-bedrijf. 

1. Navigeer via de instellingenknop ![iInstellingen icon](/assets/images/instellingen.png "instellingen icon"](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-experience/settings_icon_small.png) 	naar **Mijn instellingen**. Selecteer in het veld **Bedrijf** het niet-DAEB-bedrijf. Klik op **OK** in het scherm **Mijn instellingen**. Het niet-DAEB-bedrijf wordt geopend. 
2. Navigeer in het niet-DAEB-bedrijf via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icoLampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Diversendagboek**. Selecteer in het scherm dat opent het dagboek waarmee u de rekening-courantafrekeningen wilt verwerken. 
3. Klik op **RC regels aanmaken** om de rekening-courantregels op te halen. 
4. Klik op **Boeken** om de dagboekregels te boeken. 

## Boeken memoriaal

Wanneer er boekingen t.b.v. DAEB/niet-DAEB zijn die handmatig verwerkt dienen te worden kunt u dit doen via het reguliere proces voor BOEKEN MEMORIAAL. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwOTEyNTIzOTMsLTIxMzYzNDM2MTcsLT
EzMzQ3MDE0NDIsMjAxODY1NzcwNywxNTA5Mzg2MDEzXX0=
-->