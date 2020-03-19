# Registreren huuropzegging
In dit werkproces word
Per een gegeven datum, liefst hmet huurcontract van een huurder op een eenheid beëindigd per een gegeven datum. Als de eenheid moet worden geïnspecteerd, worden bovendien afspraken geregistreerd voor de voor- en/of eindinspectie. Tot enslotte wordt een bevestiging van de huuropzegging gestuurd. inachtneming van een opzegtermijn, kan de huur van een eenheid worden opgezegd. Vervolgens wordt de woning geïnspecteerd en zo spoedig mogelijk weer klaargemaakt voor verhuring aan een volgende huurder.

## Processchema

## Vastleggen huuropzegging

In deze stap legt u de huuropzegging vast, inclusief nieuw correspondentieadres van de vertrekkende huurder en een leegstandscontract voor de OG Eenheid.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Zoek de OG Eenheid op waarvoor de huuropzegging moet worden vastgelegd en selecteer deze.
3. Klik op de link achter **Klantnr.** in het feitenblok **Klantinformatie**. De **Klantkaart** wordt geopend van de klant die een actief huurcontract op de geselecteerde OG Eenheid heeft.
4. Controleer of degene van wie de huuropzegging afkomstig is, overeenkomt met deze klant of bevoegd is namens die klant het huurcontract te beëindigen.
5. Sluit de Klantkaart. U keert weer terug naar het overzicht met OG Eenheden.
6. Klik op **Nieuw** en kies voor **Huuropzegging maken**. Er verschijnt een popup met de vraag of u het contract op naam van de klant wilt beëindigen.
7. Klik op **Ja**. De pagina **Opzegging huurcontract** wordt geopend.
8. Controleer de standaardwaarde van de volgende velden en pas de waarde daar waar nodig aan en klik daarna op **OK**:
   - **Huurcontracteinddatum:** De datum waarop het huurcontract van de klant eindigt. Dit is standaard gelijk aan de **Einddatum volgens opzegtermijn**.
   - **Leegstandsboekingsgroep:** Deze is standaard gelijk aan de leegstandsboekingsgroep die als standaard is ingesteld in de **Empire-instellingen**.
9. Als u de **Huurcontracteinddatum** heeft aangepast in een eerdere datum, dan verschijnt een popup met de mededeling dat de opzegtermijn niet in acht is genomen en de vraag of u wilt doorgaan. Klik op **Ja**.
101. Achter de schermen wordt voor de geselecteerde OG Eenheid automatisch een **Leegstandscontract** aangemaakt, waarbij Ingangsdatum = Huurcontracteinddatum + 1 dag, en met de geselecteerde leegstandsboekingsgroep.
Ook wordt voor de geselecteerde OG Eenheid automatisch een **Verhuurmutatie** aangemaakt en gekoppeld aan de nieuwe **Huuropzegging**.
113. Als bij de OG Eenheid is ingesteld dat er één of meer voor- en/of eindinspecties worden uitgevoerd, dan wordt achter de schermen automatisch een nieuw **Onderhoudsverzoek** aangemaakt en gekoppeld aan de nieuwe **Huuropzegging**.
124. Pagina **Huurcontractopzeggingkaart** wordt geopend.
135. Vul het veld **Huuropzeggingsreden** in.
146. Controleer de telefoonnummer(s) en het e-mailadres van de vertrekkende huurder en pas deze indien nodig aan op tab **Huurcontract/Huurder** .
157. Registreer het nieuwe correspondentieadres van de vertrekkende huurder op tab **Nieuw correspondentieadres**.
    Voor een Nederlands correspondentieadres doet u dit door in het veld **Straat** de postcode en het huisnummer en eventueel het huisnummer toevoegsel in te vullen (achter elkaar, zonder spaties). Nadat u het veld verlaat, vult het systeem automatisch de velden **Straat**, **Huisnummer**, **Huisnummer toevoegsel**, **Postcode** en **Plaats** in met de waarden die het systeem heeft gevonden in de postcodetabel.
    Voor een buitenlands correspondentieadres selecteert u eerst de juiste **Landcode**. Vervolgens vult u de overige velden van het correspondentieadres.
