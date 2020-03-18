# Genereren overzicht gerealiseerde kasstromen

In dit werkproces wordt de gerealiseerde cashflow toegewezen aan de dVi-categorieën.

## Genereren overzicht gerealiseerde kasstromen

De eerste stap is het genereren van het overzicht voor gerealiseerde kasstromen. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Gerealiseerde cashflow** en klik op **Gerealiseerde cashflowvoorstellen**. 
2. Vul op de pagina **Gerealiseerde cashflowvoorstellen** de volgende velden:
	- **Boekingsdatum vanaf**
	- **Boekingsdatum t/m**
	- **Bestaande regels vervangen**: Zet dit vinkje aan als er al eerder een overzicht voor gerealiseerde kasstromen gegenereerd is voor (een deel van) de opgegeven periode. 
3. Klik op **OK**. De kasstromen worden gegenereerd. 

## Controleren posten ‘Nog nader te specificeren’

Er zal altijd een deel van de posten zijn dat niet toegewezen kan worden aan een specifieke categorie. Deze posten komen terecht in de categorie ‘Nog nader te specificeren’. Deze posten dient u te analyseren. 

1. Ga op de pagina **Gerealiseerde cashflow** naar de regel waarbij het vinkje **Initiële categorie** aan staat. Klik op het bedrag in kolom **Mutatie** om te zien welke posten gespecificeerd zijn binnen deze categorie. 
2. Wanneer bij een post in deze categorie de kolom **Grootboekrekening** gevuld is, betekent dit dat de kasstroom wel gespecificeerd is op een grootboekrekening, maar dat de grootboekrekening nog niet gekoppeld is aan een kasstroomcategorie. 
	- Navigeer naar de desbetreffende grootboekrekening en koppel de juiste kasstroomcategorie. 
	- Voer hierna de processtap **[Genereren overzicht gerealiseerde kasstromen](#generen-overzicht-gerealiseerde-kasstromen)** opnieuw uit. 
3. Wanneer bij een post in deze categorie de kolom **Grootboekrekening** *niet* gevuld is, betekent dit dat de kasstroom niet gespecificeerd is. Dit betekent dat een betaling wel op een leverancier of klant geboekt is, maar niet (geheel) vereffend is met een openstaande klant- of leverancierspost. Voor de posten met relatief hoge bedragen zou u kunnen onderzoeken waarom de vereffening nog niet heeft plaatsgevonden. De meeste posten zullen echter in de loop van de tijd vereffend worden. Wanneer u posten heeft vereffend dient u het overzicht voor gerealiseerde kasstromen opnieuw te genereren (**[Genereren overzicht gerealiseerde kasstromen](#generen-overzicht-gerealiseerde-kasstromen)**).

## Controleren posten ‘Nog te analyseren’

Er zal ook altijd een deel van de posten zijn waarbij geen kasstroomcategorie gespecificeerd kon worden door complexe vereffeningen. Deze posten komen in de categorie met het vinkje 'Nog te analyseren' terecht. 

1. Ga naar de regel waarbij het vinkje **Nog te analyseren** aan staat. Klik op het bedrag in kolom **Mutatie** om te zien welke posten gespecificeerd zijn binnen deze categorie. 
2. Voor de posten met relatief grote bedragen is het aan te raden om te onderzoeken hoe deze posten vereffend zijn en of het mogelijk is om de vereffening van deze posten opnieuw uit te voeren zodat minder complexe vereffeningen ontstaan. U kunt de posten op de volgende wijze onderzoeken. 
	- Selecteer de post die u wilt onderzoeken en kopieer de waarde uit het veld **KBG-grootboekpostvolgnummer**.
	- Onthoud of noteer de boekingsdatum van de post. 
	- Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de pagina **Grootboekposten** en zoek het gekopieerde **KBG-grootboekpostvolgnummer** op. 
	- Het veld **Tegenrekeningnummer** bevat een klant of leveranciersnummer. Kopieer dit nummer en navigeer naar de tabel **Klanten** of **Leveranciers** afhankelijk van het type nummer. 
	- Zoek de desbetreffende klant of leverancier op en klik op **Posten** om het overzicht van klant- of leveranciersposten te openen. 
	- Zoek de kasstroom met de complexe vereffening o.b.v. de boekingsdatum op. Klik op **Vereffende posten** om te zien hoe de post vereffend is. 
	- Voer de stappen m.b.t. vereffeningen ongedaan maken en vereffenen in de werkprocessen BEHEREN REKENING COURANT DEBITEUREN / BEHEREN REKENING COURANT CREDITEUREN uit om de posten op een andere manier te vereffenen. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyOTIxMzY4NCw0MDI3OTUzNjQsLTg4Nj
c2MzQ5NSw5MzE1NzA3MDVdfQ==
-->