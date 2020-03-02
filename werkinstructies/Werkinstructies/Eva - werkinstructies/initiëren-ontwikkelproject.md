# Initiëren ontwikkelproject

In Dynamics Empire worden in de projectenadministratie de projectmodellen aangemaakt. De projectmodellen zijn typen projecten. Het is in Dynamics Empire mogelijk om enkelvoudige en gemengde projectmodellen aan te maken.

## Processchema

## Aanmaken projectmodel - enkelvoudig project

Deze werkinstructie behandelt het aanmaken van een enkelvoudig renovatieproject, bestaande uit huurwoningen DAEB, met opstellen van een investeringsbegroting en budget in Dynamics Empire. Voor de huurwoningen geldt een BTW-regime 'Niet terugvorderbaar'.

Wanneer u de Reaforce- of Ortec-koppeling gebruikt zijn deze stappen ook van toepassing, met uitzondering van het daadwerkelijk opvoeren van begroting en budgetbedragen. De begroting en budgetten worden met een druk op de knop overgehaald van het expertsysteem. Deze instructie legt uit hoe.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Projectmodeloverzicht**.
 2. Kies het projecttype waarmee u een projectmodel wilt aanmaken.
 3. Er verschijnt een lijstpagina met een eerder aangemaakt projectmodel van het betreffende projecttype.
 4. Klik op **Nieuw**. Dynamics Empire zal een nieuwe lege projectmodelkaart aanmaken. Op de kaart is slechts een versienummer (1) en een projecttype ingevuld.
 6. Vul op het tabblad **Algemeen** in ieder geval de onderstaande velden op de projectmodelkaart:
	* **Projectmodelnr.**
	* **Projectnaam**
	* **Projectomschrijving**
	* **Besluit**
	* **Start- en opleverdatum**
	* **Clusternr.**
 7. Ga via de actie **Exploitatiemodel ophalen** naar de lijst met exploitatiemodellen.
 8. Kies het exploitatiemodel waarmee u een projectmodel wilt aanmaken en klik op **OK**.
 9.  Dynamics Empire zal het tabblad **Regels** vullen met budgetregels. Met het selecteren van een exploitatiemodel is tevens voor het projectmodel bepaald wat de boekingsgang is, alsook het default BTW-percentage per werksoort. Dit is te herkennen aan de werksoortboekingsgroepen in de regels van het projectmodel. (01_N21 staat voor Huurwoningen DAEB, Niet-terug vorderbare BTW en 21% BTW.)
 10. Sluit de kaart van het projectmodelkaart. U komt daarmee terug op het **Projectmodeloverzicht** waarin het zojuist aangemaakte projectmodel zichtbaar is.

>Bij het ophalen van het exploitatiemodel wordt het sjabloon met **Cashflowprognose fase verdeelsleutels** overgenomen naar het Projectmodel. Daarmee worden alle voorkeursinstellingen met betrekking tot het verdelen van de cashflowprognose over verschillende projectfasen gekoppeld aan het gekozen projectmodel. Klik op **Cashflowprognose fase verdeelsleutel** om de initiële verdeling te bekijken en eventueel projectspecifiek te maken.

