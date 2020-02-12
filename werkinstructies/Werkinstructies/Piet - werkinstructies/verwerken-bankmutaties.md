# Verwerken bankmutaties

In dit detailproces wordt een bankafschrift geïmporteerd en verwerkt.

## Processchema

## Aanmaken bankboek

Om te beginnen met het verwerken van de bankmutaties moet als eerste een bankboek aangemaakt worden. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Bank-/Giroboek**.
 2. Klik op **Nieuw**.
 3. Selecteer op de pagina **Fin. dagboeksjablonenoverzicht** de bankrekening waarvoor u bankmutaties wilt verwerken. 
 4.  Klik op **OK**, waarna de pagina **Bank-/Giroboek** opent.
 5. Vul de volgende velden:
	* **Datum:** Datum van het bankafschrift.
	* **Documentnr.:** Nummer van bankafschrift + jaarindicatie. Bijvoorbeeld: *BM0012_20* voor bankafschrift 12 van 2020.
		* Heeft u in een eerdere stap een incassorun geïmporteerd (zie **Importeren betaalrun incasso**), voeg dan een A toe aan het nummer. Bijvoorbeeld: *BM0012_20A*.
	* **Beginsaldo:** Controleer het beginsaldo en pas dit waar nodig aan.
		* Heeft u in een eerdere stap een incassorun geïmporteerd (zie **Importeren betaalrun incasso**), vul hier dan het eindsaldo van het bankafschrift in waarmee u de incassobetaalrun verwerkt heeft.
	* **Eindsaldo:** Vul het eindsaldo van het bankafschrift in.

## Controleren aanwezigheid betaalrun

