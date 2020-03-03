# Beheren onderhoudscontracten


## Processchema

## Importeren begroting
Alle uitvoeringsactiviteiten van de jaarbegroting worden ingelezen in Dynamics Empire en samengevoegd tot  gecombineerde uitvoeringsprojecten.

 1. Ga voor het importeren van begrotingsregels via de zoekfunctie ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het **Kladblokimportoverzicht**, en kies op die pagina voor de actie **Nieuw**. Dynamics Empire maakt een zogenaamde **Kladblokbudget-importkaart** aan met een eerstvolgend volgnummer.
 2. Kies voor **Budget importeren** om een bestand met begrotingsregels te importeren.
 3. Dynamics Empire opent een venster genaamd **Import budget planmatig onderhoud**. Vul in ieder geval de volgende velden in:
	 * **Importsjablooncode**
	 * **Bestandsnaam**
	 * **Projecttype**
	 * **Begrotingsjaar**
 4. Klik op de knop **Budget importeren**. Wanneer de import slaagt, krijgt u melding *De import is succesvol verlopen*.
 5. Klik op **OK** om de melding te sluiten.
 6. Het importresultaat is te zien op de eerste twee tabbladen (**Algemeen** en **Kladblokimportregels**) van de Kladblokbudget-importkaart. Sluit de kaart met het pijltje linksboven. Op de pagina **Kladblokimportoverzicht** is nu een nieuw record te zien waarin handmatige begrotingsregels zijn geïmporteerd.
 7. Wanneer u een foutief bestand hebt geïmporteerd, selecteert u de betreffende regel en klikt u op **Verwijderen**. De Kladblokbudget-importkaart wordt dan in zijn geheel verwijderd en u kunt opnieuw beginnen met de knop **Nieuw**.
 8. Wanneer u de begrotingsregels verder wilt verwerken, selecteer dan het nieuwe record en klik op **Bewerken**. U opent daarmee de Kladblokbudget-importkaart in een 'bewerken'-modus. 

### Verwerken van de begrotingsregels
 1. Uitgangspunt is dat de begrotingsregels compleet zijn geïmporteerd. Dat wil zeggen, in de begrotingsregels is de samenstelling van de projecten al bepaald d.m.v. een **Sjablooncode**. Daarnaast is per begrotingsregels bepaald wie de **Contactpersoon** is en welke rol deze persoon binnen de projecten zal uitvoeren (projectleider, toezichthouder, woonconsulent, contractbeheerder). Tevens is de initiële planning bepaald in de velden **Startdatum** en **Opleverdatum**.
 2. Klik om de regels te verwerken op de **Kladblokbudgetimport-kaart** op **Samenvoegen alle regels op basis van Sjablooncode**.
 3. Dynamics Empire zal alle begrotingsregels op tabblad **Kladblok importregels** samenvoegen of kopiëren naar tabblad **Voorlopige projectregels** waarbij een tweetal bewerkingen wordt uitgevoerd (hieronder beschreven).
 
### Samenvoegen van de begrotingsregels
Het samenvoegen van begrotingsregels is nodig om de vele regels terug te brengen naar een ingedikte vorm ten behoeve van de budgetbewaking. De stelregels is dat de begroting zo gedetailleerd mogelijk moet worden overgezet naar Dynamics Empire, zodat je in kaar kunt terugkijken hoe een project begroot is. Dit is nodig om budgetoverschrijdingen te kunnen verklaren. Echter, op dit detailniveau is het niet wenselijk om budgetten te bewaken.

Aan het samenvoegen zijn voorwaarden verbonden. De begrotingsregels dienen te zijn opgebouwd uit dezelfde waarden voor Cluster, Bouwblok, Werksoort, Werksoortboekingsgroep, Sjablooncode en Vrije code budget.

 1. Deze regels zullen na actie **Samenvoegen alle regels op basis van sjablooncode** worden samengevoegd tot één regel.
 2. De samengevoegde regel is terug te vinden op tabblad **Voorlopige projectregels**.
 3. Alle begrotingsregels die niet kunnen worden samengevoegd, zijn binnen de kladblokimportregels te herkennen aan hun opmaak van de kolom clusternummer.
 4. Door deze regels te selecteren en te kiezen voor **Kopiëren** worden deze regels als losse voorlopige projectregels bij de samengevoegde regels geplaatst.
 5. Alle regels met hetzelfde voorlopige projectnummer zullen bij het aanmaken van onderhoudsprojecten gekoppeld worden onder één project. De sjablooncode is deze kolom is aan te passen, voor het geval in Excel een foutje is gemaakt.

### Het oplossen van samenvoegconflicten

 1. Wanneer regels voldoen aan de criteria om te worden samengevoegd, maar de Projectomschrijving, Contactpersonen, Plaats of vrije tekstvelden van die regels verschillen, treed er een samenvoegconflict op. Dit is te zien aan een JA in kolom **Samenvoegconflict** op tabblad **Voorlopige projectregels**.
 2. Klik op **Ja** in deze kolom om de oorspronkelijke regels te tonen.
 3. Doorloop alle samenvoegconflicten en los ze één voor één op.

>**Tip!** Plaats een filter op alle regels met een samenvoegconflict voordat u bezig gaat met het oplossen. Dit doet u door met de rechter muisknop op een willekeurige **Ja** in kolom **Samenvoegconflict** te klikken en **Filteren op deze waarde** te selecteren. (Met **Filter wissen** heft u het filter weer op.)

### Functie instellen voor contactpersonen

 1. Op tabblad **Functies** kunt u instellen welke functiegroepcode (**Functie contact**) toegekend moet worden aan de contactpersonen bij het aanmaken van projecten.

