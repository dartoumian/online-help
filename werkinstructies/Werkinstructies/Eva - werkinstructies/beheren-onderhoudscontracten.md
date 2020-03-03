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

### Het verwerken van de begrotingsregels
 1. De begrotingsregels in dit eerste voorbeeld zijn compleet geimporteerd. Dat wil zeggen, in de begrotingsregels is de samenstelling van de projecten al bepaald d.m.v. een **Sjablooncode**. Daarnaast is per begrotingsregels bepaald wie het **contactpersoon** welke rol deze persoon binnen de projecten zal uitvoeren (projectleider, toezichthouder, woonconsulent, contractbeheerder). Tevens in de initiële planning bepaald in de velden **start -en opleverdatum**.
 2. Klik om de regels te verwerken op door in het lint **Acties - Functies - Samenvoegen alle regels op basis van Sjablooncode**.
 3. Dynamics Empire zal alle begrotingsregels op tabblad **Kladblok importregels** samenvoegen of kopiëren naar tabblad **Voorlopige projectregels** waarbij de volgende bewerkingen worden uitgevoerd.
 
### Het verwerken van de begrotingsregels
Het samenvoegen van begrotingsregels is nodig om de vele regels terug te brengen naar een ingedikte vorm ten behoeve van de budgetbewaking. De stelregels is, dat je de begroting zo gedetailleerd mogelijk overzet naar Dynamics Empire, zodat je in Dynamics Empire kan terugkijken hoe een project begroot is. Dit is nodig om budgetoverschrijdingen te kunnen verklaren. Echter, op dit detailniveau is het niet wenselijk om budgetten te bewaken.

Aan het samenvoegen zijn voorwaarden verbonden. De begrotingsregels dienen te zijn opgebouwd uit dezelfde waarden voor Cluster, Bouwblok, Werksoort, Werksoortboekingsgroep, Sjablooncode en Vrije code budget.

 1. Deze regels zullen na actie **Samenvoegen alle regels op basis van Sjablooncode**, worden samengevoegd tot één regel.
 2. De samengevoegde regel is terug te vinden op tabblad **Voorlopige projectregels**.
 3. Alle begrotingsregels die niet kunnen worden samengevoegd, zijn binnen de kladblokimportregels te herkennen aan hun opmaak van de kolom clusternummer.
 4. Door deze regels te selecteren en in het lint van de kladblokimportregels te kiezen voor **Beheren - Kopiëren**   worden deze regels als losse Voorlopige projectregels bij de samengevoegde regels geplaatst.
 5. Alle regels met dezelfde Voorlopige projectnummer zullen bij het aanmaken van onderhoudsprojecten gekoppeld worden onder één project. De sjablooncode is deze kolom is aan te passen, indien in Excel een foutje is gemaakt.

### Het oplossen van samenvoegingsconflicten

 1. Wanneer regels voldoen aan de criteria om te worden samengevoegd, maar de Projectomschrijving, Contactpersonen, Plaats of vrije tekstvelden van die regels verschillen, treed er een samenvoegingsconflict op. Dit is te zien aan een JA in kolom **Samenvoegingsconflict** op tabblad Voorlopige projectregels
 2. Klik op **Ja** in deze kolom om de oorspronkelijke regels te tonen.
 3. Doorloop op alle samenvoegingsconflicten en los ze één voor één op.

*Tip! Plaats een filter op alle regels met een samenvoegingsconflict voordat je bezig gaat met het oplossen. Dit doe je door met de rechter muisknop op een willekeurige Ja in kolom Samenvoegingsconflict te klikken en Filteren op deze waarde te selecteren. Met Filter wissen hef je de filter weer op*

### Functie instellen voor contactpersonen

 1. Op tabblad **Functies** kan je instellen welke **rol code** toegekend moet worden aan de contactpersonen bij het aanmaken van projecten.

 






 



<hr>

>#### Uitlichten van tip/extra aandachtspunt o.i.d. (H4)
>
>


<hr>

## Zie ook (links naar andere werkprocessen uit dezelfde bedrijfsfunctie) (H2)
Werkinstructie X  
Werkinstructie Y  
Werkinstructie Z
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDQ1NTg4NjEwLC02MDIyNzI2MTEsLTI3OD
A3ODQ2MV19
-->