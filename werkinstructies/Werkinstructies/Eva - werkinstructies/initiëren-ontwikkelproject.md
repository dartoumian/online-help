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
 6. Vul op het tabblad **Algemeen** de onderstaande velden op projectmodelkaart:
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

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM4MDk1MDQ0NCwtMTMwNjUzNDkxOCwtMj
A3NTYwNDExNyw2MjI3MjE2NjUsLTEyODQwMzYyOThdfQ==
-->