16. Selecteer in veld **Contactgegevens wijzigingsdatum** de datum per wanneer het nieuwe correspondentieadres ingaat.

## Plannen inspectie(s)

In deze stap plant u voor- en/of eindinspecties. Deze stap is alleen van toepassing als bij de OG Eenheid is ingesteld dat er één of meer voor- en/of eindinspecties worden uitgevoerd (zie **Onroerend Goed Eenheidkaart**, tab **Inspectie**, veld **Aantal vooropnames** en veld **Aantal eindopnames**).

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Verhuurmutatieoverzicht**.
2. Zoek de verhuurmutatie op waarvoor inspecties moeten worden gepland.
3. Open de detailpagina van de verhuurmutatie door op het nummer te klikken.
4. Navigeer naar deOpen pagina **Inspectieafspraken** van de betreffende huuropzegging. Dit kan rechtstreeks vanaf de pagina **Verhuurmutatieoverzicht** (selecteer de Verhuurmutatie die is aangemaakt tijdens de vorige stap en kies voor **Inspectieafspraken**). Het kan ook via overzichtspagina **Huuropzeggingen** (selecteer de Huuropzegging die is aangemaakt tijdens de vorige stap, open pagina Huurcontractopzeggingkaart en kies voor **Inspectieafspraken**). Een derde mogelijkheid is via de OG Eenheid (open overzicht met OG Eenheden via ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen"), selecteer de OG Eenheid en kies voor **Huuropzeggingen** en vervolgen. 
4. Klik op **Navigeren** en kies voor **Inspectieafspraken**).
52. Selecteer de eerste inspectie met **Status** 'Nieuw' die u wilt plannen.
63. Klik op **Inspectieafspraak plannen**, waarna de p. Pagina **Inspecteur Beschikbaarheid** wordt geopend. Op deze pagina worden de ingestelde **Duur** van de geselecteerde inspectie vermeld alsmede de datum waarop de eerste vooropname uiterlijk gepland moet worden. Op deze pagina worden ook alle inspecteurs vermeld.
74. In veld **Datum** selecteert u de datum waarop u de inspectie wilt plannen. Per inspecteur en per begintijd is aangegeven of de inspecteur op die tijd beschikbaar is of niet. Een vinkje betekent dat die inspecteur niet beschikbaar is op dat tijdstip.
85. Selecteer de inspecteur voor wie u de inspectie wilt plannen, vink de begintijd aan waarop u de inspectie wilt plannen en klik op **OK**.
98. Herhaal bovenstaande acties voor elke volgende inspectie die u wilt plannen.
109. Klik op **Sluiten**.


## Bevestigingen huuropzegging

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijstOpen pagina **Huurcontractopzeggingkaart** van de betreffende huuropzegging. Dit kan vanaf de pagina **Verhuurmutatieoverzicht**.
2. Zoek (selecteer de vVerhuurmutatie op waarvoor de bevestiging van de huuropzegging moet worden verstuurd.
3. Opendie is aangemaakt tijdens de vorige stap en kies voor **Huuropzegging**). Het kan ook via overzichtspagina **Huuropzeggingen** (selecteer de Huuropzegging die detailpagina van de verhuurmutatie. 
4. Navigeer naar deis aangemaakt tijdens de vorige stap en open pagina Huurcontractopzeggingkaart) of via de OG Eenheid (open overzicht met OG Eenheden, selecteer de OG Eenheid en klik op de detailpagina van de verhuurmutatie. 
4. Klik op **Navigeren** en kies voor **Huuropzeggingen**).
52. Kies voor functie **Worddocument** en s.
36. Selecteer het juiste Word-sjabloon voor de bevestiging van de huuropzegging. K en klik op **OK**. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc3Njc2MzcyMSwtMTg1MTEzMDY4OSwxND
U4MDc1MDE4LDE3MjY3OTQ2MDIsMTc2Njc5MjI2M119
-->