# Aanleveren incassobestand


## Omschrijving:
In dit detailproces wordt een incassobestand gegenereerd op basis van te incasseren klantposten.

## Processchema

## Processtappen

### Ophalen voorstel klantposten

Als u een incassobestand voor klantposten aan wilt maken, dient u aan te geven welke posten meegenomen moeten worden in het incassobestand. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")  naar de lijst **Telebankieren - bankoverzicht**.
2. Klik op **Voorstelposten ophalen**, waarna de gelijknamige pagina opent.
Vul hi.
3. Vul de volgende velden op het scherm de volgende veldenat verschijnt:
	* **Transactiedatum:** Datum waarop de incasso moet plaatsvinden.
	* **Valutadatum:** Posten met een vervaldatum op of voor deze datum worden meegenomen in het betaalvoorstel. Bij een incasso op de eerste van de maand vult u hier bijvoorbeeld 01-03-2020 in. 
	* **Onze bank:** Bank vanaf waar de incasso uitgevoerd wordt.
	* **Rekeningsoort:** 'Klant'.
	* **Code:** Selecteer de transactiewijze voor automatische incasso voor klantposten.
	* **Onder het kopje Klantposten**:
		* **Broncode:** Vul de broncode in. Voor prolongatie posten is dit 'PROLON', v. Voor service- en verbruiks posten is dit 'e SENV'.
		* **Documenttype:** 'Factuur'.
		* 	**Boekingsdatum:** Wanneer u posten vanuit de prolongatie wilt incasseren vult u hier de boekingsdatum van de prolongatie in. 
4. Klik op **OK**. Het voorstel wordt aangemaakt en er zal een popup verschijnen met het resultaat.

<hr>

### Controleren en oplossen

Als Wanneer bij de vorige stap bleek dat er foutmeldingen of waarschuwingen zijwaren ontstaan bij het aanmaken van het betaalvoorstel, dan dient u deze te controleren en eventueel op te lossen. 

1. Klik op **Voorstel**, waarna de pagina **Telebankiervoorstel** opent.
2. In de kolom **Foutmelding** ziet u meldingen die u moet oplossen voordat de voorstelregel meegenomen kan worden in het betaalvoorstel.
3. In de kolom **Waarschuwing** ziet u meldingen die niet blokkerend zijn voor het meenemen van de voorstelregel. Lees deze waarschuwingen door en bepaal of u iets met deze waarschuwing wilt doen of niet. 
4. Wanneer u foutmeldingen en/of waarschuwingen heeft opgelost selecteert u in het telebankierenvoorstel de functie **Controleren**. Het systeem controleert het voorstel opnieuw op fouten en waarschuwingen. 

<hr>

### Verwerken voorstel

Wanneer er geen foutmeldingen (meer) in het betaalvoorstel staan kunt u het betaalvoorstel omzetten naar een betaalrun. 

1. Klik op **Voorstel**, waarnaOpen de pagina **Telebankiervoorstel** opent.
2. Klik op **Verwerken**, waarna de betaalrun wordt aangemaakt. Er verschijnt een popup met het resultaat. 

<hr>

### Annuleren betaalrunregels

Wanneer naar aanleiding van het controleren van de betaalrun blijkt dat één of meerdere regels niet meegenomen moeten worden in de betaalrun, kunt u individuele regels annuleren zonder de hele betaalrun te hoeven annuleren. 

1. Selecteer in de lijst **Betaalrunlijst** de betaalrun waaruit u regels wilt annuleren en klidruk op **Bewerken.** 
2. In het scherm **Betaalrunkaart** kunt u de regelnummers vinden van de regels die u wilt annuleren. Noteer hiervan de betreffende nummers. 
3. Klik op **Status wijzigen**, waarna h. Het scherm **Betaalrun - status wijzigen** opent. Vul hier de volgende velden:
	* **Nieuwe status:** 'Geannuleerd'.
	* **Onze bank:** (lLaat ongewijzigd).
	* **Runnummer:** (lLaat ongewijzigd).
	* **Regelnr.:** Vul hier de regelnummers in van de regels die u wilt annuleren.
4. Klik op **OK**. De regels krijgen de status '**Geannuleerd'** en worden niet meegenomen wanneer u de betaalrun exporteert. 

<hr>

### Annuleren betaalrun

Wanneer naar aanleiding van het controleren van de betaalrun blijkt dat de betaalrun opnieuw gegenereerd moet worden, dient u de betaalrun in zijn geheel te annuleren. 

 1. Selecteer in de lijst **Betaalrunlijst** de betaalrun waaruit u regels wilt annuleren en klidruk op 'Bbewerken'. 
 2. Klik op **Status wijzigen**. Het scherm **Betaalrun - status wijzigen** opent. Vul hier de volgende velden:
	* **Nieuwe status:** 'Geannuleerd'.
	* **Onze bank:** (lLaat ongewijzigd).
	* **Runnummer:** (lLaat ongewijzigd).
  4. Klik op **OK**. De status van de betaalrunregels wordt aangepast naar **Geannuleerd**.  

<hr>

### Exporteren betaalrun

Wanneer de betaalrun gecontroleerd en goed bevonden is, kan deze geëxporteerd worden om vervolgens in de applicatie van de bank ingelezen te worden. 

 1. Selecteer in de lijst **Betaalrunlijst** de betaalrun die u wilt exporteren. 
 2.  Klik op **Exporteren**. Het scherm **Exporteren PAIN** opent. 
 3. Klik op **OK**. Het PAIN-bestand word opgeslagen op de in de exportprotocollen gedefinieerde locatie.

<hr>

## Zie ook:
Aanleveren betaalbestand  

<!--stackedit_data:
eyJoaXN0b3J5IjpbNjUzMTU2NTQ0LC03NjU0MDcwMzVdfQ==
-->