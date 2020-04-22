# Beheren grootboekbudgetten

In dit werkproces worden budgetten aangemaakt en geactualiseerd.

## Aanmaken nieuw budget
Wanneer u een budget voor een nieuwe periode op wilt voeren start u met het aanmaken van een nieuwe budgetperiode. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Grootboekbudgetten** en klik op **Nieuw**. 
2. Geef een **Naam** en een **Omschrijving** op in de desbetreffende kolommen. 
3. De globale dimensies kunnen aan elk budget meegegeven worden. Wilt u ook andere dimensies mee geven, geef dit dan aan in de kolommen **Code budgetdimensie 1 t/m 4**

## Vaststellen budgetten

Nadat u een nieuwe budgetperiode aangemaakt heeft kunt u het budget gaan specificeren. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Grootboekbudgetten** selecteer het budget dat u wilt bewerken en klik op **Budget bewerken**. In dit scherm kunt u handmatig budgetposten opvoeren advies is echter om de budgetten in excel op te voeren en te importeren. 
2. Klik op **Naar Excel exporteren**. Vul in het scherm dat opent de volgende gegevens:
	- **Begindatum**
	- **Aantal perioden**: Wat u hier invult is afhankelijk van de keuze in het veld **Periode lengte**. Kiest u in het veld **Periode lengte** voor 1M. Kies in dit veld dan bijvoorbeeld voor 12 om 12 maanden te exporteren. 
	- **Periode lengte**. Bijvoorbeeld 1M om budgetten per maand te exporteren. 
	- **Kolomdimensies**: Selecteer in het scherm wat opent wanneer u op **...** klikt in de kolom **Geselecteerd** welke dimensies u wilt gebruiken voor het vastleggen van het budget. 
	- Geef onder de tab **Filter; Budgetposten** extra filters op. Bijvoorbeeld een filter o.b.v. grootboekrekeningnr. als alleen budgetten voor bepaalde grootboekrekeningen wilt importeren. 
	- Klik op **OK**. Er wordt een Excel bestand aangemaakt waarin u de budgetten kunt opvoeren. 
3. Open het Excel bestand. Geef in het bestand per grootboekrekening, per dimensie per periode een budget op. 
4. Sla het Excel bestand op. Keer terug naar het budget  door in het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")  **Grootboekbudgetten** in te vullen het budget te selecteren en op **Budget bewerken** te klikken. 
5. Klik op **Vanuit Excel importeren**. Geef in het veld **Optie** aan of u budgetposten wilt vervangen of toevoegen. 
6. Klik op **OK**. Klik op **Kiezen** en selecteer het Excel bestand. Het budget wordt geïmporteerd. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgzNzc0ODYyMF19
-->