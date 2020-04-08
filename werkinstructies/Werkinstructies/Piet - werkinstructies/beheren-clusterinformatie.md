# Beheren clusterinformatie

In dit werkproces worden nieuwe clusters aangemaakt en worden bestaande clusters beheerd.


## Aanmaken cluster

In deze stap maakt u een nieuw cluster aan en voert u de benodigde basis gegevens op.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Klik op **Nieuw** om een nieuwe clusterkaart aan te maken. Druk op **Enter**. Selecteer in het scherm dat opent de clustersoort wat van toepassing is op het nieuwe cluster en klik op **OK**.
2. U keert terug naar de pagina **Cluster**. Het clusternummer wordt automatisch toegekend. Was het clusternummer desgewenst aan. 

## Aanpassen basis gegevens

In deze stap worden de basisgegevens van het cluster opgevoerd of aangepast. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart van het cluster waarvoor u basisgegevens aan wilt passen. 
2. De volgende basis gevegevens dient u bij nieuwe clusters op te voeren en kunt u desgewenst aanpassen:
	- **Naam**
	- **Onderdeel van cluster**: Alleen bij clusters van het clustersoort **Bouwblok**.
	- **Divisie**: Alleen wanneer u gebruikt maakt van divisies
	- **Service bureau**: Alleen wanneer het een service of verbruik cluster betreft en de afrekening (gedeeltelijk) plaats vind via een servicebureau. 
	- **Budgethouder**: Alleen wanneer de clustersoort gekenmerkt is als 'technisch'. 
3. **Dimensiewaarde** kunt u toevoegen of wijzigen door op **Dimensies** te klikken. 
	-  Geef in de kolom **Dimensiecode** aan welke type dimensiewaarde u toe wilt voegen. 
	- Geef in de kolom **Dimensiewaardecode** de dimensiewaarde op. 
4. Wanneer het cluster gebruik wordt op contactpersonen te koppelen aan eenheden kunt u onder de tab **Contactbeheer** medewerkers of andere contact personen toevoegen of verwijderen. 
	- Selecteer in de kolom **Functie** de functie van de contactpersoon
	- Selecteer in de kolom **Contactnr.** de contactpersoon. 

## Toevoegen Onroerend goed eenheid 

In deze stap worden eenheden toegevoegd aan een cluster. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart van het cluster waaraan u eenheden toe wilt voegen. Klik op **Eenheden toevoegen**. 
2. Selecteer op de pagina die opent de eenheden die u toe wilt voegen aan het cluster en klik op **OK**. Wanneer de clustersoort van het cluster waaraan u eenheden toegevoegd heeft het kenmerk 'financieel' heeft krijgt u een waarschuwing dat mogelijk clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaats vinden. 

## Verwijderen onroerend goed eenheid 

In deze stap worden eenheden verwijderd uit een cluster

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart van het cluster waaruit u eenheden toe wilt verwijderen. Klik op **Eenheden**. 
2. Selecteer de eenheden die u wilt verwijderen en klik op **Verwijderen**. Klik op **Sluiten** om terug te keren naar de clusterkaart. Wanneer de clustersoort van het cluster waaraan u eenheden toegevoegd heeft het kenmerk 'financieel' heeft krijgt u een waarschuwing dat mogelijk clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaats vinden. 

## Toevoegen collectief object

In deze stap worden collectieve objecten toegevoegd aan een cluster. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart van het cluster waaraan u collectieve objecten toe wilt voegen. Klik op **Collectieve objecten toevoegen**. 
2. Selecteer op de pagina die opent de collectieve objecten die u toe wilt voegen aan het cluster en klik op **OK**. Wanneer de clustersoort van het cluster waaraan u collectieve objecten toegevoegd heeft het kenmerk 'financieel' heeft krijgt u een waarschuwing dat mogelijk clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaats vinden. 

## Verwijderen collectief object 

In deze stap worden collectieve objecten verwijderd uit een cluster

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart van het cluster waaruit u collectieve objecten toe wilt verwijderen. Klik op **Eenheden**. 
2. Selecteer de collectieve objecten die u wilt verwijderen en klik op **Verwijderen**. Klik op **Sluiten** om terug te keren naar de clusterkaart. Wanneer de clustersoort van het cluster waaraan u eenheden toegevoegd heeft het kenmerk 'financieel' heeft krijgt u een waarschuwing dat mogelijk clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaats vinden. 

## Aanmaken clusterverdeelsleutels

