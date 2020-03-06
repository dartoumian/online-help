# Factureren onderhoudsdiensten 

In dit werkproces wordt een factuur voor diensten correctief onderhoud gecontroleerd, geboekt en eventueel afgedrukt. 

## Processchema

## Controleren factuur

Vanuit de bedrijfsprocessen **Uitvoeren reparatieonderhoud**, **Uitvoeren mutatieonderhoud** en **Verhuren eenheden** kunnen facturen voor diensten correctief onderhoud gecreëerd worden. Voordat deze facturen geboekt en eventueel verstuurd worden, dient een controle plaats te vinden, waarna een aanvulling of correctie noodzakelijk kan blijken te zijn.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")   naar de lijst **Verkoopfacturen**.
 2. Mogelijk vindt u op deze pagina een filterlijst, specifiek voor te verwerken facturen voor diensten correctief onderhoud. Heeft u geen voorgedefinieerde filterlijst, stel dan een filter in via de filterfunctie ![Filterpictogram](https://docs.microsoft.com/nl-nl/dynamics365/business-central/media/ui-search/filter-icon.png "Pictogram Filter"), waarbij **Onderhoudsverzoeknr.** ongelijk is aan 'leeg' (<>'').
 3. Open de juiste factuur door op het factuurnummer te klikken. De pagina **Verkoopfactuur** wordt geopend.
 4. Controleer de volgende velden op de factuurregels:
	* **BTW-productboekingsgroep**
	* **BTW-correctie**: Wanneer u de betaalde BTW over de kosten wilt terugvorderen vinkt u deze kolom aan.
	* **Omschrijving**: Pas eventueel de omschrijving aan. Dit is de omschrijving die op de factuur komt te staan.
 5. Wilt u meer informatie over het onderhoudsverzoek, kopieer dan het nummer in de kolom **Onderhoudsverzoeknr.** Navigeer via ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijstpagina **Onderhoudsverzoekoverzicht** en gebruik het nummer om het juiste onderhoudsverzoek op te zoeken. 

## Boeken en afdrukken factuur

Wanneer u de factuur wilt versturen naar de klant, bijvoorbeeld in het geval van reparatieonderhoud, dan kunt u de factuur boeken en afdrukken. 

 1. Vanaf de lijst **Verkoopfacturen** (staand op de juiste regel) of vanaf de factuurkaart klikt u op **Boeken en verzenden**.
 2. Klik in de pagina die opent op de drie puntjes '...'. Het scherm **Document verzenden naar** opent. Vul de volgende velden:
	* **E-mail**: 'Ja (prompt voor instellingen)'.
	* **Schijf**: 'PDF'.
 3. Klik op **OK** en klik op **Ja**. De pagina **E-mail verzenden** opent. Wanneer u de e-mail wilt bewerken in Outlook vinkt u **Bewerken in Outlook** aan. 
 4. Klik op **OK**. Afhankelijk van uw keuze in de vorige stap wordt de e-mail direct verzonden of wordt Outlook geopend.

## Boeken factuur

Als de factuur niet afgedrukt hoeft te worden, omdat deze bijvoorbeeld in rekening gebracht wordt via de eindafrekening, kunt u de factuur direct boeken. 

 1. Klik op **Boeken**. De factuur wordt geboekt. De volgende factuur in de te verwerken verkoopfacturen opent. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4ODY4NTE1NzAsLTE5Mjk2NDc3OV19
-->