# Verwerken pintransacties

In dit werkproces worden één of meerdere pintransacties verwerkt. 

## Processchema

## Aanmaken kasdagboek

Om te beginnen met het verwerken van de bankmutaties moet als eerste een bankboek aangemaakt worden. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Kasboek**.
 2. Klik op **Nieuw**. 
 3. Selecteer op de pagina **Fin. dagboeksjablonenoverzicht** het dagboeksjabloon voor de pinautomaat waarmee de betaling voldaan is.
 4.  Klik op **OK** waarna de pagina **Kasboek** opent.
 5. Vul de volgende velden:
	* **Beginsalo:** '0'.
	* **Eindsaldo:** Het bedrag dat gepind is.

## Aanmaken kasdagboekregels

Nadat u het kasdagboek aangemaakt heeft kunt u op de regels de pintransacties toewijzen aan een klant en afletteren met klantposten. 

 1. Vul op de regel de volgende velden:
	* **Rekeningsoort:** 'Klant'.
	* **Rekeningnr.:** Het nummer van de klant: Klantnummer. 
	* **Credit:** Het betaalde bedrag.
 2. Komt de klant één specifieke openstaande post betalen, lees dan verder bij punt 3. Betaalt de klant meer dan één openstaande post, lees dan verder vanaf punt 4. 
 3. **Vereffenen met één openstaande post:** 
	* Kklik in het veld **Vereffeningsnr.** op de drie puntjes. Het scherm **Klantposten vereffenen** opent. 
	* Selecteer de post die betaald wordt en klik op **OK**. U komt terug op de pagina **Kasboek**.
	* Ga verder naar stap [**Boeken en afdrukken kasdagboek**](#boeken-en-afdrukken-kasdagboek).
 4. **Betaling vereffenen met meerdere openstaande posten:** 
	* Selecteer de regel en klik op **Posten vereffenen**. De pagina **Klantposten vereffenen** opent. 
	* Selecteer de posten waarmee u de transactiience wilt vereffenen en selecteer **Vereffenings-id instellen**. Het beschikbare bedrag van de transactie wordt toegekend aan de geselecteerde posten, waarbij altijd geprobeerd wordt om de oudste post geheel te vereffenen. Is daarna nog een bedrag beschikbaar, dan wordt geprobeerd de op één naou oudste post geprobeerd te vereffenen. Wilt u het toegekende bedrag per post aanpassen, dan kan dit in het veld **Te vereffenen bedrag**. 
	* Klik op **OK** om de vereffening te bevestigen. U komt terug op de pagina **Kasboek**.
	* Ga verder naar stap [**Boeken en afdrukken kasdagboek**](#boeken-en-afdrukken-kasdagboek).

## Boeken en afdrukken kasdagboek

Nadat u de pintransacties vereffend heeft met één of meerdere klantposten kunt u de transactie boeken en het betaalbewijs afdrukken. 

 1. Klik op **Boek**. U krijgt de vraag of u het dagboek wilt boeken. Deze beantwoordt u met **Ja**.
 2. De regel wordt geboekt. Zijn er regels die een fout veroorzaken, dan krijgt u de vraag of u de foutenlijst af wilt afdrukken. Zijn er geen fouten, dan krijgt u de melding dat het boeken gelukt is. 
 3. De pagina **Verzamelkwitantie** opent. Klik op **Afdrukken**. Afhankelijk van uw instellingen wordt het betaalbewijs direct afgedrukt of dient u eerst de printer te selecteren waarmee u het betaalbewijs wilt afdrukken. 
 4. Na het afdrukken wordt de pagina **Kasboek** gesloten en keert u terug naar de lijst met kasboeken.

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzkyNTQwNTM4LC0xMTk3NjEzMTc1LDE2Mj
E3ODUwMTIsMTMyMTc4NTczNCw3NzA2NDIyMTAsMjA0MjQ2OTUx
NywxNzE3NjcxNjAyLC0xNzU2ODA0MTI1LDM4MTM2ODY1LC01MT
IxMTE1NjYsLTE2MzA2MzE1ODQsNDc5MTI3ODQ2LDI1OTA5NzIw
MywtNzU2NDIyMzUyLC0xNTI1NzAwNjAzLDYyNTAxNDEyNV19
-->