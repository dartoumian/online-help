# Verwerken pintransacties

In dit werkproces wordt een pintransacties verwerkt. 

## Processchema


## Aanmaken kasdagboek

Om te beginnen met het verwerken van de bankmutaties moet als eerste een bankboek aangemaakt worden. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Kasboek**
 2. Klik op **Nieuw** 
 3. Selecteer op de pagina **Fin.dagboeksjablonenoverzicht** het dagboeksjabloon voor pintransacties
 4.  Klik op **OK**. De pagina **Kasboek**
 5. Vul de volgende velden:
	* **Beginsalo:** 0
	* **Eindsaldo:** Het bedrag dat gepind is

## Aanmaken kasdagboekregels

nadat u het kasdagboek aangemaakt heeft kun u op de regels de pintransacties toewijzen aan een klant en afletteren met klant posten. 

 1. Vul op de regel de volgende velden:
	* **Rekeningsoort:** Klant
	* **Rekeningnr.:**: Klantnummer. 
	* **Credit:** Het betaalde bedrag
 2. Komt de klant één specifieke openstaande post betalen lees dan verder bij punt 3. Betaalt de klant meer dan één openstaande post lees dan verder vanaf punt 4. 
 3. **Betaling vereffenen met één openstaande post:** 
	* klik in het veld **Vereffeningsnr** de drie puntjes. Het scherm **Klantposten vereffenen** opent. 
	* Selecteer de post die betaald wordt en klik op **OK**. U komt terug op de pagina **Kasboek**
	* Ga verder naar stap Boeken en afdrukken kasboek
 4. **Betaling vereffenen met meerdere openstaande posten:** 
	* Selecteer de regel en klik op **Posten vereffenen**. De pagina **Klantposten vereffenen** opent. 
	* Selecteer de posten waarmee u de transience wilt vereffenen en selecteer **Vereffenings-id instellen**. Het beschikbare bedrag van de transactie wordt toegekend aan de geselecteerde posten waarbij altijd geprobeerd word de oudste post geheel te vereffen. Is daarna nog een bedrag beschikbaar dan wordt de op één nou oudste post geprobeerd te vereffenen. Wilt u het toegekende bedrag per post aanpassen dan kan dit in het veld **Te vereffenen bedrag**. 
	* Klik op **OK** om de verffening te bevestigen. U komt terug op de pagina **Kasboek**
	* Ga verder naar stap Boeken en afdrukken kasboek
<hr>

### Boeken en afdrukken kasdagboek

Nadat u de pintransacties vereffend heeft met één of meerdere klantposten kunt u de transactie boeken en het betaalbewijs afdrukken. 

 1. Klik op **Boek**. U krijgt de vraag of u het dagboek wilt boeken. Deze beantwoord u met **Ja. **
 2. De regel wordt geboekt. Zijn er regels die een fout veroorzaken dan krijgt u de vraag of u de foutenlijst af wilt drukken. Zijn er geen fouten krijgt u de melding dat het boeken gelukt is. 
 3. De pagina **Verzamelkwitantie**. opent. Klik op afdrukken. Afhankelijk van uw instellingen wordt het betaalbewijs direct afgedrukt of dient u eerst de printer te selecteren waarmee u het betaalbewijs wilt drukken. 
 4. Na het afdrukken wordt de pagina **Kasboek** gesloten en keert u terug naar het scherm 



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE4Mjg4NTM2NSwtODYwNzQ3NjM1LC00Nz
E4MjMyNTMsMTQwNTAwMDQzNV19
-->