## Aanmaken project

 1. Controleer voor het aanmaken van onderhoudsprojecten of alle regels zijn verwerkt op de **Kladblokbudgetimport**. Alle regels op tabblad **Kladblokimportregels** zijn verwerkt als het clusternummer groen kleurt. Met de functionaliteit **Gekopieerde regels verbergen** (via item **Beheren** bovenin het tabblad) kunt u snel controleren of alle regels zijn verwerkt. Met **Gekopieerde regels tonen** brengt u ze weer in beeld.
 
>**Tip!** Als regels niet zijn verwerkt, dient u deze handmatig te kopiëren of samen te voegen. Selecteer  hiervoor de niet-verwerkte regels en klik op de knop **Kopiëren** of **Samenvoegen**. Hebt u hierbij een fout gemaakt, verwijder dan de gekopieerde/samengevoegde regel uit
tabblad **Voorlopige projectregels**.

 2. Plaats vervolgens een vinkje in veld **Definitieve versie** op tabblad **Algemeen**.
 3. Controleer of het totaalbedrag in het veld **Regeltotaal excl. BTW** op tabblad **Algemeen** overeenkomt met het bedrag dat door de bestuurder is goedgekeurd voor Planmatig, Contract- of Serviceonderhoud. Voer indien gewenst een detailcontrole uit.
 4. Navigeer naar de functie **Aanmaken onderhoudsprojecten**.
 5. Na het voltooien van deze actie verschijnt een venster waarin Dynamics Empire aangeeft dat er een X aantal projecten is aangemaakt. Klik vervolgens op **OK** om dit venster te sluiten.
 6. Er kunnen vanaf dit moment geen wijzigingen meer worden aangebracht op de Kladblokbudgetimportkaart. Alle correcties van fouten in de voorbereiding dienen in de projectadministratie te worden gecorrigeerd.
  
### Verbeteren projectnaam en -omschrijving
 1. Het verbeteren van projectnaam en -omschrijving is een actie die de projectleider moet uitvoeren, direct na het aanmaken van onderhoudsprojecten.
 2. Alle aangemaakte projecten zijn terug te vinden via het **Projectoverzicht** (![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")).
 3. Open een projectkaart door één van de regels te selecteren en te klikken op **Bewerken**.
 4. Op de Projectkaart, tabblad **Algemeen**, is een projectnaam en omschrijving te zien. Deze **Naam** en **Omschrijving** van het project worden door het systeem bepaald op basis van de bovenste voorlopige projectregel op de **Kladblokbudgetimportkaart** en dekken mogelijk de lading niet voor alle regels die aan het project zijn gekoppeld. Deze regels zijn terug te zien op tabblad **Budgetregels**. 
 5. Doorloop alle projecten en pas naar behoefte **Naam** en **Omschrijving** aan.

>**Tip!** Maak een uniforme afspraak voor de naamstelling en omschrijving van projecten, bijv.:
 >**Naam** = Soort werk (schilderwerk) + clusternummer (TC0102) of indien meer clusters (diverse clusters)
 > **Omschrijving** = uitgebreide omschrijving werk (Schilderwerk kozijnen, ramen, deuren, boeiborden)
     

### Toevoegen contactpersonen aan project
 1. Het toevoegen van een contactpersoon aan een project kan op het tabblad **Contactpersonen** van de projectkaart.
 2. Klik op een lege regel in de cel van kolom **Contactnr.** op het dropdown-menu en selecteer de juiste contactpersoon uit de lijst die verschijnt.
 3. Voer vervolgens (indien van toepassing) de functiecode, bedrijfsnaam, telefoon en e-mail in. De contactpersoon staat nu gekoppeld aan het project.
 4. Als op de regel van de contactpersoon ook de kolominformatie **Prioriteit** wordt ingevoerd, worden de contactpersonen met de prioriteit 1, 2 en 3 getoond op het tabblad **Algemeen**.

## Aanvullen projectgegevens op projectkaart

 1. Aangemaakte projecten zijn zichtbaar tussen alle actieve projecten in de lijst Projectoverzicht. Navigeer via het zoekveld naar de lijst **Projectoverzicht**.
 2. Na een project te hebben gekozen en in het lint op **Bewerken** te klikken, wordt de projectkaart van uw keuze geopend.
 4. Op het tabblad **Boekingsinfo** staan de default projectbudgethouders ingesteld. Deze default budgethouders zijn gekoppeld aan het projecttype (overwegend de manager en directie). Voeg de projectleider toe aan de budgethouders. Deze handeling is nodig omdat het systeem niet weet wie de projectleider wordt.
 5. Klik hiervoor op de drie puntjes naast het veld **Orderbudgethouders**.
 6. Klik op de eerste lege regel in kolom **Budgethouder**, zoek de projectleider op in de lijst en selecteer deze.
 7. Sluit de Budgethouder-kaart door op de knop **Sluiten** rechtsonder in het venster te klikken.
 8. Herhaal de stappen 4 t/m 6 bij de **Verkoopbudgethouder** en de **Factuurbudgethouder**.
 9. Sluit de project-kaart met **pijltje naar links** en informeer de projectleider dat zijn project is aangemaakt. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ3NTMyMDY2NSwtMTE4MTY2MDY3OSw3OD
E0OTk3NjMsNTg3Mjk3Mzg1LC00OTcwNzMwOSwyMDg4MzIwMDM2
LDIxMzYyNDExMjUsOTkxMzgxNDc0LC05MDUzMzgzNzAsLTYwMj
I3MjYxMSwtMjc4MDc4NDYxXX0=
-->