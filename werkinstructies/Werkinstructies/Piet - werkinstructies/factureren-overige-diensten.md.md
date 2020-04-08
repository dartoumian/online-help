# Factureren overige diensten

In dit werkproces worden de diensten gefactureerd die geen betrekking hebben op onderhoud, periodieke huur of het verkopen van onroerend goed.


## Maak factuur voor niet verhuur gerelateerde diensten

Wanneer u een factuur aan wilt maken voor niet verhuurgerelateerde zaken kunt u hier een verkoopfactuur voor aanmaken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Verkoopfacturen** en klik op **Nieuw**. Er wordt een nieuwe verkoopfactuur aangemaakt. 
2. Vul of muteer de volgende velden op de factuur kop:
	- **Klantnaam**
	- **Boekingsomschrijving**: Het onderwerp van de factuur.
	- **Boekingsdatum**
	- **Vervaldatum**: De datum waarop de factuur betaald dient te zijn.
	- **Transactiewijze**: De wijze waarop de factuur betaald wordt. 
3. Vul of muteer de volgende velden in de factuurregel
	- **Soort**: Grootboekrekening
	- **Nr.**: Grootboek waarop de kosten geboekt dienen te worden. 
	- **Btw- productboekingsgroep**: De btw soort die van toepassing is.
	- **Omschrijving**: De omschrijving van de kosten. Deze omschrijving wordt meegegeven in het grootboek en wordt getoond op de factuur. 
	- **Aantal**: 1
	- **Eenheidsprijs Excl. btw**
	 - **Dimensie waarden velden**: Velden die eindigen met de het woord code zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld kunnen worden. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.  

## Boeken en versturen niet verhuur gerelateerde factuur

Nadat u de factuurgegevens gevuld heeft kunt u de verkoopfactuur boeken en versturen. 

1. Klik op **Boeken en verzenden**. 
2. Klik op **...** en selecteer in het veld **E-mail** **Ja (standaardinstellingen gebruiken)**. Klik op **Ok**. Klik op **Ja**. 
3. De factuur wordt geboekt en er wordt een e-mail met bijlage klaar gezet die u kunt versturen. 

## Maak factuur voor verhuur gerelateerde diensten

Wanneer u een factuur aan wilt maken voor verhuurgerelateerde zaken kunt u hier een verhuurfactuur voor aanmaken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Verhuurfacturen** en klik op **Nieuw**. Er wordt een nieuwe verhuurfactuur aangemaakt. 
2. Vul of muteer de volgende velden op de factuur kop:
	- **Klantnaam**
	- **Boekingsomschrijving**: Het onderwerp van de factuur.
	- **Boekingsdatum**
	- **Vervaldatum**: De datum waarop de factuur betaald dient te zijn.
	- **Transactiewijze**: De wijze waarop de factuur betaald wordt. 
3. Vul of muteer de volgende velden in de factuurregel
	- **Soort**: Element
	- **Eenheidnr.**
	- **Contractvolgnr.**: Maak dit veld leeg
	- **Nr.**: Elementnummer waarop de kosten geboekt moeten worden.
	- **Btw- productboekingsgroep**: De btw soort die van toepassing is.
	- **Omschrijving**: De omschrijving van de kosten. Deze omschrijving wordt meegegeven in het grootboek en wordt getoond op de factuur. 
	- **Eenheidsprijs Excl. btw**

## Boeken en versturen verhuur gerelateerde factuur

Nadat u de factuurgegevens gevuld heeft kunt u de verkoopfactuur boeken en versturen. 

1. Klik op **Boeken en afdrukken**. Klik op **Verzenden naar**. Kies voor **PDF-document**. 
3. Sla het PDF document op en verstuur het document via de post of email. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI3MDMzMzkwNl19
-->