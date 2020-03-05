# Aangeven BTW

In dit werkproces wordt de BTW-aangifte gegenereerd en geboekt zodat dit kan worden aangegeven bij de belastingdienst en worden betaald.

## Genereren BTW-voorstel

In deze stap wordt een voorstel gemaakt voor welke klanten aangemaand worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Btw-aangiften**. De gelijknamige pagina opent. 
2. Klik op **Voorbeeld**. De pagina **Btw-aangiftevoorbeeld** opent. 
3. Vul de volgende velden met de aangegeven waarden:
	-	**Selectie posten o.b.v.**: 'Documentdatum'
	-	**Btw-posten opnemen**: 'Open'
	-	**Btw-posten opnemen**: 'Tijdens periode'
	-	**Datumfilter**: 1 januari van het huidige jaar tot de einddatum waarover u de BTW aan wilt geven (voorbeeld: '01-01-2020..31-05-2020')
4. De kolom **Bedrag** toont het bedrag per BTW-productboekingsgroep dat meegenomen zal worden in de aangifte. Wanneer u op één van de getallen klikt kunt u zien uit welke posten het bedrag opgebouwd is. 

## Genereren BTW-aangifte

In deze stap wordt het rapport met daarop de bedragen die op BTW-aangifte overgenomen kunnen worden gegenereerd.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Btw-aangiften**. De gelijknamige pagina opent. 
2. Klik op **Afdrukken**. De pagina **Btw-aangifte** opent. Vul de volgende velden met de aangegeven waarden:
	- **Begindatum**: 1 januari van het huidige jaar.
	- **Einddatum**: De einddatum van de periode waarover u de BTW aan wilt geven. 
	-	**Btw-posten opnemen**: 'Open'
	-	**Btw-posten opnemen**: 'Tijdens periode'
	-	**Aangiftesjabloon**: Selecteer het aangiftesjabloon.
3. Klik op **Verzenden naar** om de aangifte te openen in PDF.
>**LET OP!** Posten die nog niet aangegeven zijn en een documentdatum hebben in het voorgaande jaar worden niet meegenomen. U kunt de processtap  **[Genereren BTW voorstel](#genereren-btw-voorstel)** uitvoeren met ander datumfilter om te zien of er nog aan te geven posten in voorgaande jaren aanwezig zijn. 

## Boeken BTW-aangifte

Dit betreft het boeken van de bedragen op de BTW-aangifte.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Btw-aangiften**. De gelijknamige pagina opent. 
2. Klik op **Btw-vereffening berekenen en boeken.** De gelijknamige pagina opent. 
3. Vul de volgende velden: 
 	- **Begindatum**: 1 januari van het huidige jaar
	- **Einddatum**: Dit is de einddatum van de periode waarover u de BTW aan wilt geven. 
	- **Boekingsdatum**: Dit is de datum waarop u de BTW-aangifte wilt boeken. 
	-  **Documentnr.** : Hier vermeldt u het documentnummer dat u mee wilt geven bij de boeking. 
	- **Vereffeningsrekening**: Dit is de rekening waarop de BTW-aangifte geboekt moet worden. 
	- **Boeken**: Kies voor **Ja** als u direct wilt boeken. Kies voor **Nee** als u eerst een voorbeeld wilt genereren.
4. Klik op **Verzenden naar**. Wanneer u heeft aangegeven dat u wilt boeken wordt het rapport gegenereerd en wordt de BTW-aangifte geboekt. De aangifte wordt ook als vordering op de leverancierskaart van de belastingdienst geboekt. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzQxMjUyMDQ2LC00NTA4OTI5MzQsMTA3Nz
Y1Mzg0Ml19
-->