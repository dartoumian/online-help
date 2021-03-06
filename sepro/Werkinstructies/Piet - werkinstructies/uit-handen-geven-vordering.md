
# Uit handen geven vordering

In dit werkproces worden vorderingen op klanten uit handen gegeven aan een deurwaarder en wordt de voortgang van het dossier bijgehouden.

## Processchema

## Opvoeren deurwaarderdossier

U kunt handmatig een deurwaarderdossier opvoeren. In veel gevallen zal een deurwaarderdossier echter automatisch aangemaakt zijn vanuit het aanmaningsproces. In dat geval gaat u verder met **[Controleren deurwaarderdossier](#controleren-deurwaarderdossier)**.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Klanten**.
2. Selecteer de klant waarvoor u een deurwaarderdossier aan wilt maken. Klik op **Deurwaarderdossiers**, waarna de gelijknamige  pagina opent.
3. Klik op **Nieuw** waarna een nieuw deurwaarderdossier voor de klant wordt aangemaakt. 
4. Controleer of het veld **Deurwaardernr.** gevuld is met de juiste deurwaarder.
5. Klik op **Posten Selecteren**. De pagina **Klantposten** opent. Selecteer de posten die opgenomen moeten worden in het dossier. Klik op **OK**, waarna u terugkeert naar het dossier. 
6. Als de gegevens ingevuld zijn, ga dan verder met **[Versturen deurwaarderdossier](#versturen-deurwaarderdossier)**.

## Controleren deurwaarderdossier

Vanuit het aanmaningsproces kunnen deurwaarderdossiers automatisch aangemaakt worden. Deze aanmaning kunt u controleren voordat u ze verstuur naar de deurwaarder. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de  **Deurwaarderdossiers**.
2. Selecteer het deurwaarderdossier dat u wilt controleren. 
3. Controleer of het veld **Deurwaardernr.** gevuld is met de juiste deurwaarder.
4. Controleer of de juiste/alle posten opgenomen zijn in het dossier.
5. Als de gegevens ingevuld zijn, ga dan verder met **[Versturen deurwaarderdossier](#versturen-deurwaarderdossier)**.


## Versturen deurwaarderdossier

Wanneer alle gegevens gevuld en gecontroleerd zijn kunt u het dossier versturen. 

1. Pas het veld **Status** aan. 
2. Vul op het deurwaarderdossier het veld **Briefsjabloon**. 
3. Navigeer via het feitenblok naar de interactielogposten. Zoek de interactielogpost voor de WIK-brief op en sla het PDF-document lokaal op. 
4. Keer terug naar het deurwaarderdossier en klik op **E-mail**. De bevestiging van het uit handen geven opent in Outlook. U kunt de eerder opgeslagen WIK-brief toevoegen als bijlage.
5. Nadat u de mail verstuurd heeft is het veld **Verstuurd** gevuld met de datum van vandaag. Dit betekent dat het dossier geactiveerd is.


## Opvoeren betaalvonnis

Wanneer u een betaalvonnis heeft kunt u dit aangeven op het dossier. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Deurwaarderdossiers**.
2. Selecteer het dossier waarvoor u een betaalvonnis op wilt voeren. 
3. Zet het veld **Betaalvonnis** op **Ja**.
4. Vul het veld **Betaalvonnis t/m** met de betaalvonnisdatum. 
5. Het betaalvonnis is verwerkt. Nieuwe klantposten met een boekingsdatum na deze datum worden niet meer automatisch toegevoegd aan het dossier. 

## Opvoeren ontruiming

Wanneer ontruiming gepland is kunt u dit aangeven op het dossier. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Deurwaarderdossiers**.
2. Selecteer het dossier waarvoor u een geplande ontruiming op wilt voeren en open het dossier. 
3. Klik op het veld **Ontruimingsdatum**. De pagina **Aanzeggingen ontruiming(en)** opent. 
4. Vul de datum voor de geplande ontruiming in en geef een reden voor ontruiming op. Geef een datum voor het verzenden van de brief in wanneer van toepassing.
5. Klik op **Sluiten** om terug te keren naar het dossier. 

## Opvoeren afgelasting ontruiming

Wanneer een geplande ontruiming afgelast is kunt u dit opvoeren op het deurwaarderdossier 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Deurwaarderdossiers**.
2. Selecteer het dossier waarvoor u de afgelasting  ontruiming op wilt voeren en open het dossier. 
3. Klik op het veld **Ontruimingsdatum**. De pagina **Aanzeggingen ontruiming(en)** opent. 
4. Vul de velden **Datum afgelasting** en **Reden afgelasting**. 
5. Klik op **Sluiten** om terug te keren naar het dossier. 

## Afsluiten deurwaarderdossier

Wanneer een klant de vordering heeft voldaan of wanneer de vordering oninbaar blijkt, kunt u het deurwaarderdossier afsluiten.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Deurwaarderdossiers**.
2. Selecteer het dossier dat u af wilt sluiten en open het. 
3. Vul in het veld **Reden afsluiting** de reden voor afsluiten. Het veld **Datum Afsluiting** wordt gevuld met de datum van vandaag. Nieuwe posten gereed voor deze klant worden niet meer automatisch toegevoegd aan het dossier. 
4. Wanneer u een nog openstaande vordering af wilt boeken kunt u dit doen via het proces AFBOEKEN VORDERING.
5. Wanneer u een dossier opnieuw wilt openen doet u dit door het veld **Reden afsluiting** leeg te maken.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NTg2NjAzMzddfQ==
-->