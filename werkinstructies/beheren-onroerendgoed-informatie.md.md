
# Beheren onroerendgoed-informatie

Dit werkproces betreft het aanmaken van nieuwe onroerendgoed-eenheden en het beheren van algemene informatie over die eenheden, dat wil zeggen: informatie die nodig is voor andere doeleinden dan het verhuren van de eenheden. Dit betreft o.a.:

- adres van de eenheid, inclusief koppeling met CBS-buurt, CBS-wijk en gemeente;
- koppeling van een BAG-verblijfsobject aan de eenheid;
- toewijzen van dimensiewaarden aan de eenheden t.b.v. het boeken van eenheidsgebonden kosten en opbrengsten;
- gegevens voor het onderhouden van de eenheid, m.n. onderhoudsvormen en vraagboomsoort;
- WOZ-gegevens van de eenheid;
- cartotheekitems van de eenheid.

## Aanmaken nieuwe eenheid

In deze stap maakt u een nieuwe OG Eenheid aan, inclusief het unieke eenheidsnummer en de koppeling aan een eenheidstype en eenheidsdetailsoort.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Klik op **Nieuw** | **+ Nieuw**. Een pagina verschijnt waarop u de nieuwe eenheid kunt aanmaken met bijbehorende basisgegevens.
3. Het systeem genereert automatisch een uniek nummer en toont deze waarde in veld **Nr.**
4. Ga met de cursor in het veld **Straatnaam** staan en type in dit veld achter elkaar (zonder spaties) de postcode, het huisnummer en eventueel het toevoegsel van de nieuwe eenheid (bijvoorbeeld: '3904NJ4').
5. Verlaat het veld **Straatnaam**. Het systeem vult automatisch alle velden van het adres met de juiste waarden.
6. Het systeem koppelt aan de hand van de postcode/huisnummer-combinatie automatisch de juiste **CBS-buurt**, **CBS-wijk** en **Gemeente** aan de OG Eenheid.
7. De **Status** van de eenheid is standaard gelijk aan 'In ontwikkeling'.
8. Navigeer naar **Verhuurcontracten**. De pagina **Contractoverzicht** wordt geopend. Het systeem heeft standaard een contractregel aangemaakt met **Exploitatietoestandstype** gelijk aan 'In ontwikkeling'. Deze contractregel bevat per definitie geen **Elementen**, zodat prolongatie van deze regel niet leidt tot prolongatiefacturen, noch tot prolongatieposten (boekingen). Pas eventueel de **Ingangsdatum** of het **Exploitatietoestandstype** van deze contractregel aan. Sluit de pagina.
9. Selecteer de **Eenheidstype** waartoe de nieuwe eenheid behoort in veld **Type** op tabblad **Algemeen**.
10. Selecteer de **VERA-eenheiddetailsoort** waartoe de eenheid behoort in veld **Eenheiddetailsoort** op tabblad **VERA-eigenschappen**.

## Aanpassen adres

In deze stap past u het adres van een bestaande eenheid aan.
 
1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Selecteer de OG Eenheid waarvan u het adres wilt aanpassen.
3. Ga met de cursor in het veld **Straatnaam** staan en vervang de huidige waarde door de combinatie van (achter elkaar, zonder spaties) de postcode, het huisnummer en eventueel het toevoegsel van de bestaande eenheid in (bijvoorbeeld: '3904NJ4').
4. Verlaat het veld **Straatnaam**. Het systeem vult automatisch alle velden van het adres met de juiste waarden.
5. Het systeem koppelt aan de hand van de postcode/huisnummer-combinatie automatisch de juiste **CBS-buurt**, **CBS-wijk** en **Gemeente** aan de OG Eenheid.

## Koppelen BAG-verblijfsobject

In deze stap koppelt u een BAG-verblijfsobject aan een OG Eenheid. Dit kunt u doen voor een individuele OG Eenheid of in bulk voor alle OG Eenheden. Voor een individuele eenheid gaat u als volgt te werk.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Selecteer de OG Eenheid waaraan u een BAG-verblijfsobject wilt koppelen.
3. Klik op **Acties** en kies voor **BAG-verblijfsobject koppelen**.
4. Aan de eenheid wordt automatisch het **BAG-verblijfsobject** gekoppeld waartoe een **Nummeraanduiding** behoort met dezelfde combinatie van **Postcode**, **Huisnummer**, **Huisletter** en **Huisnummertoevoeging** als de OG Eenheid. Als er meerdere nummeraanduidingen zijn die matchen met deze combinatie, dan wordt het BAG-verblijfsobject gekoppeld waarvan de nummeraanduiding de meest recente ingangsdatum heeft.
5. Het adres van het gekoppelde BAG-verblijfsobject wordt getoond op tabblad **Adressen**. Het ID van het gekoppelde BAG-verblijfsobject wordt getoond op tabblad **Algemeen**.

Om BAG-verblijfsobjecten in bulk toe te wijzen aan alle eenheden gaat u als volgt te werk.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **BAG Import**.
2. Klik op **Eenheid bij BAG zoeken**. Het systeem gaat nu proberen BAG-verblijfsobjecten te koppelen aan *alle* OG Eenheden in *alle* bedrijven.


