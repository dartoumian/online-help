# Periodiek factureren huurovereenkomst

In dit werkproces wordt het overzicht van de te verwachte kasstromen gegenereerd en geanalyseerd.


## Genereren kasstroom prognoseposten

De eerste stap is het genereren van de kasstroom prognoseposten zodat deze in een latere stap gebruikt kunnen worden in rapportages. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de pagina **Cashflowprognoses**.
2. Klik op **Nieuw**, een nieuwe **cashflowprognosekaart** wordt geopend. Vul de volgende velden:
	- **Nr.:** Pas het nummer aan zodat duidelijk is voor welke periode de prognose aangemaakt is. Bijvoorbeeld PROG-0119-1219 voor de periode januari 2019 tot december 2019
	- **Omschrijving:** Geen een omschrijving mee die waaruit blijkt op welke periode de prognose betrekking heeft
	- **Grootboekbudget van:** Datum vanaf wanneer grootboekbudgetten meegenomen moeten worden
	- **Grootboekbudget van:** Grootboekbudget van + 12 maanden
	- **Handmatige betalingen van:** Datum vanaf wanneer project- en leningen Cashflow meegenomen moeten worden
	- **Handmatige betalingen tot:** Handmatige betalingen van + 12 maanden
3. Klik op **Prognoses van projecten laden**. De Cashflow posten vanuit de projecten modulen worden opgehaald
4.  Klik op **Prognoses van financieringen laden** De Cashflow posten vanuit de projecten modulen worden opgehaald
5. Klik op **Cashflowvoorstel**. De pagina **Cashflowvoorstel** wordt geopend. Klik op **Voorstel regels voorstellen**. Het opvraagscherm **Voorstelregels voorstellen** wordt geopend. Vul de volgende waardes:
	- **Cashflowprognose:** Selecteer het bij stap 2 aangemaakte voorstel
	- **Liquide fondsen:** Ja
	- **Cashflow handmatige opbrengsten:** Ja
	- **Cashflow handmatige kosten:** Ja
	- **Budget:** Ja
	- **Budget:** Selecteer het budget dat u wilt gebruiken voor deze cashflowprognose
	- Selecteer **OK** om de cashflowvoorstelregels aan te maken. U keert terug naar de pagina **Cashflowvoorstel**. De regels tonen de voorgestelde cashflowposten.
6. Selecteer **Registreren** op de pagina **Cashflowvoorstel** om de voorgestelde cashflowposten definitief te maken. De posten zijn overgezet naar de tabel **Cashflowprognoseposten** en kunnen gebruikt worden in rapportages.

## Rapporteren kasstroom prognoseposten

Nadat de voorstelposten aangemaakt zijn kan een rapportage o.b.v. de voorstelposten gegenereerd worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de pagina **rapportageschema's**. Selecteer het rapportageschema voor kasstroom prognoses en klik op **Overzicht**. 
2. Vul de volgende velden:
	- **Weergaven per:** Maand
	- **Datum Filter:** Eerste rapportage maand. Bijvoorbeeld 01-01-2010..31-01-2020
	- **Cashflowfilter:** Selecteer de cashflowprognose waarover u wilt rapporteren.
	- Het schema toont per kasstroom categorie de **mutatie per maand**. De onderste 2 regels van het schema tonen de **verwachte mutatie van de liquide middelen**.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzY4MTc0OTQ5XX0=
-->