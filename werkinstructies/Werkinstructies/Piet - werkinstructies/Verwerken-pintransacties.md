# Verwerken pin transacties

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
	* Ga verder naar stap Boeken en afdrukken kasboek. 
 3. **Betaling vereffenen met meerdere openstaande posten:** 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU4NTkyOTczNCwxNDA1MDAwNDM1XX0=
-->