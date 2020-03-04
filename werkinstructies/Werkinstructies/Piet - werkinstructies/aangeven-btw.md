# Aangeven BTW

In dit werkproces wordt de BTW-aangifte gegenereerd en geboekt zodat dit kan worden aangegeven bij de belastingdienst en worden betaald.

## Genereren BTW-voorstel

In deze stap wordt een voorstel gemaakt voor welke klanten aangemaand worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Btw-aangiften**. De gelijknamige pagina opent. 
2. Klik op **Voorbeeld**. De pagina **Btw-aangiftevoorbeeld** opent. 
3. Vul de volgende velden:
	-	**Selectie posten o.b.v.**: Documentdatum
	-	**Btw-posten opnemen**: Open
	-	**Btw-posten opnemen**: Tijdens periode
	-	**Datumfilter**: 1 januari van het huidige jaar tot de einddatum waarover u de BTW aan wilt geven.  
4. De kolom **Bedrag** toont het bedrag per BTW-productboekingsgroep dat meegenomen zal worden in de aangifte. Wanneer u op één van de getallen klikt kunt u zien uit welke posten het bedrag opgebouwd is. 

## Genereren BTW-aangifte

In deze stap wordt het rapport met daarop de bedragen die op BTW-aangifte overgenomen kunnen worden gegenereerd.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Btw-aangiften**. De gelijknamige pagina opent. 
2. Klik op **Afdrukken**. De pagina **Btw-aangifte** opent. Vul de volgende velden:
	- **Begindatum**: 1 januari van het huidige jaar. 
	- **Einddatum**: De einddatum van de periode waarover u de BTW aan wilt geven. 
	-	**Btw-posten opnemen**: Open
	-	**Btw-posten opnemen**: Tijdens periode
	-	**Aangiftesjabloon**: Selecteer het aangifte sjabloon.
3. Klik op **Verzenden naar** om de aangifte te openen in PDF.
4. LET OP!! Posten die nog niet aangegeven zijn en een documentdatum hebben in het voorgaande jaar worden niet meegenomen. U kunt de processtap  **[Genereren BTW voorstel](#genereren-btw-voorstel)** uitvoeren met ander datum filter om te zien of er nog aan te geven posten in voorgaande jaren aanwezig zijn. 

## Boeken BTW aangifte

Het boeken van de bedragen op BTW aangifte.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Btw-aangiften**. De pagina **Btw-aangift opent**. 
2. Klik op **Btw-vereffening berekenen en boeken.** De pagina Btw-vereffening berekenen en boeken opent. 
3. Vul de volgende velden: 
 	- **Begindatum**: 1 januari van het huidige jaar. 
	- **Einddatum**: De einddatum van de periode waarover u de BTW aan wilt geven. 
	- **Boekingsdatum**: De datum waarop u de BTW-aangifte wilt boeken. 
	-  **Documentnr.** : Het documentnummer wat u mee wilt geven bij de boeking. 
	- **Vereffeningsrekening**: De rekening waarop de Btw-aangifte geboekt moet worden. 
	- **Boeken**: Kies voor ja wanneer u direct wilt boeken. Kies voor nee wanneer u eerst een voorbeeld wilt genereren. 
4. Klik op **Verzenden naar**. Wanneer u aan heeft gegeven dat u wilt boeken wordt het rapport gegenereerd en wordt de Btw-aangifte geboekt. De Btw-aangifte wordt ook al vordering op de leverancierskaart van de belastingdienst geboekt. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk0MjI2NzY5M119
-->