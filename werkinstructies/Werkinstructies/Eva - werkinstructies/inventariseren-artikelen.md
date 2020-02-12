# Inventariseren artikelen

Het is gebruikelijk om periodiek (bijvoorbeeld één keer per jaar) de aanwezige magazijnen te herinventariseren. Hierbij wordt de vastgelegde voorraadstand in Dynamics Empire vergeleken met hetgeen daadwerkelijk in de magazijnen aanwezig is. Het doel is om de voorraadstand in Dynamics Empire bij te werken, zodat deze één op één overeenkomt met wat er in de magazijnen aanwezig is. Dit waarborgt dat de waarde klopt en het inkoopvoorstel de juiste waarden geeft.

## Processchema

## Artikelen (her)inventariseren

Uitgangspunt bij het inventarisatiedagboek is dat dit leeg moet zijn voordat er geïnventariseerd wordt. Als er nog regels bestaan moeten deze eerst verwijderd worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Inventarisatiedagboeken**.
2. Selecteer de juiste regel en kies de functie **Voorraad berekenen**.
3. Het filteroverzicht **Voorstelposten ophalen** opent. Vul hier de volgende velden:
	* **Boekingsdatum:** Deze datum wordt automatisch gevuld met de huidige datum en kan indien nodig worden aangepast.
	* **Documentnummer** Geef hier een kenmerk op zoals 'Inventarisatie bus 1'.
4. Voeg via de filteroptie  eventueel specifieke filters voor één of meerdere specifieke artikelen, of voor een specifiek magazijn.
5. Klik op **OK**. De in Dynamics Empire bekende artikel aantallen worden berekend. 

## Corrigeren artikelen

Het aantal artikelen per magazijn wordt nu weergegeven in het inventarisatiedagboek. In de kolom **Aantal (berekend)** staat het bekende aantal artikelen. Indien er negatieve correcties worden uitgevoerd, zullen de bedragen positief getoond worden!

 1. Geef in de kolom **Aantal (inventarisatie)** de werkelijk getelde aantallen op. 
 2. Klik op **Boeken** in het Lint. 
 3. Klik op **Ja** bij de melding **Wilt u dagboekregels boeken?**
 4. Wanneer de boeking succesvol is verlopen krijgt u hiervan een bevestigingsmelding, klik op **OK**. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbNDcxMjM0MTQwLDQyOTYyODkxNCwtMTgzNz
g2MTQ0Nl19
-->