# Initiëren ontwikkelproject

In Dynamics Empire worden in de projectenadministratie de projectmodellen aangemaakt. De projectmodellen zijn typen projecten. Het is in Dynamics Empire mogelijk om enkelvoudige en gemengde projectmodellen aan te maken.

## Processchema

## Aanmaken projectmodel - enkelvoudig

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

## Opstellen begrotingsregels - Enkelvoudig project

In de volgende stappen gaan we een begroting/budgetten opvoeren.
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

## Herberekenen begrotingsregels
(...)

## Definitief maken projectmodel

De begroting is d.m.v. een bestuursbesluit vastgesteld nu dient de begroting van het projectmodel vastgesteld en definitief gemaakt te worden.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Projectmodeloverzicht**.
 2.  Kies het juiste projecttype en vervolgens het juiste projectmodel. 
 3. Door voor de actie **Bewerken** te kiezen is het projectmodel van uw keuze te openen.
 4. Controleer of begroting en budget op tabblad **Regels** overeenkomen met het bestuursbesluit dat aan het projectdossier in DMS is toegevoegd.
 5. Schakel op tabblad **Algemeen** het veld **Definitieve versie** in.

## Aanmaken project
(...)

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
 12. Vul op de offertekaart de volgende gegevens in:
	 - Verzochte ontvangstdatum (vereist)
	 - Contact = naam van uw contactpersoon bij de leverancier (niet vereist)
	 - Omschrijving van offerteregels
 13. De **offertekaart** wordt geopend. Vul op de offertekaart de volgende gegevens in:
	 - Verzochte ontvangstdatum (vereist)
	 - Contact = naam van jouw contactpersoon bij de leverancier (niet vereist)
	 - Omschrijving van offerteregels
 14. Gebruik de bladerknoppen links en rechts van de offertekaart om te bladeren naar de 2e offertekaart om de gegevens in te vullen.

## Orders aanmaken
(...)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg4NjgyMDY0MiwtMTA1OTE3Mzg4OCw1MT
MyOTkwNTUsLTM4MzgzMzQwNiwtMTk3NjMzNzExMSwxODU2OTMx
NjkxLC0xOTI0NjI0NzksLTQwNTcyMjM2MCwtOTEzNzE0NzgwLD
YyNjA4NTY2MSw5ODEzMjM5MiwtMzgwOTUwNDQ0LC0xMzA2NTM0
OTE4LC0yMDc1NjA0MTE3LDYyMjcyMTY2NSwtMTI4NDAzNjI5OF
19
-->