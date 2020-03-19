# Afsluiten jaar

In dit werkproces worden alle de balansmutaties verwerkt en wordt de winst- en verliesrekening afgesloten.

## Afsluiten jaar

Het afsluiten van de boekingsperiode van het afgelopen jaar, zodat boekingen die hierna nog worden gemaakt in het afgelopen jaar worden gekenmerkt.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Boekingsperioden**. Klik op **Jaar afsluiten**. 
2. Maak wanneer nodig alvast een nieuw boekjaar aan door op **Nieuw jaar** te klikken. Vul de volgende velden op de pagina die opent:
	-	**Begindatum**
	-	**Aantal perioden**: 12
	-	**Periode lengte**: 1M
3. Klik op **OK**. 

## Instellen grootboek t.b.v. afsluitboekingen

Voordat de eindejaarsboekingen gemaakt kunnen worden dient eerst het grootboek ingesteld te worden voor deze boekingen. Advies is om deze handelingen uit te voeren na reguliere kantooruren. In deze processtap worden namelijk de dimensie verplichtingen van het grootboek afgehaald en worden de vinkjes m.b.t. direct boeken op grootboekrekeningen aangepast. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Configuratiepakketten** en selecteer het pakket wat betrekking heeft op de jaarafsluiting. Open dit pakket. Dit pakket bevat 2 tabellen:
	-	Tabel Nr. 15: Grootboekrekeningen
	-	Tabel Nr. 352: Standaard dimensies
2. Klik op **Pakket exporteren** en sla het pakket op. Dit pakker bevat de inrichting van de 2 tabellen op dit moment. Dit pakket kunt u later gebruiken om  de inrichting terug te zetten. 
3. Klik op **Naar Excel exporteren** en sla het geëxporteerde bestand op. 
4. Open het geëxporteerde Excel bestand:
	- Zet in het tabblad **Grootboekrekening** de kolom **Direct boeken** op **Waar**. 
	- Maak in het tabblad **Standaard dimensie** de kolommen **Dimensiewaarde code**, **Waardeboeking** en **Meervoudige-selectie actie** leeg. 
	- Sla het Excel bestand op. 
5. Ga terug naar het RapidStart pakket en klik op **Vanuit Excel importeren**. Klik in het scherm wat opent op **Import**. 
6. Klik vervolgens op **Pakket toepassen** en de geïmporteerde inrichting toe te passen.

## Boeken naar beginbalans rekeningen

De eerste stap in het boeken van de jaarafsluiting is het boeken naar de beginbalans rekeningen t.b.v. het RGS. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Periodieke daboeken**. Selecteer in het scherm wat open in het veld **Batchnaam** de batch voor het boeken van de beginbalans. 
2. Controleer de **boekingsdatum** van de regels. Deze zouden op 31-12 van het af te sluiten jaar moeten staan. Pas indien nodig aan. 
3. Klik op **Boeken** om de boekingen uit te voeren. 

## Afsluiten winst- en verliesrekening 

Nadat de beginbalans boekingen gemaakt zijn kan de Winst en Verlies rekening afgesloten worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Afsluiten WenV-rekening**. Vul in de pagina die opent de volgende velden:
	- **Einddatum boekjaar**
	- **Fin. dagboeksjabloon**: Het dagboek wat u wilt gebruiken voor deze boeking. 
	- **Fin. dagboekbatch**; De dagboekbatch die u wilt gebruiken voor deze boeking. 
	- **Documentnummer**
	- **Resultaat lopend boekjaar**: De rekening waarop u het resultaat wilt boeken. 
	- **Boekingsomschrijving**
2. Klik op **OK**. De regels worden klaargezet in het dagboek wat u opgegeven hebt. 
3. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Diversendagboek** en selecteer het dagboek waarin u de regels klaargezet heeft. Selecteer wanneer nodig de juiste batch in het veld **Batchnaam**. 
4. Klik op **Boeken** om de winst- en verliesrekening te boeken. 

## Terugzetten grootboekinstellingen

Nadat u de boekingen t.b.v. de jaarafsluiting verwerkt heeft dient u de instellingen die u in de eerste stap aanpast heeft terug te zetten. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Configuratiepakketten** klik op  **Pakket importeren**. 
2. Open het pakket en klik op **Pakket toepassen**. De instellingen worden terug gezet. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTIxMDcwNTYxXX0=
-->