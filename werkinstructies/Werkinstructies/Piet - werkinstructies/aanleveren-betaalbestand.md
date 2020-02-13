# Aanleveren betaalbestand

In dit detailproces wordt een betaalbestand gegenereerd op basis van uit te betalen klant- en leveranciersposten.

## Processchema

## Ophalen voorstel leveranciersposten

Als u een betaalbestand voor leveranciersposten aan wilt maken dient u aan te geven welke posten meegenomen moeten worden in het betaalbestand. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Telebankieren - bankoverzicht** ana een pan waarna de gelijknamige pagina opent. Vul hier de volgende velden:
	* **Transactiedatum:** Datum waarop de betaling moet plaatsvinden.
	* **Valutadatum:** Posten met een vervaldatum vóór deze datum worden meegenomen in het betaalvoorstel.
	* **Onze bank:** Bank vanaf waar de incasso uitgevoerd wordt.
	* **Rekeningsoort:** 'Leverancier'.
	* **Code:** Selecteer de transactiewijze voor automatisch uitbetalen van leveranciersposten.
5. Klik op **OK**. Het betaalvoorstel wordt aangemaakt en er zal een popup verschijnen met het resultaat.

## Ophalen voorstel klantposten

Als u een betaalbestand voor klantposten aan wilt maken dient u aan te geven welke posten meegenomen moeten worden in het betaalbestand. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Telebankieren - bankoverzicht**.
 2. Klik op **Voorstelposten ophalen**, waarna de gelijknamige pagina opent.
 3. Vul de volgende velden op het scherm:
	* **Transactiedatum:** Datum waarop de betaling moet plaatsvinden.
	* **Valutadatum:** Posten met een vervaldatum vóór deze datum worden meegenomen in het betaalvoorstel.	
	* **Onze bank:** Bank vanaf waar de incasso uitgevoerd wordt.
	* **Rekeningsoort:** 'Klant'.
	* **Code:** Selecteer de transactiewijze voor automatisch uitbetalen van klantposten.
	* **Broncode:** Vul de broncode in wanneer u alleen posten vanuit een bepaalde sub-adminstratie uit wilt betalen, bijvoorbeeld SENV voor service en verbruik.
	* **Documenttype**: 'Creditnota'.
 4. Klik op **OK**. Het betaalvoorstel wordt aangemaakt en er zal een popup verschijnen met het resultaat.

## Controleren en oplossen

er bij de vorige stap foutmeldingen of waarschuwingen n ontstaan bij het aanmaken van het betaalvoorstel, dan dient u deze te controleren en eventueel op te lossen.

 1. Klik op **Voorstel**, waarna de pagina **Telebankiervoorstel** opent.
 2. In de kolom **Foutmelding** ziet u meldingen die u moet oplossen voordat de voorstelregel meegenomen kan worden in het betaalvoorstel.
 3. In de kolom **Waarschuwing** ziet u meldingen die niet blokkerend zijn voor het meenemen van de voorstelregel. Lees deze waarschuwingen door en bepaal of u iets met deze waarschuwing wilt doen of niet. 
 4. Wanneer u foutmeldingen en/of waarschuwingen heeft opgelost selecteert u in het telebankierenvoorstel de functie **Controleren**. Het systeem controleert het voorstel opnieuw op fouten en waarschuwingen. 

## Verwerken voorstel

Wanneer er geen foutmeldingen (meer) in het betaalvoorstel staan kunt u het betaalvoorstel omzetten naar een betaalrun. 

 1. Klik op **Voorstel**, waarna de pagina **Telebankiervoorstel** opent.
 2. Klik op **Verwerken**, waarna de betaalrun wordt aangemaakt. Er verschijnt een popup met het resultaat. 

## Controleren betaalrun
 
Nadat u de betaalrun aangemaakt heeft kunt u deze (laten) controleren.

 1. Klik op de pagina  **Telebankieren - bankoverzicht** op **Betaalrun**. De pagina **Betaalrunlijst** opent. De laatst aangemaakte betaalrun staat onderaan in de lijst. 
 2. Klik op de actie **Betaalrun afdrukken** om de betaalrun af te drukken. 

## Annuleren betaalrunregels

Wanneer naar aanleiding van het controleren van de betaalrun blijkt dat één of meerdere regels niet meegenomen moeten worden in de betaalrun, kunt u individuele regels annuleren zonder de hele betaalrun te hoeven annuleren. 

 1. Selecteer in de lijst **etaalrunlijst** (de betaalrun waaruit u regels wilt annuleren en k op Bbewerken**. 
 2. In het scherm **Betaalrunkaart** kunt u de regels vinden die u wilt annuleren. Noteer hiervan de nummers.
 3. Klik op **Status wijzigen**, waarna h. Het scherm **Betaalrun - status wijzigen** opent. Vul hier de volgende velden:
	* **Nieuwe status:** 'Geannuleerd'
	* **Onze bank:** (laat ongewijzigd)
	* **Runnummer:** (laat ongewijzigd)
	* **Regelnr.:** Vul hier de regelnummers in van de regels die u wilt annuleren.
4. Klik op **OK**. De regels krijgen de status 'Geannuleerd' en worden niet meegenomen wanneer u de betaalrun exporteert. 

## Annuleren betaalrun

Wanneer naar aanleiding van het controleren van de betaalrun blijkt dat de betaalrun opnieuw gegenereerd moet worden dient u de betaalrun in zijn geheel te annuleren. 

 1. Selecteer in de lijst **etaalrunlijst** de betaalrun waaruit u regels wilt annuleren en klidruk op **Bbewerken**. 
 2. Klik op **Status wijzigen**et scherm **Betaalrun - status wijzigen** opent. Vul hier de volgende velden:
	* **Nieuwe status:** 'Geannuleerd'
	* **Onze bank:** (laat ongewijzigd)
	* **Runnummer:** (laat ongewijzigd)
4. Klik op **OK**. De status van de betaalrunregels wordt aangepast naar 'Geannuleerd'.  

## Exporteren betaalrun

Wanneer de betaalrun gecontroleerd en goed bevonden is, kan deze geëxporteerd worden om vervolgens in de applicatie van de bank ingelezen te worden. 

 1. Selecteer in de lijst **Bbetaalrunlijst** de betaalrun die u wilt exporteren. 
 2.  Klik op **Exporteren**. Het scherm **Exporteren PAIN** opent. 
 3. Klik op **OK**. Het PAIN-bestand wordt opgeslagen op de in de exportprotocollen gedefinieerde locatie.

## Zie ook:
Aanleveren incassobestand  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUzMTUxMzI1OCwtMjM1ODc3ODksLTMxMz
YxMDAyOSwtMjY3ODA4Nzk1LDExNTYwOTYwOTEsNjg2NDkyNDM4
LC0xODQ0MDg2MTc5LDEyMzc4MDg5MDAsOTQ2MjY1MzQyLC0xMT
QzMDUzOTk0LDExNTQ0ODU0NDBdfQ==
-->