## Aanmaken projectmodel - gemengd project

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")  naar de lijst **Projectmodeloverzicht**. Kies het projecttype waarmee u een projectmodel wilt aanmaken en selecteer bijvoorbeeld **Investeringen bestaand bezit in exploitatie**.
 3. Er verschijnt een lijstpagina met eerder aangemaakte projectmodel van het betreffende projecttype. 
 4. Klik op **Nieuw** in het lint van deze lijstpagina.
 5. Dynamics Empire zal een nieuwe lege projectmodelkaart aanmaken. Op de kaart is slechts een versienummer (1) en een projecttype ingevuld.
 6. Vul op het tabblad **Algemeen** de onderstaande velden op projectmodelkaart:
	* **Projectmodelnr.** P2000
	* **Projectnaam** Renovatie Geisenlaan
	* **Projectomschrijving** Gemengd
	* **Besluit** Initiatiefase
	* **Start en opleverdatum** Naar eigen inzicht
	* **Clusternr.** P2000 
 7. Navigeer in het lint van de projectmodelkaart via **Acties - Functies - Exploitatiemodel ophalen** naar de lijst met exploitatiemodellen.
 8. Kies het exploitatiemodel waarmee u een projectmodel wilt aanmaken en selecteer bijvoorbeeld **Gemengd** en druk op **OK**.
 9.   Dynamics Empire zal het tabblad **Regels** vullen met budgetregels (STIKO). Met het selecteren van een exploitatiemodel is tevens voor het projectmodel bepaald wat de boekingsgang is en default BTW percentage per werksoort. Dit is te herkennen aan de Werksoortboekingsgroepen in de regels van het projectmodel. 00_G21 staat voor Gemengd en 21% BTW. 
 10. Sluit de kaart van het projectmodelkaart. U komt daarmee terug in de lijst met het **projectmodeloverzicht** waarin het zojuist aangemaakte projectmodel Gemengd zichtbaar is.
 11. Op het gemengde projectmodel zullen straks de individuele begrotingen voor de appartementen en winkels worden gecumuleerd. We gaan nu verder met het aanmaken van projectmodellen voor de appartementen en winkels.
 12. Klik op **Nieuw** in het lint van deze lijstpagina.
 13. Dynamics Empire zal een nieuwe lege projectmodelkaart aanmaken. Op de kaart is slechts een versienummer (1) en een projecttype ingevuld.
 14. Vul op het tabblad **Algemeen** de onderstaande velden op projectmodelkaart:
	 * **Projectmodelnr.** P2000-02
	 * **Projectnaam** Renovatie Geisenlaan
	 * **Projectomschrijving** 2 winkels
	 * **Clusternr.** P2000
 15. Navigeer in het lint van de projectmodelkaart via **Acties - Functies - Exploitatiemodel ophalen** naar de lijst met exploitatiemodellen.
 16. Kies het exploitatiemodel waarmee u een projectmodel wilt aanmaken en selecteer bijvoorbeeld **BOG NDAEB TV** en druk op **OK**.
 17. Dynamics Empire zal het tabblad **Regels** vullen met budgetregels (STIKO). Met het selecteren van een exploitatiemodel is tevens voor het projectmodel bepaald wat de boekingsgang is en default BTW percentage per werksoort. Dit is te herkennen aan de Werksoortboekingsgroepen in de regels van het projectmodel. 23_T21 staat voor Bedrijfs Onroerend Goed en terugvorderbare BTW en 21% BTW.
 18. Sluit de kaart van het projectmodelkaart. U komt daarmee terug in de lijst met het **projectmodeloverzicht** waarin het zojuist aangemaakte projectmodel Gemengd zichtbaar is.

<hr>

>#### Uitlichten van tip/extra aandachtspunt o.i.d. (H4)
>
>Bij het ophalen van het exploitatiemodel wordt het sjabloon met Cashflowprognose fase verdeelsleutels overgenomen naar het Projectmodel. De gegevens van de tabel “Cashflowprognose fase verdeelsleutel sjabloon” worden overgenomen naar de tabel “Projectmodel Cashflowprognose fase verdeelsleutel”. Daarmee worden alle voorkeursinstellingen met betrekking tot het verdelen van de cashflowprognose over verschillende projectfase gekoppeld aan het gekozen projectmodel. Klik op Cashflowprognose fase verdeelsleutel in het lint om de initiële verdeling te bekijken en eventueel project specifiek te maken.


## Opstellen begrotingsregels - enkelvoudig project