## Aanpassen exploitatievorm

In deze stap past u de exploitatievorm van de OG Eenheid aan. Via de exploitatievorm van de OG Eenheid bepaalt u of, en zo ja, op welke manier, de OG Eenheid kan worden verhuurd of verkocht.  U kunt een exploitatievorm toevoegen of juist verwijderen bij de OG Eenheid. Elke exploitatievorm is van een bepaald soort (*Verhuur*, *Verkoop* of *Uit beheer*) en bestaat uit een combinatie van **Aanbiedingssoort** en **Aanbiedingsvorm**.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken.
3. Navigeer naar de **Exploitatievormen**.  Een pagina wordt geopend met de exploitatievormen die momenteel zijn gekoppeld aan de OG Eenheid.
4. Om een extra exploitatievorm toe te voegen aan de OG Eenheid, klik op **Nieuw**, selecteer een **Soort**,  klik op de drie puntjes in de kolom **Aanbiedingssoort**, selecteer een regel en klik op **OK**.
5. Om een bestaande exploitatievorm te verwijderen van de OG Eenheid, selecteer een regel en klik op **Verwijderen**.


## Aanpassen bestemming 

In deze stap past u de bestemming van de OG Eenheid aan. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3. Selecteer een nieuwe waarde in veld **Bestemming** in tabblad **VERA-eigenschappen**. 
4. Selecteer een nieuwe waarde in veld **Huidig labelconditie** in tabblad **Exploitatie (Alg)**. 


## Toewijzen dimensiewaarden

In deze stap wijst u dimensiewaarden toe aan een OG Eenheid. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**. 
2. Selecteer de OG Eenheid waaraan u een dimensiewaarde toe wilt voegen. Navigeer naar **Dimensies**. 
3. Geef in de kolom **Dimensiecode** aan welk type dimensiewaarde u toe wilt voegen. 
4. Geef in de kolom **Dimensiewaardecode** de dimensiewaarde op.

## Aanpassen gegevens t.b.v. onderhoud

In deze stap wijst u een vraagboomsoort en één of meerdere onderhoudsvormen toe aan een OG Eenheid.

## Importeren nieuwe WOZ-waarden

In deze stap importeert u nieuwe WOZ-waarden van OG Eenheden, zodat deze per OG Eenheid in de vorm van een nieuwe regel worden toegevoegd in de WOZ-gegevens van die OG Eenheid. U kunt WOZ-waarden in bulk importeren met behulp van een CSV-bestand dat per OG Eenheid één regel met de volgende velden (gescheiden door komma's) bevat: 

- Type = 'WOZ-gegevens'
- OG Eenheidnummer
- WOZ-objectnummer
- WOZ-peildatum
- WOZ-taxatiewaarde
- Jaar vanaf

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **OGE Exploitatie (Fin.)-import**.
2. Een pagina wordt geopend met meerdere tabbladen, waaronder tabblad **WOZ**. Dit tabblad is initieel leeg.
3. Kies voor de actie **Importeren**.
4. Selecteer het CSV-bestand en klik op **OK**.
5. De geïmporteerde gegevens worden vermeld op tabblad **WOZ**.
6. Klik op **Acties** en kies voor **Verwerken**. De geïmporteerde gegevens worden toegevoegd aan de **WOZ-gegevens** van de desbetreffende OG Eenheden.

Ook kunt u handmatig een nieuwe regel toevoegen of een bestaande regel aanpassen in of verwijderen uit de WOZ-gegevens van een individuele OG Eenheid.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Onr. Goed-Eenhedenoverzicht**.
2. Selecteer de OG Eenheid waarvan u de WOZ-gegevens wilt wijzigen. 
3. Klik op **Navigeren** en kies voor **WOZ-gegevens**. Een pagina wordt geopend met een overzicht met WOZ-waarden van de OG Eenheid.
4. Om een bestaande regel te verwijderen selecteert u de regel en klikt u op **Verwijderen**.
5. Om een bestaande regel aan te passen selecteert u de regel en past u de waarde in de betreffende kolom aan.
6. Om een nieuwe regel toe te voegen selecteert u een lege regel en daarop een **WOZ-peildatum**, voert u de **WOZ-taxatiewaarde** in en voert u het **Jaar vanaf** in.
7. Sluit de pagina.

## Aanpassen cartotheekitems

In deze stap past u de cartotheekitems van een OG Eenheid aan.

## Zie ook

[Beheren collectief object informatie](../beheren-collectief-object-informatie/)  
[Bewaken uitvoering onderhoudsorders](../bewaken-uitvoering-onderhoudsorders/)  
[Registreren onderhoudsverzoek](../registreren-onderhoudsverzoek/)  
[Samenstellen onderhoudsorders](../samenstellen-onderhoudsorders/)  
[Uitvoeren contractueel onderhoud](../uitvoeren-contractueel-onderhoud/)  
[Uitvoeren inspectie](../uitvoeren-inspectie/)  
[Uitvoeren onderhoudsorder](../Uitvoeren-onderhoudsorder/)  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTcxMjcxMzg2MF19
-->