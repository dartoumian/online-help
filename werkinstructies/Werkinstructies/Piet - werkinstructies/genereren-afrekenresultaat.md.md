# Generen afrekenresultaat

In dit werkproces worden de afgerekende service- en verbruikskosten en opbrengsten overgeboekt van de balans naar het resultaat.
>Let op. Voer dit proces alleen uit wanneer u alle afrekeningen voor deze afrekenperiode geboekt heeft. 

## Aanpassen periode afrekenbatch

Voordat u het resultaat kunt verwerken dient u de periode van de afrekenbatch waarvoor u het resultaat wilt verwerken op te rekken. Dit doet u om posten die niet verder verdeeld hoeven en een boekingsdatum buiten de afrekenperiode hebben maar die wel meegenomen moeten worden in het resultaat mee genomen worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **SV-afrekenbatches** en klik op **Bewerken**. 
2. Selecteer de afrekenbatch waarvoor u het resultaat wilt boeken en zet de waarde in kolom **Einddatum periode 1** op 1 jaar verder. 

## Aanmaken en boeken afrekenresultaat

In deze processtap zet u alle kosten die meegenomen dienen te worden in het resultaat goed, maakt u een voorstel voor het afrekenresultaat en boekt u het afrekenresultaat. 

1. Als eerste dient u er zeker van te zijn dat kosten in het cluster waarvoor u het resultaat wilt gaan boeken en die niet verder verdeeld hoeven te worden betrekking hebben op de te verwerken periode. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **SV-kostenselectie**. 
2. Stel een filter in op  **Clusternr. ** voor het cluster waarvoor u kosten wilt beoordelen. 
3. Stel een filter in op posten waarbij de kolom **Afrekenbach** leeg is (''). 
4. Bepaal of al deze posten betrekking hebben op de periode waarvoor u het resultaat wilt verwerken. Bevat dit gefilterde overzicht posten die geen betrekking hebben op de af te rekenen periode vul dan in het veld **Afrekenbatchnaam** de periode in waarop de posten wel betrekking hebben. Laat de afrekenbatch leeg voor de posten die wel meegenomen dienen te worden in het verwerken van het resultaat. 
5. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **SV-afrekeningenoverzicht** en klik op **Aanmaken SV-afrek.resultaat**. 
6. Selecteer op de pagina die opent in het veld **Batchnaam** de batch waarvoor u het resultaat wilt verwerken. 
7. Wanneer u met clustergroepen werk selecteert u in het veld **Clustegroepfilter** de clustergroep waarvoor u de kosten wilt verdelen. 
8. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusterfilter** het cluster waarvoor u de kosten wilt verdelen. 
9. Vul in het veld **Boekingsdatum** de datum waarop u het resultaat wilt boeken. 
10. Geef een documentnummer. Dit is het documentnummer wat meegegeven wordt in de boeking op het grootboek. 
11. Laat de optie **Alleen niet verder te verdelen kosten verwerken** uit staan. 
12. Klik op **OK. ** Het voorstel voor de resultaatboeking wordt klaargezet in het overzicht **SV-afrekenresultaat**
13. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **SV-afrekenresultaat**. Dit overzicht toont alle geboekte en nog te boeken afrekenresultaten. Het kenmerk **Verwerkt** geeft aan of een resultaat al geboekt is. 
14. Klik op **Boeken** om de nog niet verwerkte afrekenresultaten te boeken. 
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTU2ODQ1NzE1XX0=
-->