In de volgende stappen gaan we een begroting/budget opvoeren.
**Let wel:** Deze stappen zijn niet nodig wanneer u met een expertsysteem zoals Reaforce of Ortec werkt. De begroting is immers in dat systeem opgevoerd, aangeboden aan het bestuur en goedgekeurd. Ga in dat geval verder met het SYNCHRONISEREN VAN GEGEVENS MET EXPERTSYSTEEM. 
De volgende stappen zijn wel relevant als u niet met de Reaforce- of Orteckoppeling werkt.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Projectmodeloverzicht**.
 2. Het **Overzicht projecttypen** verschijnt.  Na een projecttype te hebben gekozen en op **OK** te klikken verschijnt het projectmodeloverzicht met projectmodellen op basis van het projecttype van uw keuze.  
 3. Open het projectmodel door op het projectmodelnummer te klikken.
 4. Klik op de naam van tabblad **Algemeen** om dit te sluiten (voor meer ruimte).
 5. Wijzig de begroting door op de regel(s) van (een) specifieke werksoort(en) een bedrag in te vullen of te veranderen in de kolom **Kostprijs**.
 6. De begroting wordt bepaald op basis van aantal x kostprijs. U kunt de begroting ook vaststellen door het aantal aan te passen en een **Kostprijs** per **Aantal** op te voeren. Bij deze rekenwijze hoort ook een andere **Eenheidscode**. Pas daarom, indien gewenst, deze aan.
 7. Klik op **Verwerken - Cashflowprognose fase verdeelsleutel** om de initiële verdeling te bekijken en eventueel projectspecifiek te maken.
 8. Voer in kolom **Toelichting** een toelichting op het bedrag in.
 9. Klik op de projectmodelkaart op **Contactpersonen** om projectcontactpersonen toe te kennen. Zoek collega’s op door in kolom **Contactnr.** te zoeken.
10. Selecteer de juiste persoon en geef in kolom **Functiecode** een rol op die hij/zij zal vervullen op het project.
11. Herhaal bovenstaande stappen voor iedereen die deel uitmaakt van het projectteam.
12. Klik nu op **Afdrukken** om de opgevoerde begroting te printen. Deze print kan gebruikt worden als onderlegger bij een fasebesluit. Het verkrijgen van een besluit om in dit voorbeeld de initiatiefase van het project in te gaan, gebeurt volledig buiten het systeem om. Alle stukken die bij het besluit worden gebruikt, dienen inclusief het besluit te worden gearchiveerd in DMS, geïndexeerd op het project. Zodra er een besluit is, kan het projectmodel op uw verzoek door de projectcontroller worden omgezet in een project.
14. Klik op de projectmodelkaart op **Opmerkingen** om uw collega (projectcontroller) te vragen om het model om te zetten.
16. Dynamics Empire opent een lijstscherm waarin u een opmerking richting gebruikers van Dynamics Empire kunt toekennen aan het projectmodel.
Zoek uw collega’s op via kolom **Contactnr.**
17. Voer de notitie in en klik op **Sluiten**. Dynamics Empire zal een bericht sturen naar de betreffende collega.

## Herberekenen begrotingsregels - enkelvoudig project
 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Projectmodeloverzicht**.
 2.  Het **Overzicht projecttype** verschijnt.  Na een projecttype te hebben gekozen en op **OK** te klikken verschijnt het projectmodeloverzicht met projectmodellen op basis van het projecttype van uw keuze.
 3. Door te kiezen voor **Bewerken** is het projectmodel van uw keuze te openen. Deze versie van het projectmodel is bevroren en is niet meer te wijzigen. Alle wijzigingen moeten in een versie 2 worden doorgevoerd.
 4. Navigeer naar **Nieuw - Nieuwe Versie** om een versie 2 aan te maken. Deze nieuwe versie van het projectmodel bevat  nu nog geen gegevens.
 5. Deze gegevens kopieert u vanuit het voorgaande projectmodel door te navigeren naar **Projectmodel kopiëren**. Dynamics Empire opent het venster **Kopiëren van/naar projectmodel**.
 6. Selecteer versie 1 in het veld **Bron modelnr.**
 7. Plaats een vinkje in veld **Inclusief Kop** om ook de gegevens op tabblad **Algemeen** mee te kopiëren en klik op **OK**.
 8. Dynamics Empire zal alle gegevens van versie 1 kopiëren naar versie 2. Met deze status van versie 2 kunt u nu de gewenste wijzigingen op de regels van specifieke werksoorten doorvoeren.
 9. Verberg op de projectmodelkaart eventueel tabblad **Algemeen** door eenmaal op de tekst van het tabblad te klikken en zo de regels maximaal in beeld te hebben.
 10. Wijzig de begroting door op de regel(s) van een specifieke werksoort(en) een bedrag in te vullen of te veranderen in de kolom **Kostprijs**.
 11. De begroting wordt bepaald op basis van aantal x kostprijs. *Het default aantal op alle regels is 1 en de default eenheidcode is post.* U kunt de begroting ook vaststellen door het aantal aan te passen en een **kostprijs** per **aantal** op te voeren. Bij deze rekenwijze hoort ook een andere **eenheidcode**. Pas daarom, indien gewenst, de eenheidcode aan.
 12. Klik op **Cashflowprognose fase verdeelsleutel** om de initiële verdeling te bekijken en eventueel project-specifiek te maken.
 13. Voer in kolom **Toelichting** een toelichting op het bedrag in.