In deze stap worden de eerste clusterverdeelsleutels aangemaakt. Dit hoeft alleen te gebeuren wanner de clustersoort van het cluster het kenmerk 'financieel' heeft. Alleen eenheden die in exploitatie zijn (status = verhuurd of leegstand) worden toegevoegd aan een clusterverdeelsleutel. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart waarvoor u clusterverdeelsleutels aan wilt maken. Klik op **Clusterverdeelsleutels**. 
2. Klik op **Nieuw** en vul de volgende velden op de **Clusterverdeelsleutelkaart**:
	- **Verdeelsleuteltype**
	- **Ingangsdatum**: Advies is om hier altijd te kiezen voor 1 januari van het huidige jaar. 
3. Wanneer u bij het verdeelsleutel type gekozen heeft voor een type dat niet gelijk is aan lineair dient u de wegingsfactoren per eenheid op te geven. U kunt de wegingsfactor opgeven in de kolom **Teller**. 
4. Klik op **Verdeelsleutel activeren** om de verdeelsleutel te activeren. 
5. Herhaal stap 2 t/m 4 wanneer u verdeelsleutels met verschillenden verdeelsleuteltypes aan wilt maken. 

## Actualiseren individuele clusterverdeelsleutels

Wanneer u in een eerdere stap eenheden toegevoegd heeft aan het cluster of verwijderd heeft uit het cluster en er waren al clusterverdeelsleutels aanwezig voor het cluster kunt u de clusterverdeelsleutels behorende bij het cluster actualiseren. Alleen eenheden die in exploitatie zijn (status = verhuurd of leegstand) worden toegevoegd aan een clusterverdeelsleutel. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Clusteroverzicht**. Open de clusterkaart waarvoor u clusterverdeelsleutels wilt actualiseren. Klik op **Clusterverdeelsleutels**. 
2. Selecteer de meest recente clusterverdeelsleutel van het clusterverdeelsleutel type. Klik op **Verdeelsleutel actualiseren**. De nieuwe clusterverdeelsleutelkaart wordt geopend. 
3. Vul in het veld **Ingangsdatum** de ingangsdatum van de nieuwe verdeelsleutel in. Deze moet altijd na vandaag liggen. 
4. Wanneer u eenheden toegevoegd hebt aan het cluster en het type verdeelsleutel is niet LINEAIR dan dient u in de kolom **Teller** de wegingsfactor voor de nieuwe eenheden op te geven. 
5. Klik op **Verdeelsleutel activeren** om de verdeelsleutel te activeren. 
6. Herhaal stap 2 t/m 5 wanneer u verdeelsleutels met verschillenden verdeelsleuteltypes wilt actualiseren.

## Muteren Service en verbruik elementen

Wanneer u cluster gebruikt wordt binnen het proces 'Service en verbruik afrekening' dienen de elementen die afgerekend worden beheerd te worden. Deze processtap beschrijft hoe u elementen toekent aan een cluster en hou u deze elementen beheerd. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar de pagina **Elementen**. Kies in het veld **Elementsjabloon** voor **Cluster** en vul in het veld **Clusternummer** het clusternummer waarvoor u elementen wilt muteren. 
2. Wanneer u een nieuwe element wilt toevoegen aan een cluster vult u in de regel in het veld **Nr.** het elementnummer in. Klik daarna in de lege regel onder de nieuw aangemaakte regel om de regel te activeren. 
3. In de kolom **Teller bepalen** geeft u aan op welke wijze de kosten die betrekking hebben op het element verdeeld dienen te worden. Er zijn 3 opties:
	- **Handmatig**: U geeft per eenheid aan hoeveel kosten toegerekend dienen te worden
	- **Voorschot (berekend)**: De kosten worden verdeeld o.b.v. het betaalde voorschot
	- **Lineair**: De kosten worden lineair verdeeld over alle eenheden. Elke eenheid krijg even veel kosten toegerekend. 
4. Wanneer in de kolom **Teller bepalen** gekozen is voor **Handmatig** kunt u de verdeling per eenheid aanpassen door op **Tellers** te klikken. Onder de tab **Teller per OG eenheid** geeft u in de kolom **Teller** de weging per eenheid op. Wanneer u de tellers aangepast heeft klikt u op F5 om de pagina te verversen. De waarde in het veld **Noemer berekend** is bijgewerkt. Kopieer de waarde uit het veld **Noemer berekend** en plak deze waarde in het veld **Noemer**. Klik op **Sluiten** om terug te keren naar de pagina **Elementen**
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NDYxMTI4OTZdfQ==
-->