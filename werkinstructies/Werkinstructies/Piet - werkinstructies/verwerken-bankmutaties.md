# Verwerken bankmutaties
In dit detailproces wordt een bankafschrift geïmporteerd en verwerkt.

## Processchema

## Aanmaken bankboek


Om te beginnen met het verwerken van de bankmutaties moet als eerste een bankboek aangemaakt worden.

1.  Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst  **Bank-/Giroboek**.
2.  Klik op  **Nieuw**.
3.  Selecteer op de pagina  **Fin.dagboeksjablonenoverzicht**  de bankrekening waarvoor u bankmutaties wilt verwerken.
4.  Klik op  **OK**. De pagina **Bank-/Giroboek** opent.
5.  Vul onder kopje **Regels** voor een record de volgende velden:
    -   **Datum:**  Datum van het bankafschrift.
    -   **Documentnr.:** Nummer van bankafschrift + jaarindicatie. Voorbeeld: BM0012_20 voor bankafschrift 12 van 2020.
        -   Heeft u in een eerdere stap een incassorun geïmporteerd (zie  **[Importeren betaalrun incasso](#importeren-betaalrun-incasso)**), voeg dan een A toe aan het nummer. Voorbeeld: BM0012_20A.
    -   **Beginsaldo:**  Controleer het beginsaldo, pas dit waar nodig aan.
        -   Heeft u in een eerdere stap een incassorun geïmporteerd (zie  **[Importeren betaalrun incasso](#importeren-betaalrun-incasso)**), vul hier dan het eindsaldo van het bankafschrift in waarmee u de incassobetaalrun verwerkt heeft.
    -   **Eindsaldo:**  Vul het eindsaldo van het bankafschrift in.

## Controleren aanwezigheid betaalrun

Voordat u het gedownloade bankafschrift importeert dient u betaalruns voor incasso of betalingen te verwerken. 

 1. Klik op de actie **Betaalrun toevoegen**, waarna het scherm **Betaalrunlijst** opent.
 2. Bepaal of één of meerdere betaalruns betrekking hebben op het dagafschrift dat u wilt verwerken. 
 3. Zit er een betaalrun bij die betrekking heeft op een incasso, ga dan verder naar de instructie voor [**Importeren betaalrun incasso**](#importeren-betaalrun-incasso).
 4. Zit er geen betaalrun bij die betrekking heeft op de incasso, maar wel betrekking heeft op uitbetalingen, ga dan verder naar de instructie voor **[Importeren betaalrun uitbetalingen](#importeren-betaalrun-uitbetalingen)**.
 5. Zijn er geen betaalruns die betrekking hebben op het dagafschrift dat u wilt verwerken, sluit dan het scherm en ga verder naar de instructie voor **[Importeren bankmutaties](#importeren-bankmutaties)**.

## Importeren betaalrun incasso

Wanneer u een betaalrun wilt verwerken die betrekking heeft op een incasso, is het belangrijk dat u deze betaalrun eerst verwerkt en boekt voordat u het gedownloade bankafschrift verwerkt. 

 1. Selecteer op de **Betaalrunlijst** de betaalrun die u wilt importeren.
 2. Klik op **OK**. U komt terug op **Bank-/Giroboek** en de betaalrunregels zijn geïmporteerd in de bankboekregels. 
 3. Pas het eindsaldo van het bankafschrift aan naar het beginsaldo + het totaalbedrag van de betaalrun. 
 4. Klik op **Boeken**, waarna het bankboek met de incassorun wordt geboekt. 
 5. U dient nu een nieuw bankboek aan te maken om de resterende mutaties te verwerken. U begint weer bij de stap **[Aanmaken bankboek](#aanmaken-bankboek)**.

## Importeren betaalrunuitbetalingen

Wanneer u een betaalrun wilt verwerken die betrekking heeft op een betaling  dient u deze te importeren in het bankboek. 

 1. Selecteer op de **Betaalrunlijst** de betaalrun die u wilt importeren.
 2. Klik op **OK**. U komt terug op de pagina **Bank-/Giroboek**. De betaalrunregels zijn geïmporteerd in de bankboekregels. 
 3. Ga verder naar de instructie voor **Importeren bankmutaties**.

## Importeren bankmutaties

Wanneer u betaalruns heeft verwerkt kunt u het dagafschrift dat u gedownload heeft via uw bankapplicatie importeren. 

 1. Klik op het specifieke  bank-/giroboek op de actie **Inlezen bankmutaties**. De gelijknamige pagina wordt geopend.
 2. Kies voor **Inlezen CAMPT0.53**.
 3. Klik op de knop **Kiezen** en selecteer het gedownloade bankafschrift. Het bankafschrift wordt geïmporteerd.
 4. Klik op **Verwerken** waarna het geïmporteerde bankafschrift wordt verwerkt. De regels uit het bankafschrift zullen waar mogelijk herkend worden en er zal waar mogelijk een vereffening voorstellen.
 5. Klik op **Sluiten** om de pagina **Inlezen bankmutaties** te verlaten en terug te keren naar het **Bank-/giroboek**. U zult zien dat de regels uit het bankafschrift geïmporteerd zijn in het Bank-/Giroboek.

## Handmatig verwerken bankmutaties

Nadat u het bankafschrift van de bank geïmporteerd heeft kunt u de niet automatisch herkende posten toekennen en vereffenen. De hieronder beschreven stappen hoeven niet in volgorde uitgevoerd te worden, maar geven een overzicht van hoe u posten toe kunt kennen en vereffenen. 

 - **Uitgebreide informatie transactie**: Om te zien welke informatie meegegeven is vanaf het bankafschrift selecteert u de regel en klikt u op **Details**. U kunt ook de shortcut Ctrl+I gebruiken. Het scherm **Telebank regeldetails** opent. Dit scherm toont de gegevens die zijn meegekomen vanaf het geïmporteerde bankafschrift. 
 
 ### Kolommen

 - **Rekeningsoort:** Wanneer er geen posten herkend zijn wordt deze kolom bij bijschrijvingen standaard gevuld met de waarde **Klant**. Heeft de mutatie betrekking op een leverancier of wilt u de post direct op een grootboekrekening boeken, pas dit veld dan aan naar de waarde **Leverancier** of **Grootboekrekening**.
 - **Rekeningnummer:** Vul hier, afhankelijk van het veld **Rekeningsoort** het **Klantnummer, leveranciersnummer** of **Grootboekrekeningnummer**.

### Vereffenen

 - **Vereffenen met één openstaande klant- of leverancierspost:** 
	 - Wanneer u de transactie wilt vereffenen met één klant- of leverancierspost klikt u in de regel in veld veld **Vereffeningsnr.** de drie puntjes. De pagina **Klantposten / leverancierposten vereffenen** opent. 
	 - Selecteer de post waarmee u de transactie wilt vereffenen. 
	 - Klik op **OK**. U keert terug naar de pagina **Bank-/Giroboek**.
 - **Vereffenen met meerder openstaande klant- of leverancierspost:** 
	 - Selecteer de bankboekregel en klik op **Posten vereffenen**. De pagina **Klantposten / leverancierposten vereffenen** opent. 
	 - Selecteer de posten waarmee u de trancatie wilt vereffenen en selecteer **Vereffenings-id instellen**. Het beschikbare bedrag van de transactie wordt toegekend aan de geselecteerde posten waarbij altijd geprobeerd word de oudste post geheel te vereffen. Is daarna nog een bedrag beschikbaar dan wordt de op één nou oudste post geprobeerd te vereffenen. Wilt u het toegekende bedrag per post aanpassen dan kan dit in het veld **Te vereffenen bedrag**. 
	 - 	  Klik op **OK** om de vereffening te bevestigen en terug te keren naar de pagina **Bank-/Giroboek**.


>#### IBAN-nummer toevoegen ter herkenning
>
>In Dynamics Empire is het IBAN-nummer een belangrijke variabele voor het automatisch toekennen van een bankmutatie aan een klant. Vanuit het bankboek kunnen IBAN-nummers toegevoegd worden aan de lijst met bankrekeningen per klant om de herkenning te verbeteren. 
>
> 1. Selecteer de regel waarvan u het IBAN-nummer toe wilt voegen aan de klant. Zorg dat het veld **Rekeningnr.** het nummer van de klant bevat. Het scherm **Nieuwe bankrekening klant** opent. 
> 2. Klik op **Bankrekening klant aanmaken** in het IBAN-nummer toe te voegen aan de lijst met bankrekeningen voor de geselecteerde klant. 

## Boeken bankboek


Wanneer u alle alle bankboekregels toegekend of vereffend heeft kunt u het bankboek boeken. 

 1. Voordat u het bankboek definitief boekt kunt u kijken of er bij het boeken fouten naar voren komen waardoor bepaalde regels niet geboekt kunnen worden. Om vooraf inzicht in te krijgen in deze foutmeldingen klikt u op **Controle voor boeken**. Wanneer u de vraag krijgt of u de fouten af wilt drukken kunt u er voor kiezen om de lijst met fouten af te drukken. 
 2. Wanneer er fouten zijn ontstaan wordt in de kolom **Aantal fouten** of er fouten zijn die het boeken van de regel voorkomen. Wanneer er fouten zijn kunt u per regel op het aantal klikken. Het scherm **KGB fouten log** opent. Op dit scherm worden de fouten getoond die u dient op te lossen. 
 3. Nadat u geen fouten meer heeft of wanneer u alvast de regels zonder fouten wilt boeken, klikt u op **Boeken**. De regels worden geboekt. Zijn er regels die een fout veroorzaken, dan krijgt u de vraag of u de foutenlijst af wilt drukken. Zijn er geen fouten, dan wordt het bankboek afgesloten. 


## Zie ook
Aanleveren incassobestand  
Aanleveren betaalbestand
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcwMTg1MTcyMiwtNzM5MjU2NjI4LDE4Nz
AyODIwMTcsMTY2NTAyNjc3NSwxNjMyMjcyNDYzLDE0NTI3NTAy
OTcsLTE1Mzg5NjE4ODIsNDg5MDk0NDU2LDk3MjMzNTgxOCwtMT
gwODQ5NzA2MiwxMjQxNzIwNjAyLDk2MTI0MTQwOSwxMTU5Njg2
NDU2LC0yMDMzNjM5NzQzLC0xNDQzODMwMTAwLDU0NTk5NDE5My
wtMTg4NjE5NTIwMiwtMTgwNTc2MDI0NywyMDIxODE0NTI1LC05
OTIxNjEzMzldfQ==
-->