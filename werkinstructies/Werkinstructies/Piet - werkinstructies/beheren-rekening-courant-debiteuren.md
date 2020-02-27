# Beheren rekening-courant debiteuren

De rekening-courant van de klant wordt gevormd door de klantposten. U kunt mutaties op deze **Klantposten** uitvoeren.
U benadert de klantposten voor een specifieke klant door naar de klantlijst of -kaart te navigeren en op de actie/functie **Posten** te klikken. 

## Processchema

## Afdrukken rekening-courant

Wanneer u de rekening-courant van een klant af wilt drukken kan dit vanaf pagina **Klantposten**.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Klanten**.
2. Zoek de klant op waarvoor u de rekening-courant wilt afdrukken.
3. Selecteer de juiste klantregel en klik op **Posten**. De pagina **Klantposten** opent. 
4. Kies voor **Afdrukken**. De pagina **Rekening-courant cumulatief** opent. Klik op **Verzenden naar** en kies voor 'PDF' om de rekening-courant van de klant af te drukken. 
5. Het rekening-courantoverzicht wordt geopend als PDF. 

## Vereffenen debiteurenposten 

Wanneer u klantposten met elkaar wilt vereffenen kunt u dit doen vanaf de pagina **Klantposten**.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Klanten**.
2. Zoek de klant op waarvoor u de posten wilt vereffenen.
3. Selecteer de klant en klik op **Posten**. De pagina **Klantposten** opent.
4. Selecteer één van de posten die u wilt vereffenen. 
>Wilt u een betaling vereffenen met een openstaande factuur, selecteer dan altijd de betaling. Wanneer u een factuur met een creditfactuur wilt vereffenen maakt het niet uit welke post u selecteert. Wilt u een betaling vereffenen met zowel een credit- als een debetfactuur, vereffen dan éérst de creditfactuur met de debetfactuur en daarna pas de betaling met de resterende openstaande post. Dit is van belang voor het verwerken van de gerealiseerde kasstromen.
5. Kies de actie **Posten vereffenen**. De pagina **Klantposten vereffenen** opent.
6. Selecteer de post(en) waarmee u de in stap 4 geselecteerde post wilt vereffenen.
7. Klik op actie **Vereffening-id instellen**. De kolom **Vereffenings-id** wordt gevuld met uw gebruikersnaam.
8. In het veld **Te vereffenen bedrag** kunt u eventueel het te vereffenen bedrag per post aanpassen.
9. Kies de actie **Vereffening boeken**. De pagina **Vereffening boeken** opent. 
10. Vul in het veld **Boekingsdatum** de datum van vandaag in (sneltoets: H) en klik op **OK**. De vereffening wordt geboekt en u keert terug naar de pagina **Klantposten**.
 
## Ongedaan maken debiteurenpostenvereffening 

Wanneer u de vereffening van klantposten ongedaan wilt maken kunt u dit doen vanaf de pagina **Klantposten**.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Klanten**.
2. Zoek de klant op waarvoor u de vereffening ongedaan wilt maken.
3. Selecteer de klant en kies voor functie **Posten**. De pagina **Klantposten** opent.
4. Selecteer één van de posten waarvoor u de vereffening ongedaan wilt maken en klik op **Vereffening posten ongedaan maken**. De pagina **Vereffening klantposten ongedaan maken** opent.
6. Selecteer de regel(s) waarvoor u de vereffening ongedaan wilt maken en klik op **Vereffening ongedaan maken**. Er verschijnt een pop-up met de vraag of u door wilt gaan. Klik op **Ja**; de vereffening wordt nogmaals bevestigd. U keert terug naar de pagina **Klantposten**.

## Instellen individuele afwachtcode

Wanneer u bepaalde klantposten uit wilt sluiten van aanmaningen kunt u dit doen vanaf de pagina **Klantposten**.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Klanten**.
2. Zoek de klant op waarvoor u een individuele post uit wilt sluiten van aanmaningen.
3. Selecteer de klant en klik op **Posten**. De pagina **Klantposten** opent.
4. Vul bij de post die u wilt uitsluiten van aanmaningen in het veld **Afwachten** de afwachtcode in die van toepassing is.

## Uitsluiten debiteur van aanmaningen

Wanneer u een klant in zijn geheel wilt uitsluiten van aanmaningen kunt u dit doen door een aanmaningsconditie in te stellen op de klantkaart.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Klanten**.
2. Zoek de klant op die u uit wilt sluiten van aanmaningen. Open de klantkaart. 
3. Selecteer in het veld **Aanmaningsconditiecode** de aanmaningsconditie die gebruikt wordt om klanten uit te sluiten van aanmaningen. 
4. Wanneer u het veld verlaat krijgt u de vraag of u de aanmaningsconditie op de klantposten aan wilt passen. Selecteer in dit scherm **Alle posten aanpassen** en klik op **OK**.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU3MTUyNTQ2LDE5MTg3NjM4OTIsLTEyND
g1MzcyNjcsMTMyNzA4OTE2MSwtOTU3MTE2MjgzLC0xNjM2MzM2
NTEwLDE0MzEzODE1NTksMTI2NDkwNjQ1MiwxODE3OTk5MDIwXX
0=
-->