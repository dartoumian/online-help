# Boeken memoriaal

In dit werkproces worden memoriaalposten opgevoerd en geboekt. 

## Aanmaken standaard dagboekregels

Als u een dagboek heeft dat u regelmatig verwerkt, dan kunt u hier standaard dagboekregels voor aanmaken. U kunt deze standaardregels ophalen en vervolgens bewerken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Diversendagboek**. Selecteer in het scherm dat opent het dagboek waarvoor u standaard regels wilt importeren en klik op **OK**.
2. Klik op **Standaarddagboekregels ophalen**. Selecteer het sjabloon en klik op **OK ** om de standaard regels toe te voegen aan het dagboek. 

## Importeren journaalposten

Voor terugkerende journaalposten (denk bijvoorbeeld aan salaris boekingen vanuit een separaat pakket) kunt u standaard journaal import definiëren. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Import dashboard overzicht**. Klik op **Import** en selecteer het bestand dat u wilt importeren.  Het memoriaal wordt geimporteerd. 
2. Klik op **Uitvoeren** om het geïmporteerde bestand te verwerken tot journaalregels. 
3. U kunt de geïmporteerde regels beoordelen en bewerken door  via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **diversendagboek** te navigeren.  Selecteer in het scherm wat open het dagboek waarin de regels geïmporteerd zijn en klik op **OK**.

## Bewerken journaalregels

U kunt memoriaal regels aanmaken of bewerken in het diversendagboek. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **diversendagboek**. Selecteer in het scherm wat open het dagboek waarin u regels wilt aanmaken of bewerken en klik op **OK**.
2. Het scherm waarin u dagboekregels aan kunt maken opent. Selecteer in het veld **Batchnaam**, de batch waarin u de regels wilt aanmaken\bewerken. 
3. Vul of controleer de volgende velden:
	- **Boekingsdatum**
	- **Documentnummer**: Wordt in de meeste gevallen automatisch aangemaakt. 
	- **Rekeningsoort**: Kies uit Grootboekrekening \ klant \ leverancier
	- **Rekeningnummer**: Het grootboekrekeningnummer \ klantnummer \ leveranciersnummer. In het geval van een service en verbruik correctie kunt u dit veld leeg laten. 
	- **Kostencode**: In geval van service en verbruik vult u hier de kostencode. 
	- **Clusternr.**: Vul wanneer van toepassing. Wanneer het veld **Kostencode** gevuld is, is dit veld verplicht. 
	- **Eenheidnr. **: Vul wanneer van toepassing.
	- **Omschrijving**
	- **Btw-soort**: In de meeste gevallen laat u dit veld leeg
	- **Bedrijfboekingsgroep** laat \ maak dit veld leeg. 
	- **Productboekingsgroep**: Maak dit veld leeg. Laat dit veld gevuld wanneer u het veld **Kostencode** gevuld heeft. 
	- **Btw-bedrijfboekingsgroep**: In de meeste gevallen laat u dit veld leeg.
	- **Btw-productboekingsgroep**: In de meeste gevallen laat u dit veld leeg.
	- **Bedrag**
	- **Tegenrekeningsoort **:  Kies uit Grootboekrekening \ klant \ leverancier
	- **Tegenrekeningnummer**: Het grootboekrekeningnummer \ klantnummer \ leveranciersnummer.
	-  **Btw-soort Tegenrek. **: In de meeste gevallen laat u dit veld leeg
	- **Bedrijfboekingsgroep Tegenrek.** lLat \ maak dit veld leeg. 
	- **Productboekingsgroep Tegenrek.**: Laat \ maak dit veld leeg. 
	- **Btw-bedrijfboekingsgroep**: In de meeste gevallen laat u dit veld leeg.
	- **Btw-productboekingsgroep**: In de meeste gevallen laat u dit veld leeg.
4. Vul eventueel dimensiewaarden in de velden die eindigen op **...Code**. U kunt dimensiewaarden ook vullen door op **Dimensies** te klikken. 
5. U kunt een voorstel van de boeking die gemaakt gaat worden opvragen door op **Voorbeeld van boeking weergeven** te klikken. 
6. Voordat u het memoriaal kunt boeken dient deze goedgekeurd te worden. Klik op **Goedkeuringsaanvraag verzenden** en dan op **Dagboekbatch** om het memoriaal goed te laten keuren. Het goedkeuren vind plaats binnen het proces GOEDKEUREN DOCUMENTEN

## Boeken memoriaal

Wanneer het dagboek goedgekeurd is kunt u het dagboek boeken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **diversendagboek**. Selecteer in het scherm wat open het dagboek wat u wilt boeken klik op **OK**.
2. Het scherm waarin u dagboekregels aan kunt maken opent. Selecteer in het veld **Batchnaam**, de batch waarin u de regels wilt boeken en klik op **Boeken**.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg2NjI1NzQ4NywtMTEzNDkwMjY4XX0=
-->