Voordat u het gedownloade bankafschrift importeert dient u betaalruns voor incasso of betalingen te verwerken. 

 1. Klik op **Betaalrun toevoegen**, waarna het scherm **Betaalrunlijst** opent.
 2. Bepaal of één of meerdere betaalruns betrekking hebben op het dagafschrift dat u wilt verwerken. 
 3. Zit er een betaalrun bij die betrekking heeft op een incasso, ga dan verder naar de instructie voor [**Importeren betaalrun incasso**](#importeren-betaalrun-incasso).
 4. Zit er geen betaalrun bij die betrekking heeft op de incasso, maar wel betrekking heeft op uitbetalingen, ga dan verder naar de instructie voor **[Importeren betaalrun uitbetalingen](#importeren-betaalrun-uitbetalingen)**.
 5. Zijn er geen betaalruns die betrekking hebben op het dagafschrift dat u wilt verwerken, sluit dan het scherm en ga verder naar de instructie voor **[Importeren bankmutaties](#importeren-bankmutaties)**.

## Importeren betaalrun incasso

Wanneer u een betaalrun wilt verwerken die betrekking heeft op een incasso, is het belangrijk dat u deze betaalrun eerst verwerkt en boekt voordat u het gedownloade bankafschrift verwerkt. 

 1. Selecteer op de **Betaalrunlijst** de betaalrun die u wilt importeren.
 2. Klik op **OK**. U komt terug op ank-/iroboek** en de betaalrunregels zijn geïmporteerd in de bankboekregels. 
 3. Pas het eindsaldo van het bankafschrift aan naar het beginsaldo + het totaalbedrag van de betaalrun. 
 4. Klik op **Boeken**, waarna het bankboek met de incassorun wordt geboekt. 
 5. U dient nu een nieuw bankboek aan te maken om de resterende mutaties te verwerken. U begint weer bij de stap **[Aanmaken bankboek](#aanmaken-bankboek)**.

## Importeren betaalrunuitbetalingen

Wanneer u een betaalrun wilt verwerken die betrekking heeft op een betaling, dient u deze te importeren in het bankboek. 

 1. Selecteer op de **Betaalrunlijst** de betaalrun die u wilt importeren.
 2. Klik op **OK**. U komt terug op ank-/iroboek**. De betaalrunregels zijn geïmporteerd in de bankboekregels. 
 3. Ga verder naar de instructie voor **Importeren bankmutaties**.

## Importeren bankmutaties

Wanneer u betaalruns heeft verwerkt kunt u het dagafschrift dat u gedownload heeft via uw bankapplicatie importeren. 

 1. Klik op het specifiekde pagina **Bhet geopende bank-/Ggiroboek op **Inlezen bankmutaties**. De gelijknamige pagina wordt geopend. 
 2. Klik op **Inlezen CAMPT0.53**. 
 3. Klik op **Kiezen** en selecteer het gedownloade bankafschrift. Het bankafschrift wordt geïmporteerd.
 4. Klik op **Verwerken** waarna het geïmporteerde bankafschrift wordt verwerkt. De regels uit het bankafschrift zullen waar mogelijk herkend worden en er zal waar mogelijk een vereffening voorstellen. 
 5. Klik op **Sluiten** om de pagina **Inlezen bankmutaties** te verlaten en terug te keren naar e ank-/iroboek**. U zult zien dat de regels uit het bankafschrift geïmporteerd zijn in het Bank-/ Giroboek.

## Handmatig verwerken bankmutaties

Nadat u het bankafschrift van de bank geïmporteerd heeft kunt u de niet automatisch herkende posten toekennen en vereffenen. De hieronder beschreven stappen hoeven niet in de aangegeven volgorde uitgevoerd te worden, maar geven een overzicht van hoe u posten toe kunt kennen en vereffenen. 

 - **Uitgebreide informatie transactie**: Om te zien welke informatie meegegeven is vanaf het bankafschrift selecteert u de regel en klikt u op **Details**. U kunt ook de shortcut '**Ctrl + I**' gebruiken. Het scherm **Telebank regeldetails** opent; hierop worden de tgegevens getoond die mee zijn gekomen vanaf het geïmporteerde bankafschrift.   
 
### Kolommen

 - **Rekeningsoort:** Wanneer er geen posten herkend zijn wordt deze kolom bij bijschrijvingen standaard gevuld met de waarde **Klant**. Heeft de mutatie betrekking op een leverancier of wilt u de post direct op een grootboekrekening boeken, pas dit veld dan aan naar de waarde **Leverancier** of **Grootboekrekening**.
 - **Rekeningnummer:** Vul hier afhankelijk van het veld **Rekeningsoort** het **Klantnummer, Leveranciersnummer** of **Grootboekrekeningnummer** in.

### Vereffenen

 - **Vereffenen met één openstaande klant- of leverancierspost:** 
	 1. Wanneer u de transactie wilt vereffenen met één klant- of leverancierspost klikt u in de regel in veld **Vereffeningsnr.** op de drie puntjes. De pagina **Klantposten / leverancierposten vereffenen** opent. 
	 2. Selecteer de post waarmee u de transactie wilt vereffenen. 
	 3. Klik op **OK**. U keert terug naar de pagina **Bank-/Giroboek**.
 - **Vereffenen met meerdere openstaande klant- of leveranciersposten:** 
	 1. Selecteer de bankboekregel en klik op **Posten vereffenen**. De pagina **Klantposten / leverancierposten vereffenen** opent. 
	 2. Selecteer de posten waarmee u de transactie wilt vereffenen en selecteer **Vereffenings-id instellen**. Het beschikbare bedrag van de transactie wordt toegekend aan de geselecteerde posten waarbij altijd geprobeerd wordt om de oudste post geheel te vereffenen. Is daarna nog een bedrag beschikbaar, dan wordt geprobeerd om de op één na oudste post te vereffenen. Wilt u het toegekende bedrag per post aanpassen, dan kan dit in het veld **Te vereffenen bedrag**. 
	 3. Klik op **OK** om de verffening te bevestigen en terug te keren naar de pagina **Bank-/Giroboek**.

>### IBAN-nummer toevoegen ter herkenning
>
>In Dynamics Empire is het IBAN-nummer een belangrijke variable voor het automatisch toekennen van een bankmutatie aan een klant. Vanuit het bankboek kunnen IBAN-nummers toegevoegd worden aan de lijst met bankrekeningen per klant om de herkenning te verbeteren. 
>
> 1. Selecteer de regel waarvan u het IBAN-nummer toe wilt voegen aan de klant. Zorg dat het veld **Rekeningnr.** het nummer van de klant bevat. Het scherm **Nieuwe bankrekening klant** opent. 
> 2. Klik op **Bankrekening klant aanmaken** om het IBAN-nummer toe te voegen aan de lijst met bankrekeningen voor de geselecteerde klant. 

## Boeken bankboek

Wanneer u alle bankboekregels toegekend of vereffend heeft, kunt u het bankboek boeken. 

 1. Voordat u het bankboek definitief boekt kunt u kijken of er bij het boeken fouten naar voren komen waardoor bepaalde regels niet geboekt kunnen worden. Om vooraf inzicht in te krijgen in deze foutmeldingen klikt u op **Controle voor boeken**. U kunt ervoor kiezen om de lijst met fouten af te drukken. 
 2. Wanneer er fouten zijn ontstaan wordt in de kolom **Aantal fouten** het aantal vermeld van de fouten die het boeken van de regel voorkomen. Wanneer er fouten zijn kunt u per regel op het aantal klikken. Het scherm **KGB fouten log** opent. Op dit scherm worden de fouten getoond die u dient op te lossen. 
 3. Als er geen fouten meer zijn, of als u alvast de regels zonder fouten wilt boeken, klikt u op **Boeken**. De regels worden geboekt. Zijn er regels die een fout veroorzaken, dan krijgt u de vraag of u de foutenlijst af wilt drukken. Zijn er geen fouten, dan wordt het bankboek afgesloten. 

## Zie ook
Aanleveren incassobestand  
Aanleveren betaalbestand
# Registreren huuropzegging   ## Omschrijving (Geef hier de omschrijving het detailproces)   ## Processchema (Hier komt link naar Mavim of plaatje van proces.)   ## Processtappen   ### Vastleggen huuropzegging In deze stap legt u de huuropzegging vast, inclusief nieuw correspondentieadres van de vertrekkende huurder en een leegstandscontract voor de OG Eenheid.   1. Klik in het rolcentrum op de knop **OG Eenheden** of navigeer via het zoekveld naar de lijst **Onr. Goed-Eenhedenoverzicht**. 2. Selecteer de OG Eenheid waarvoor de huuropzegging moet worden vastgelegd. 3. Klik op de link achter **Klantnr** in het feitenblok **Klantinformatie**. De **Klantkaart** wordt geopend van de klant die een actief huurcontract op de geselecteerde OG Eenheid heeft. 4. Controleer of degene van wie de huuropzegging afkomstig is, overeenkomt met deze klant of bevoegt is namens die klant het huurcontract te be�indigen. 5. Sluit de Klantkaart. U keert weer terug naar het overzicht met OG Eenheden. 6. Klik op de knop ***Nieuw*** - **Huuropzegging maken**. Er verschijnt een popup met de vraag of u contract op naam van de klant wilt be�indigen. 7. Klik op **Ja**. Pagina **Opzegging huurcontract** wordt geopend. 8. Controleer de standaardwaarde van de volgende velden en pas de waarde daar waar nodig aan:
 * **Huurcontracteinddatum:** De datum waarop het huurcontract van de klant eindigt. Dit is standaard gelijk aan de **Einddatum volgens opzegtermijn** * **Leegstandsboekingsgroep:** is standaard gelijk aan de leegstandsboekingsgroep die als standaard is ingesteld in de **Empire-instellingen**. 9. Klik op **OK**. 10. Als u de **Huurcontracteinddatum** heeft aangepast in een eerdere datum, dan verschijnt een popup met de mededeling dat de opzegtermijn niet in acht is genomen en de vraag of u wil doorgaan. Klik op **Ja**. 11. Achter de schermen wordt voor de geselecteerde OG Eenheid automatisch een **Leegstandscontract** aangemaakt, waarbij Ingangsdatum = Huurcontracteinddatum + 1 dag en met de geselecteerde Leegstandsboekingsgroep. 12. Achter de schermen wordt voor de geselecteerde OG Eenheid automatisch een **Verhuurmutatie** aangemaakt en gekoppeld aan de nieuwe **Huuropzegging**. 13. In het geval bij de OG Eenheid is ingesteld dat er 1 of meer voor- en/of eindinspecties worden uitgevoerd, dan wordt na actie 9 of 10 achter de schermen automatisch een nieuwe **Onderhoudsverzoek** aangemaakt en gekoppeld aan de nieuwe **Huuropzegging**. 14. Pagina **Huurcontractopzeggingkaart** wordt geopend. 15. Vul het veld **Huuropzeggingsreden** in. 16. Controleer de telefoonnummer(s) en het e-mailadres van de vertrekkende huurder en pas deze indien nodig aan in tab **Huurcontract / Huurder** . 17. Registreer het nieuwe correspondentieadres van de vertrekkende huurder in tab **Nieuw correspondentieadres**. * Voor een Nederlands correspondentieadres doet u dit door in het veld **Straat** de postcode en het huisnummer en eventueel het huisnummer toevoegsel in te vullen (achter elkaar, zonder spaties). Nadat u het veld verlaat, vult het systeem automatisch de velden **Straat**, **Huisnummer**, **Huisnummer toevoegsel**, **Postcode** en **Plaats** in met de waarden die het systeem heeft gevonden in de postcodetabel. * Voor een buitenlands correspondentieadres selecteert u eerst de juiste **Landcode**. Vervolgens vult u de overige velden van het correspondentieadres. 18. Selecteer in veld **Contactgegevens wijzigingsdatum** de datum per wanneer het nieuwe correspondentieadres ingaat.   <hr>
  ### Plannen inspectie(s) In deze stap plant u voor- en/of eindinspecties. Deze stap is alleen van toepassing als bij de OG Eenheid is ingesteld dat er 1 of meer voor- en/of eindinspecties worden uitgevoerd (zie pagina **Onrerend Goed Eenheidkaart**, tab **Inspectie**, veld **Aantal vooropnames** en veld **Aantal eindopnames**).   1. Open pagina **Inspectieafspraken** van de betreffende huuropzegging * Rechtstreeks vanaf de pagina **Verhuurmutatieoverzicht** (selecteer de Verhuurmutatie die is aangemaakt tijdens de vorige stap en klik op ***Navigeren*** - **Inspectieafspraken**). * Via overzichtspagina **Huuropzeggingen** (selecteer de Huuropzegging die is aangemaakt tijdens de vorige stap, open pagina Huurcontractopzeggingkaart en klik op ***Navigeren*** - ***Opzegging*** - **Inspectieafspraken**). * Via de OG Eenheid (open overzicht met OG Eenheden, selecteer de OG Eenheid en klik op ***Navigeren*** - **Huuropzeggingen**, klik op ***Navigeren*** - ***Opzegging*** - **Inspectieafspraken**) 2. Selecteer de eerste inspectie met **Status** = Nieuw die u wilt plannen. 3. Klik op **Inspectieafspraak plannen**. Pagina **Inspecteur Beschikbaarheid** wordt geopend. Op deze pagina worden de ingestelde **Duur** van de geselecteerde inspectie gepland vermeld alsmede de datum waarop de eerste vooropname uiterlijk gepland moet worden. Op deze pagina worden ook alle inspecteurs vermeld. 4. In veld **Datum** selecteer de datum waarop u de inspectie wilt plannen. Per inspecteur en per begintijd is aangegeven of de inspecteur op die tijd beschikbaar is of niet. Een vinkje betekent dat die inspecteur niet beschikbaar is op dat tijdstip. 5. Selecteer de inspecteur voor wie u de inspectie wilt plannen. 6. Vink de begintijd aan waarop u de inspectie wilt plannen. 7. Klik op **OK**. 8. Herhaal actie 2 t/m 7 voor elke volgende inspectie die u wilt plannen. 9. Klik op **OK**.   <hr>   ### Bevestigingen huuropzegging     1. Open pagina **Huurcontractopzeggingkaart** van de betreffende huuropzegging. * Vanaf de pagina **Verhuurmutatieoverzicht** (selecteer de Verhuurmutatie die is aangemaakt tijdens de vorige stap en klik op ***Navigeren*** - **Huuropzegging**). * Via overzichtspagina **Huuropzeggingen** (selecteer de Huuropzegging die is aangemaakt tijdens de vorige stap en open pagina Huurcontractopzeggingkaart. * Via de OG Eenheid (open overzicht met OG Eenheden, selecteer de OG Eenheid en klik op ***Navigeren*** - **Huuropzeggingen**) 2. Klik op ***Acties*** - **Worddocument**. 3. Selecteer het juiste Word-sjabloon voor de bevestiging van de huuropzegging en klik op **OK**. 4.   <hr>   ## Zie ook (links naar andere detailprocessen uit dezelfde procesgroep) Werkinstructie X Werkinstructie Y Werkinstructie Z
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMzA0MTM4ODksLTE4MDU3NjAyNDcsMj
AyMTgxNDUyNSwtOTkyMTYxMzM5XX0=
-->