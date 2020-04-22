# Factureren verkoop onroerend goed

In dit werkproces wordt het verkocht onroerend goed gefactureerd.


## Genereren verkoopfactuur

Het verkoopproces van onroerend goed wordt afgesloten door het aanmaken en boeken van de verkoopfactuur. De verkoopfactuur wordt aangemaakt vanaf de verkoop aanbieding. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Onr. Goed-Eenhedenoverzicht**. 
2. Selecteer de eenheid waarvoor u de verkoopfactuur aan wilt maken en klik op **Verkoopaanbiedingen**. 
3. Open de aanbieding waarvoor u de verkoopfactuur aan wilt maken. 
4. Klik op **Verkoopfactuur maken** om de verkoopfactuur aan te maken. De verkoopfactuur is aangemaakt. 

## Aanvullen factuur 

Nadat de factuur aangemaakt is kunt u de factuur controleren en aanvullen. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Onr. Goed-Eenhedenoverzicht**. 
2. Selecteer de eenheid waarvoor u de verkoopfactuur wilt aanvullen en klik op **Verkoopaanbiedingen**. 
3. Open de aanbieding waarvoor u de verkoopfactuur wilt aanvullen 
4. Klik op **Verkoopfactuur** De verkoopfactuur wordt geopend. 
5. Vul de volgende gegevens op de factuur kop aan:
	- **Verkoopkosten**
	- **Boekingomschrijving**
	- **Reden uit exploitatie**
	- **Boekings -/ Stukdatum**
	- **Documentdatum**
	- **Extern stuknummer** (niet verplicht)
	- **Transportdatum**
	- **Definitief getransportation**: Zet optie aan. 
6. Vul de factuurregels aan met bijvoorbeeld de verkoop- of makelaarskosten. Selecteer een nieuwe regel en vul de volgende velden. 
	- **Soort**: Grootboekrekening
	- **Nr.**: De rekening waarop de kosten of opbrengsten geboekt moeten worden
	- **Omschrijving**
	- **Btw-productboekingsgroep**
	- **Aantal**: Wanneer het kosten betreft vul hier dan -1 in. Betreft het opbrengsten vul dan 1 in.
	- **Eenheidsprijs Exc. btw**
	- **Dimensie waarden velden**: Velden die eindigen met de het woord code zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld kunnen worden. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.  
7. Wanneer alle gegevens gecontroleerd en aangevuld zijn kunt u de factuur ter goedkeuring aanbieden. Klik op **Goedkeuringsaanvraag verzenden**. De goedkeuringsaanvraag wordt verzonden. 

## Boeken en versturen factuur 

Nadat de factuur goedgekeurd is kunt u de factuur boeken. 
1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Verkoopfacturen**. 
2. Selecteer de factuur die u wilt boeken en klik op **Boeken en verzenden**. 
2. Klik op **...** en selecteer in het veld **E-mail** **Ja (standaardinstellingen gebruiken)**. Klik op **Ok**. Klik op **Ja**. 
3. De factuur wordt geboekt en er wordt een e-mail met bijlage klaar gezet die u kunt versturen. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgzNzM1Mzk5NF19
-->