15. Ga naar **Projectmodel - Opmerkingen** om uw collega (projectcontroller) te vragen om het model om te zetten.

## Definitief maken projectmodel

De begroting is d.m.v. een bestuursbesluit vastgesteld nu dient de begroting van het projectmodel vastgesteld en definitief gemaakt te worden.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Projectmodeloverzicht**.
 2.  Kies het juiste projecttype en vervolgens het juiste projectmodel. 
 3. Door voor de actie **Bewerken** te kiezen is het projectmodel van uw keuze te openen.
 4. Controleer of begroting en budget op tabblad **Regels** overeenkomen met het bestuursbesluit dat aan het projectdossier in DMS is toegevoegd.
 5. Schakel op tabblad **Algemeen** het veld **Definitieve versie** in.

## Aanmaken enkelvoudig project

De begroting is d.m.v. een bestuursbesluit vastgesteld. Ook de begroting van het projectmodel is vastgesteld en definitief gemaakt te worden nu kan op basis van het definitieve projectmodel het project aangemaakt worden.
 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Projectmodeloverzicht**.
 2.  Het **Overzicht projecttype** verschijnt.  Na een projecttype te hebben gekozen en op **OK** te klikken verschijnt het projectmodeloverzicht met projectmodellen op basis van het projecttype van uw keuze.
 3. Door te kiezen voor **Bewerken** is het projectmodel van uw keuze te openen.
 4. Omdat begroting is vastgesteld, heeft ook het projectmodel de status 'definitieve versie'. Controleert u dit door op het tabblad **Algemeen** te kijken of het veld **Definitieve versie** staat ingesteld.
 5. Door te navigeren naar **Definitieve versie** maakt Dynamics Empire een project aan op basis van de parameters uit het definitieve projectmodel.
 6. Sluit de projectmodel-kaart met **pijltje naar links** linksboven in het venster.

## Verwerken projectgegevens

