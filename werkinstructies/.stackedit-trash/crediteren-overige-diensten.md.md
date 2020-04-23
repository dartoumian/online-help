# Crediteren overige diensten

In dit werkproces worden de diensten gecrediteerd die geen betrekking hebben op onderhoud, periodieke huur of het verkopen van onroerend goed.


## Maak credit nota voor niet verhuur gerelateerde diensten

Wanneer u een credit nota wilt maken voor niet verhuurgerelateerde zaken kunt u hier een verkoopcreditnota voor aanmaken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Verkoopcreditnota's** en klik op **Nieuw**. Er wordt een nieuwe verkoopcreditnota aangemaakt. 
2. Vul of muteer de volgende velden op de factuur kop:
	- **Klantnaam**
	- **Boekingsomschrijving**: Het onderwerp van de creditnota.
	- **Boekingsdatum**
3. Wanneer u een eerder gefactureerde verkoopfactuur wilt crediteren kunt u dit doen door middel van het kopiëren van de originele factuur. 
	- Klik op **Document kopiëren**. Selecteer in het veld **Documenttype** **Geboekte factuur**. 
	- Selecteer in het veld **Documentnr.** het document wat u wilt kopiëren. 
	- Klik op **OK**. 
	- U kunt nu verder gaan naar de stap **[Boeken en versturen verhuur gerelateerde credit nota](#Boeken-en-versturen-verhuur-gerelateerde-credit-nota)** 
5. Wanneer u geen andere factuur als basis kunt gebruiken voor de factuurregels vul of muteer dan de volgende velden in de factuurregel
	- **Soort**: Grootboekrekening
	- **Nr.**: Grootboek waarop de kosten gecrediteerd dienen te worden. 
	- **Btw- productboekingsgroep**: De btw soort die van toepassing is.
	- **Omschrijving**: De omschrijving van de gecrediteerde kosten. Deze omschrijving wordt meegegeven in het grootboek en wordt getoond op de creditnota. 
	- **Aantal**: 1
	- **Eenheidsprijs Excl. btw**
	 - **Dimensie waarden velden**: Velden die eindigen met de het woord code zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld kunnen worden. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.  

## Boeken en versturen verhuur gerelateerde credit nota

Nadat u de factuurgegevens gevuld heeft kunt u de verkoopcreditnota boeken en versturen. 

1. Klik op **Boeken en verzenden**. 
2. Klik op **...** en selecteer in het veld **E-mail** **Ja (standaardinstellingen gebruiken)**. Klik op **Ok**. Klik op **Ja**. 
3. De creditnota wordt geboekt en er wordt een e-mail met bijlage klaar gezet die u kunt versturen. 

## Maak credit nota voor verhuur gerelateerde diensten

Wanneer u een credit nota aan wilt maken voor verhuurgerelateerde zaken kunt u hier een verhuurcreditnota voor aanmaken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Verhuurcreditnota's** en klik op **Nieuw**. Er wordt een nieuwe verhuurcreditnota aangemaakt. 
2. Vul of muteer de volgende velden op de factuur kop:
	- **Klantnaam**
	- **Boekingsomschrijving**: Het onderwerp van de creditnota.
	- **Boekingsdatum**
3. Wanneer u een eerder gefactureerde verhuurfactuur wilt crediteren kunt u dit doen door middel van het kopiëren van de originele factuur. 
	- Klik op **Document kopiëren**. Selecteer in het veld **Documenttype** **Geboekte factuur**. 
	- Selecteer in het veld **Documentnr.** het document wat u wilt kopiëren. 
	- Klik op **OK**. 
	- U kunt nu verder gaan naar de stap **[Boeken en versturen verhuur gerelateerde credit nota](#Boeken-en-versturen-verhuur-gerelateerde-credit-nota)** 
4. Vul of muteer de volgende velden in de factuurregel
	- **Soort**: Element
	- **Eenheidnr.**
	- **Contractvolgnr.**: Maak dit veld leeg
	- **Nr.**: Elementnummer waarvoor u kosten wilt crediteren.
	- **Btw- productboekingsgroep**: De btw soort die van toepassing is.
	- **Omschrijving**: De omschrijving van de te crediteren kosten. Deze omschrijving wordt meegegeven in het grootboek en wordt getoond op de factuur. 
	- **Eenheidsprijs Excl. btw**

## Boeken en versturen niet verhuur gerelateerde credit nota

Nadat u de factuurgegevens gevuld heeft kunt u de verhuurcreditnota boeken en versturen. 

1. Klik op **Boeken en afdrukken**. Klik op **Verzenden naar**. Kies voor **PDF-document**. 
3. Sla het PDF document op en verstuur het document via de post of email. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MDI4MDQ2MTRdfQ==
-->