# Prognosticeren kasstromen

In dit werkproces wordt het overzicht van de te verwachte kasstromen gegenereerd en geanalyseerd.


## Genereren kasstroom prognoseposten

De eerste stap is het genereren van de kasstroom prognoseposten, zodat deze in een latere stap gebruikt kunnen worden in rapportages. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de pagina **Cashflowprognoses**.
2. Klik op **Nieuw**, een nieuwe **cashflowprognosekaart** wordt geopend. Vul de volgende velden:
	- **Nr.**: Pas het nummer aan, zodat duidelijk is voor welke periode de prognose aangemaakt is. Bijvoorbeeld PROG-0119-1219 voor de periode januari 2019 tot december 2019.
	- **Omschrijving**: Geef een omschrijving mee waaruit blijkt op welke periode de prognose betrekking heeft.
	- **Grootboekbudget van**: Datum vanaf wanneer grootboekbudgetten meegenomen moeten worden.
	- **Grootboekbudget tot**: Grootboekbudget van + 12 maanden.
	- **Handmatige betalingen van**: Datum vanaf wanneer project- en leningencashflow meegenomen moet worden.
	- **Handmatige betalingen tot**: Handmatige betalingen van + 12 maanden.
3. Kies voor de actie **Prognoses van projecten laden**. De cashflowposten vanuit de projectenmodulen worden opgehaald.
4.  Klik op **Prognoses van financieringen laden**. De cashflowposten vanuit de projectenmodulen worden opgehaald.
5. Klik op **Cashflowvoorstel**. De gelijknamige pagina  wordt geopend. Kies nu voor het proces **Voorstelregels voorstellen**, waarna de gelijknamige pagina wordt geopend. Vul de volgende waarden:
	- **Cashflowprognose**: Selecteer het bij stap 2 aangemaakte voorstel.
	- **Liquide middelen**: 'Aan'.
	- **Cashflow handmatige opbrengsten**: 'Aan'.
	- **Cashflow handmatige kosten**: 'Aan'.
	- **Budget**: 'Aan'.
	- **Budget**: Selecteer het budget dat u wilt gebruiken voor deze cashflowprognose.
	- Selecteer **OK** om de cashflowvoorstelregels aan te maken. U keert terug naar de pagina **Cashflowvoorstel**. De regels tonen de voorgestelde cashflowposten.
6. Selecteer **Registreren** op de pagina **Cashflowvoorstel** om de voorgestelde cashflowposten definitief te maken. De posten zijn overgezet naar de tabel **Cashflowprognoseposten** en kunnen gebruikt worden in rapportages.

## Rapporteren kasstroom prognoseposten

Nadat de voorstelposten aangemaakt zijn kan een rapportage o.b.v. de voorstelposten gegenereerd worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de pagina **Rapportageschema's**. Selecteer het rapportageschema voor kasstroomprognoses en kies voor proces **Overzicht**. 
2. Vul de volgende velden:
	- **Weergaven per:** 'Maand'.
	- **Datum Filter:** Eerste rapportagemaand, bijvoorbeeld 01-01-2010..31-01-2020.
	- **Cashflowfilter:** Selecteer de cashflowprognose waarover u wilt rapporteren.
	- Het schema toont per kasstroomcategorie de **Mutatie per maand**. De onderste twee regels van het schema tonen de **verwachte mutatie van de liquide middelen**.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxNDY5NjAxODIsLTQ5OTk3NDcxOF19
-->