De projectgegevens worden vastgelegd op het aangemaakte project.

 1. Het zojuist aangemaakt project is zichtbaar tussen alle actieve projecten in de lijst **Projectoverzicht** (![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")).
 2. Na keuze van een project en het kiezen van de actie **Bewerken** wordt de projectkaart van uw keuze geopend.
 3. Voer een fase op voor het project bij het veld **Projectfase** op het tabblad **Algemeen**.
 4. Op het tabblad **Boekingsinfo** staan de default projectbudgethouders ingesteld. Voeg de projectleider toe aan de budgethouders door op de drie puntjes naast het veld **Orderbudgethouders** te klikken. Klik op de eerste lege regel in kolom **Budgethouder**, zoek de projectleider op in de lijst en selecteer deze.
 7. Sluit de budgethouder-kaart door op de knop **Sluiten** rechtsonder in het venster te klikken.
 8. Herhaal de stappen 4 en 5 voor de **Verkoopbudgethouder** en de **Factuurbudgethouder**.
 9. Sluit de projectkaart met **pijltje naar links** en informeer de projectleider dat zijn project is aangemaakt. 

## Aanmaken offertes
De offerteaanvraag kan per brief, via het Leveranciersportaal of door een aanbesteding in verschillende media-typen worden gecommuniceerd. Nadat brieven in DMS zijn gearchiveerd kunnen ze (ook per e-mail) verstuurd worden. Hiermee wordt voorkomen dat een brief wel bij een leverancier ligt, maar niet in het projectdossier zit.
Bij het genereren van brieven worden zogenaamde tabelrelaties en samenvoegvelden gebruikt om alle relevante informatie uit Dynamics Empire naar de brief over te zetten. Ontvangen offertes worden tevens in DMS vastgelegd en aan de gebruiker toegewezen ter beoordeling.

### Vastleggen inkoopoffertes
 1. Ga voor het vastleggen van inkoopoffertes naar het **Projectoverzicht** (![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")) en open met **Bewerken** het project van uw keuze.
 2. Dynamics Empire opent de projectkaart. Deze bestaat uit vier tabbladen (midden), feitenblokken (rechts) en een menu met acties (boven).
 3. Selecteer op tabblad **Budgetregels** de budgetregel(s) waarvoor u een offerte wilt aanvragen.
 4. Klik op de actie **Inkoopofferte aanvragen**. Dynamics Empire vraagt uw bevestiging voor een inkoopofferte op de betreffende budgetregel, klik op **Ja**.
 5. U komt in een overzicht met leveranciers. Zoek en selecteer de gewenste leverancier en klik op **OK**. Dynamics Empire zal een offertekaart aanmaken die aan het project gekoppeld is.
 6. Klik op **OK** om de melding hiervan te sluiten.
 7. Voor de **budgetregel** wordt een **Inkoopoffertekaart** aangemaakt. In het feitenblok verschijnt een 1 achter item **Budgetgegevens-Werkderden**. Feitenblok **Budgetgegevens** toont het aantal inkoopregels van de geselecteerde budgetregel en feitenblok **Projectgegevens** toont alle inkoopregels van het project.
 8. Herhaal bovenstaande stappen als u bij een 2e leverancier een offerte wilt aanvragen. Het resultaat zal een 2e offertekaart zijn die gekoppeld is aan de budgetregel voor een andere leverancier, en gewijzigde aantallen in feitenblokitem **Werkderden**.
 9. Klik op het getal in het feitenblok om de offertekaarten op te vragen. U komt daarmee in een overzicht genaamd **Werkderdenoverzicht**. Dit overzicht toont alle inkoopstukken die zijn aangemaakt vanuit het project en de budgetregel. 
 >**Tip!** Mocht u een fout hebben gemaakt bij het selecteren van de leverancier, verwijder dan de offertekaart. Dit doet u als volgt:
>- Ga naar de inkoopoffertekaart door te kiezen voor **kaart**.
>- Verwijder met het *prullenbak-icoon* midden bovenaan het venster de inkoopofferte.
 10. U gaat nu de offertekaarten invullen met relevante gegevens voor de aanvraag. Selecteer hiervoor de eerste offerte in het **Werkderdenoverzicht** en open de kaart.
 11. Vul op de offertekaart de volgende gegevens in:
	 - Verzochte ontvangstdatum (vereist)
	 - Contact = naam van uw contactpersoon bij de leverancier (niet vereist)
	 - Omschrijving van offerteregels
 12. De **offertekaart** wordt geopend. Vul op de offertekaart de volgende gegevens in:
	 - Verzochte ontvangstdatum (vereist)
	 - Contact = naam van jouw contactpersoon bij de leverancier (niet vereist)
	 - Omschrijving van offerteregels
 13. Gebruik de bladerknoppen links en rechts van de offertekaart om te bladeren naar de 2e offertekaart om de gegevens in te vullen.
 
### Versturen inkoopoffertes
In dit proces moeten de aanvragen verstuurd worden naar de verschillende leveranciers.
 1. Klik vanaf Offertekaart op **Nieuw-Worddocument** om een offertebrief te genereren en te versturen.
 2. U komt in een overzicht met briefsjablonen ten behoeve van inkoop. Selecteer het gewenste briefsjabloon en klik op **OK**.
 3. Als de brief vragen stelt, wordt een vragenlijst geopend. Beantwoord de vragen in kolom **Antwoord** en klik op **OK**.
 4. Zie verder het proces VERWERKEN UITGAANDE POST.

### Ontvangen inkoopoffertes
De verschillende offertes worden ontvangen en naar de juiste afdeling doorgestuurd. In dit deelproces worden de volgende handelingen verricht:
- Verwerken ontvangen offertes
- Archiveren offertes in DMS

Inkomende poststukken worden over het algemeen gescand door de postkamer, geïndexeerd, gearchiveerd en pas daarna toegekend aan u. Dit wordt gedaan door een taak in Dynamics Empire voor u aan te maken.
 1. De binnenkomende offerte wordt in **DMS** geopend. Bestudeer de offerte en leg daarna de volgende gegevens uit de offerte op de offertekaart in Dynamics Empire vast:
	- Ontvangstdatum
	- Offertenummer leverancier
	- Prijs
 4. Ga voor het vastleggen van gegevens van de inkoopoffertes naar het **Projectoverzicht** (![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")) en open het project van uw keuze.
 5. Klik op het item **Werkderden** in het feitenblok. Het **werkderdenoverzicht** wordt geopend.
 6. Selecteer de betreffende offerte en klik op **Kaart** op de inkoopoffertekaart te openen.
 7. Leg de gegevens uit de ontvangen offerte vast.
 8. Het geoffreerde bedrag legt u vast in het veld **Directe kostprijs** op de regels van de offerte.
 9.  Gebruik de bladerknoppen links en rechts van de offertekaart om te bladeren naar de 2e offertekaart om de gegevens in te vullen.  

## Aanmaken orders
Het vastleggen van inkooporders in Dynamics Empire kan door de inkoopofferte om te zetten naar een inkooporder of door het rechtstreek aanmaken van een inkooporder.

### Rechtstreeks aanmaken inkooporders
Deze werkinstructie behandelt het rechtstreeks aanmaken van een inkooporder. Dit doet u wanneer de inkoopprijs op een andere wijze is verkregen dan via een inkoopofferte, bijvoorbeeld bij meer/minderwerk, met behulp van eenheidsprijzen of een contract. 
 1. Ga voor het vastleggen van inkoopoorders naar het **Projectoverzicht** (![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")) en open met **Bewerken** het project van uw keuze.
 2. Dynamics Empire zal op de projectkaart openen.
 3. Selecteer op tabblad **Budgetregels** de budgetregel(s) waarvoor u een order wilt aanmaken.
 4. Klik op de actie **Inkooporder aanmaken**.
 5. Dynamics Empire vraagt uw bevestiging voor een inkoopoorder op de betreffende budgetregel; klik op **Ja**.
 6. Zoek en selecteer de gewenste leverancier en klik op **OK**. Dynamics Empire zal een offertekaart aanmaken die aan het project gekoppeld is.
 7. Klik op **OK** om de melding hiervan te sluiten.
 8. Bij een planmatigonderhoudsproject wordt de status van het project omgezet in 'Order'. De aangemaakte inkooporder is te vinden vanaf het feitenblok via item Werkderden. Het aantal in dit feitenblok is toegenomen en geeft het aantal inkoopregels weer die zijn aangemaakt vanuit het project.
 9. Klik op het aantal in feitenblok **Budgetgegevens** (als het een VGO-project betreft) of feitenblok **Projectgegevens** (als het een Onderhoudsproject betreft) om de inkooporder te openen.
 10. U komt daarmee in een overzicht genaamd **Werkderdenoverzicht**. Dit overzicht toont alle inkoopstukken die zijn aangemaakt vanuit het project en de budgetregel. Een inkooporder kan uit meerdere inkoopregels bestaan. De regels worden afzonderlijk weergegeven omdat de status van beide regels op enig moment kan verschillen. Eén regel kan gegund zijn, terwijl de andere regel is gereedgemeld. Door beide regels te tonen heeft u overzicht over de status van de regels.
 > **Tip!** *Mocht u een order hebben aangemaakt voor een verkeerde leverancier, dan kunt u als volgt deze inkooporder verwijderen:*
>- Selecteer één van de orderregels in het **Werkderdenoverzicht** en kies voor **Kaart**.
>- Druk vervolgens op het prullenbak-icoon midden bovenaan de inkooporderkaart.
>- Als een deel van de inkooporder al gefactureerd is, kan de order niet worden verwijderd. Klik dan op **Inkooporder afhandelen**	(tabblad **Algemeen**, veld **Status** naar **Afgehandeld**)
 11. U gaat nu de orderkaart invullen met relevante gegevens. Selecteer één van de orderregels in het **Werkderdenoverzicht** en klik op **Kaart** om de orderkaart te openen.
 12. Vul in de inkooporderregels de **Directe kostprijs** als orderbedragen excl. BTW.
 13. Als de order aangemaakt is vanuit een offerte, dan zijn de directe kostprijzen reeds ingevuld. Pas eventueel de directe kostprijs aan als u onderhandeld heeft over de offerteprijs.
 14. Als het ingevulde bedrag **Directe kostprijs excl. BTW** hoger is dan het budgetbedrag excl. BTW zal Dynamic Empire hiervan melding doen: "Het budget ........wordt € xx,xx overschreden". Tevens kleurt de orderregel rood.
 15. Inkooporderregels kunnen opgesplitst worden ten behoeve van termijnen. Dit moet echter binnen de structuur van de aanwezige orderregels, rekening houdend met de volgorde waarin de werkzaamheden worden uitgevoerd.
 16. Kies binnen het tabblad **Regels** inkooporderregel(s) die u wilt opdelen in termijnen door te kiezen voor de actie **Regel -  Termijnen toevoegen**.
 17. Het gelijknamige scherm wordt geopend.
 18. Om met twee termijnen te werken vult u bij **Extra aantal termijnen** de waarde 1 in. De inkooporderregel zal gesplitst worden.
 19. Pas het veld **Directe kostprijs** aan als de termijnen niet evenredig zijn.
 >**Let op!** Dynamics Empire rekent het aanpassen van de directe kostprijs niet door naar andere regels. Bedenk dus, voordat u deze handeling gaat doen, wat het bedrag per termijn zal zijn. Mocht de inkooporder uit meer regels bestaan die u wilt opdelen t.b.v. termijnen, selecteer dan alle regels.
 20. Voer in kolom **Omschrijving 2** een omschrijving in van de termijnen.
 21. Voer een verwachte factuurdatum per termijn op in kolom **Verwachte factuurdatum**.
 
### Inkoopofferte omzetten in order
 1. Ga voor het omzetten van een inkoopofferte naar een  inkoopoorder naar het **Projectoverzicht** (![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")) en open met **Bewerken** het project van uw keuze.
 2. Dynamics Empire zal op de projectkaart openen.
 3. Klik in het feitenblok projectgegevens op het item **Werkderden**. U komt hiermee in het Werkderdenoverzicht.
 4. Selecteer in het Werkderdenoverzicht de inkoopofferte die u wilt omzetten en kies voor **Kaart** om de offertekaart te openen.
 5. Klik op de actie **Verwerken - Order maken**.
 6. Dynamics Empire vraagt of u de offerte wilt omzetten. Klik hier op **Ja**.
 7. Sluit de offertekaart. U komt hiermee terug in het Werkderdenoverzicht. In dit overzicht zijn nieuwe regels te zien met regelsoort = 'Order'. Tevens is te zien dat de status van de offerte is veranderd in 'Omgezet'. De offerte is gearchiveerd in Dynamics Empire en niet meer te wijzigen. De inkooporder heeft status = 'Open'.
 8. Sluit het werkderdenoverzicht. U komt hiermee terug in het projectoverzicht (of op de projectkaart). Hier is te zien dat de status van het project is veranderd in 'Order'.

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTcyOTMwMjE5LDExMjUzNTQ2ODgsLTIyNj
YyNDk3OCwtMzk3MDI4NTUsNDUxNzQ3MDM1LC0xNDQxNTI1NTc0
LC0xNjM3Nzg4MTg3LC0xNTQ0ODY4MDUxLDE2OTk1NjkxMTUsMT
g4NjgyMDY0MiwtMTA1OTE3Mzg4OCw1MTMyOTkwNTUsLTM4Mzgz
MzQwNiwtMTk3NjMzNzExMSwxODU2OTMxNjkxLC0xOTI0NjI0Nz
ksLTQwNTcyMjM2MCwtOTEzNzE0NzgwLDYyNjA4NTY2MSw5ODEz
MjM5Ml19
-->