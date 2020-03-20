
# Uitvoeren jaarlijkse huurverhoging
In dit werkproces wordt de jaarlijkse huurverhoging uitgevoerd op basis van het vastgelegde huurverhogingsbeleid. Daarbij wordt voor elke eenheid de nieuwe nettohuur berekend: eerst in simulatie, en als definitief wanneer de uitkomsten van de simulatie acceptabel zijn. De berekening vindt per eenheid plaats op basis van het aan de eenheid toegewezen huurverhogingsbeleidstype en de nettohuuraftopping. Nadat de nieuwe nettohuur definitief is berekend, wordt de huurverhoging geëffectueerd. Ten slotte worden de klanten aangezegd, d.w.z. officieel geïnformeerd over de nieuwe nettohuur die ze vanaf de huurverhogingsdatum moeten gaan betalen. 

## Toewijzen beleidstypes 
In deze stap wijst u de vastgelegde huurverhogingsbeleidstypes toe aan de OG Eenheden waarvan u de nettohuur wilt aanpassen: per OG Eenheid één beleidstype. Als u in het verleden al beleidstypes heeft toegewezen aan OG Eenheden, dan is deze toewijzing in principe nog steeds bruikbaar voor de jaarlijkse huurverhoging van het nieuwe tijdvak. In dat geval hoeft u alleen beleidstypes toe te wijzen aan OG Eenheden die in dit nieuwe tijdvak tot een ander deel van uw bezit behoren dan in het vorige tijdvak (bijvoorbeeld doordat een woning recentelijk is bestempeld als sloopwoning).

Het beleidstype van een OG Eenheid bepaalt met name met welk percentage de nettohuur wordt aangepast. 

U kunt de beleidstypes op twee manieren toewijzen aan OG Eenheden: 
a. Aan een individuele OG Eenheid via de pagina **Onroerend goed eenheidkaart** 
b. In bulk aan meerdere OG Eenheden, via een import uit een Excel-werkblad waarin per OG Eenheid het nummer van de OG Eenheid en de code van het toe te wijzen beleidstype is vermeld. Om dit Excel-werkblad te kunnen importeren, moet de eerste kolom exact de naam **Eenheidnr.** hebben en de tweede kolom de naam **Huurverhogingsbeleidstypecode**. 

_**Ad a:**_
 1. Ga via de zoekfunctionaliteit ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")  naar **Onr. Goed Eenhedenoverzicht**. 
 2. Klik op het **Nr.** van de OG Eenheid waaraan u een beleidstype wil toewijzen. De pagina **Onroerend goed eenheidkaart** wordt geopend met de details van de geselecteerde OG Eenheid. 
 3. Open tabblad **Exploitatie (Fin.)**. 
 4. Selecteer in veld **Huurverhogingsbeleidstype** het juiste beleidstype. 
 5. Sluit de pagina. 

_**Ad b:**_
1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Huurverhogingseigenschappen voor OG Eenheden importeren**.  Een pagina wordt geopend met enkele opties. 
2. Selecteer in optie **Werkmapbestandsnaam** het juiste Excel-bestand. 
3. Selecteer in optie **Werkbladnaam** het juiste werkblad in de geselecteerde werkmap. 
4. Klik op **OK**.  


## Toewijzen aftoppingen 
In deze stap wijst u de vastgelegde nettohuuraftoppingen toe aan de OG eenheden waarvan u de nettohuur wilt aanpassen: per OG Eenheid één aftopping. Als u in het verleden al aftoppingen heeft toegewezen aan OG Eenheden, dan is deze toewijzing in principe nog steeds bruikbaar voor de jaarlijkse huurverhoging van het nieuwe tijdvak. In dat geval hoeft u alleen aftoppingen toe te wijzen aan OG Eenheden die dit nieuwe tijdvak tot een ander deel van uw bezit behoren dan vorig tijdvak (bijvoorbeeld doordat een woning recentelijk is bestempeld als sloopwoning).  

De aftopping bepaalt tot welk maximum bedrag de nieuwe nettohuur wordt afgetopt.

U kunt de aftoppingen op twee manieren toewijzen aan OG Eenheden: 
a. Aan een individuele OG Eenheid via de pagina **Onroerend goed eenheidkaart** 
b. In bulk aan meerdere OG Eenheden, via een import uit een Excel-werkblad waarin per OG Eenheid het nummer van de OG Eenheid en de code van het toe te wijzen beleidstype is vermeld. Om dit Excel-werkblad te kunnen importeren, moet de eerste kolom exact de naam **Eenheidnr.** hebben en de derde kolom de naam **Nettohuur aftoppingscode**. 

_**Ad a:**_
1. Ga via de zoekfunctionaliteit ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")  naar **Onr. Goed Eenhedenoverzicht**. 
3. Klik op het **Nr.** van de OG Eenheid waaraan u een beleidstype wil toewijzen. De pagina **Onroerend goed eenheidkaart** wordt geopend met de details van de geselecteerde OG Eenheid. 
4. Open tabblad **Exploitatie (Fin.)**. 
5. Selecteer in veld **Nettohuuraftopping** de juiste aftopping. 
6. Sluit de pagina. 

_**Ad b:**_
1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Huurverhogingseigenschappen voor OG Eenheden importeren**.  Een pagina wordt geopend met enkele opties. 
2. Selecteer in optie **Werkmapbestandsnaam** het juiste Excel-bestand. 
3. Selecteer in optie **Werkbladnaam** het juiste werkblad in de geselecteerde werkmap. 
4. Klik op **OK**.  


## Aanvragen huishoudverklaringen 
In deze stap vraagt u huishoudverklaringen aan voor die OG Eenheden waarvoor u van plan bent de nettohuur inkomensafhankelijk te verhogen, d.w.z. verhogen met een percentage dat boven het maximum basisverhogingspercentage ligt dat door de Rijksoverheid is vastgesteld voor het betreffende huurverhogingstijdvak.  Deze huishoudverklaringen vraagt u aan bij de Belastingdienst via een zogenoemd vraagbestand. Dit vraagbestand kunt u exporteren uit Dynamics Empire. De Belastingdienst verstrekt de aangevraagde huishoudverklaringen in de vorm van een antwoordbestand. Dit antwoordbestand kunt u importeren in Dynamics Empire. 

U maakt als volgt een vraagbestand aan dat u kunt verstrekken aan de Belastingdienst: 
1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Aanvraaggegevens huishoudverklaringen exporteren**.  Een pagina wordt geopend met enkele opties en filtermogelijkheden. 
2. Selecteer het **Huurverhogingstijdvak** waarop de inkomensafhankelijke huurverhoging betrekking heeft. 
3. Selecteer de **Huurverhogingsdatum** waarop de huurverhoging ingaat. 
4. Stel de filters zodanig in dat alleen die OG Eenheden worden geselecteerd waarvoor u daadwerkelijk van plan bent de nettohuur inkomensafhankelijk te verhogen. 
5. Klik op **OK**. Het systeem maakt het vraagbestand aan. 
6. Klik op **Opslaan** en selecteer de locatie waar het bestand moet worden opgeslagen. Let op: afhankelijk van het aantal regels kan door het systeem meer dan één vraagbestand worden aangemaakt. 
7. Upload het vraagbestand (of de vraagbestanden) via het webportaal van de Belastingdienst. Voor meer informatie, zie:   [http://www.inkomensafhankelijkehuurverhoging.nl](http://www.inkomensafhankelijkehuurverhoging.nl). 

U importeert als volgt het antwoordbestand dat u heeft ontvangen van de Belastingdienst: 
1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Huishoudverklaringen importeren**.  Een pagina wordt geopend met twee opties. 
2. Selecteer het antwoordbestand in optie **Bestandsnaam**. 
3. Selecteer de **Huurverhogingsdatum** waarop de huurverhoging ingaat. 
4. Klik op **OK**.  


## Simuleren nieuwe nettohuur 
In deze stap simuleert u de berekening van de nieuwe nettohuur van één of meer OG Eenheden, op basis van de aan die OG Eenheden toegewezen beleidstypen en aftoppingen. Daartoe maakt u eerst voor die OG Eenheden huurverhogingsparameters aan, waarin alle gegevens worden verzameld die nodig zijn om de nieuwe nettohuur te berekenen. Vervolgens berekent u op basis van die parameters de nieuwe nettohuur in simulatie. De uitkomst van de berekening in simulatie wordt alleen opgeslagen in de tabel van de jaarlijkse huurverhoging, en dus niet in de contractregels van de OG Eenheden. De uitkomst van de simulatie heeft dus geen enkele invloed op de prolongatie van verhuurcontracten van de OG Eenheden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Huurverhogingsparameters voor OG Eenheden aanmaken**.  Een pagina wordt geopend. 
2. Selecteer in veld **Tijdvakcode** de code van het huurverhogingstijdvak waarvoor u de parameters wil aanmaken. 
3. Stel eventueel filters in als u slechts voor een gedeelte van het bezit de parameters wil aanmaken. Als u geen filters instelt, dan zal het systeem van alle OG Eenheden parameters proberen aan te maken. 
4. Klik op **OK**. Het systeem maakt voor alle OG Eenheden die voldoen aan de filteren de huurverhogingsparameters aan voor het geselecteerde tijdvak. 
5. Mochten voor één of meer OG Eenheden essentiële gegevens (zoals huurverhogingsbeleidstype) ontbreken die nodig zijn voor het berekenen van de nieuwe nettohuur, dan genereert het systeem een exceptierapport. Op dat exceptierapport wordt per OG Eenheid gespecificeerd welke gegevens ontbreken. 
6. Stel de ontbrekende  gegevens voor de betreffende OG Eenheden alsnog in en maak de parameters opnieuw aan. 
7. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Jaarlijkse hHuurverhoging soverzicht**.  Het huurverhogingsoverzicht wordt geopend. 
8. Pas indien nodig het filter op kolom **Tijdvakcode** aan, zodat de huurverhogingen van het juiste tijdvak worden getoond. 
9. Alle OG Eenheden waarvoor u de parameters heeft aangemaakt, worden getoond op het overzicht. Voor OG Eenheden waarvan de parameters succesvol zijn aangemaakt, bevat kolom **Verwerkingsstatus** de waarde *Aangemaakt*. De waarden van de parameters staan vermeld in de desbetreffend kolommen. 
10. Voor OG Eenheden waarvan het aanmaken van de parameters een exceptie opleverde, bevat kolom **Verwerkingsstatus** de waarde *Overgeslagen*. 
11. Als u de details van de parameters wil bekijken van een OG Eenheden, klik dan op de **Tijdvakcode** in de desbetreffende regel van het overzicht. De detailpagina van de geselecteerde huurverhoging wordt geopend. De parameters staan vermeld  de tabbladen **Uitgangspunten**, **Instellingen - verhogingspercentage en batch**, **Intellingen - primaire aftopping** en **Instellingen - secundaire aftopping op maximale huurprijs**. Sluit de detailpagina.  
12. Selecteer de huurverhogingen van de OG Eenheden met verwerkingsstatus *Aangemaakt* waarvan u de nieuwe nettohuur in simulatie wil berekenen.  
13. Klik op **Proces** en kies voor **Berekenen (simulatie)**. De nieuwe nettohuur van de geselecteerde OG Eenheden wordt berekend in simulatie-modus en de **Verwerkingsstatus** van de geselecteerde huurverhogingen wordt aangepast naar *Simulatie*. 
14.  De uitkomst van de berekening (o.a. **Nieuwe nettohuur** en **Effectief verhogingspercentage**) wordt vermeld in de desbetreffende kolommen in het overzicht.  


## Controleren nieuwe nettohuur 
In deze stap controleert u de uitkomst van de simulatie van de berekening van de nieuwe nettohuur. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Huurverhogingsoverzicht**.  Het huurverhogingsoverzicht wordt geopend. 
2. U kunt de uitkomst van de berekening controleren in de desbetreffende kolommen (o.a. **Nieuwe nettohuur** en **Effectief verhogingspercentage**) van het overzicht. 
3. Als u de details van de uitkomst van de berekening wilt bekijken van een OG Eenheid, klik dan op de **Tijdvakcode** in de desbetreffende regel van het overzicht. De detailpagina van de geselecteerde huurverhoging wordt geopend. De uitkomst van de berekening staat vermeld in de tabbladen **Berekening en effectuering** en **Nettohuur elementen**. Sluit de detailpagina. 
4. U kunt de uitkomsten van de berekening ook vanaf het overzicht exporteren naar Excel (klik op **Pagina** en kies voor **Openen in Excel**). In Excel kunt u o.a. de gemiddelde huursomstijging als gevolg van de jaarlijkse huurverhoging berekenen. 

Mocht de uitkomst van de simulatieberekening niet acceptabel zijn, pas dan het huurverhogingsbeleid van de desbetreffende OG Eenheden aan. Bijvoorbeeld: 
 - door het ingestelde verhogingspercentage van één of meer beleidstypes aan te passen; 
 - door andere beleidstypes en/of andere aftoppingen toe te wijzen aan bepaalde OG Eenheden;
 - door de eigenschappen van bepaalde beleidstypes te wijzigen. 

>**Let op**: Nadat u het huurverhogingsbeleid heeft aangepast, moet u eerst de huurverhogingsparameters van de desbetreffende OG Eenheden opnieuw aanmaken, voordat u opnieuw de nieuwe nettohuur van die OG Eenheden in simulatie gaat berekenen. Doet u dat niet, dan wordt de berekening uitgevoerd op basis van de vorige parameters waarin de gegevens zijn vastgelegd van het huurverhogingsbeleid zoals dat destijds was vastgelegd. In dat geval zal de uitkomst van de nieuwe berekening exact hetzelfde zijn als de vorige berekening. 


## Definitief berekenen nieuwe nettohuur 
In deze stap maakt u een definitieve berekening van de nieuwe nettohuur van geselecteerde OG Eenheden waarvan de uitkomst van de simulatie acceptabel was. Doordat de definitieve berekening wordt gedaan op basis van dezelfde huurverhogingsparameters als de simulatieberekening, is de uitkomst van de definitieve berekening gelijk aan die van de simulatieberekening. Het verschil is dat de uitkomst van de definitieve berekening per eenheid wordt opgeslagen in de contractregel die fungeert als basiscontract voor de jaarlijkse huurverhoging (d.w.z. de contractregel die geldig is op de dag vóór de huurverhogingsdatum). 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Huurverhogingsoverzicht**.  Het huurverhogingsoverzicht wordt geopend. 
2. Pas indien nodig het filter op kolom **Tijdvakcode** aan, zodat de huurverhogingen van het juiste tijdvak worden getoond. 
3. Selecteer de huurverhogingen van de OG Eenheden waarvan u de nieuwe nettohuur definitief wilt berekenen.  
4. Klik op **Proces** en kies voor **Berekenen (definitief)**. De nieuwe nettohuur van de geselecteerde OG Eenheden wordt definitief berekend en de **Verwerkingsstatus** van de geselecteerde huurverhogingen wordt aangepast naar *Definitief*. 
5.  Per OG Eenheid wordt de **Batch** opgeslagen in de contractregel die fungeert als basiscontract voor de jaarlijkse huurverhoging en wordt het berekende **Effectieve verhogingspercentage** opgeslagen in de **Nettohuurelementen** van de genoemde contractregel. 
6. Om dit te controleren voor een OG Eenheid selecteert u de huurverhoging van die OG Eenheid op het **Huurverhoginsgoverzicht**. Navigeer naar **Contract**. Het contractoverzicht wordt geopend waarop de contractregel wordt vermeld die fungeert als basiscontract voor de jaarlijkse huurverhoging. Navigeer naar **Elementen**. Het elementenoverzicht wordt geopend. In kolom **Bedrag** wordt de **Huidige nettohuur** getoond en in kolom **Bedrag na huurverhoging** de definitief berekende **Nieuwe nettohuur**. 


## Effectueren huurverhoging 
In deze stap effectueert de de huurverhoging van geselecteerde eenheden. Daarbij wordt voor elke eenheid een nieuwe contractregel aangemaakt die ingaat op de huurverhogingsdatum. De nettohuur van deze nieuwe contractregel bevat het nieuwe bedrag. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Huurverhoging verwerken**.  Een pagina met opties en filtermogelijkheden wordt geopend. 
2. Selecteer de **Huurverhogingsdatum**. 
3. Selecteer een **Huurprijsmutatiereden**. 
4. Selecteer de **Huurverhogingsbatchnaam** waarvan u de huurverhoging wil effectueren. 
5. Specificeer eventueel in veld **Eenheidnr.** de OG Eenheden waarvan u de huurverhoging wil effectueren. 
6. Klik op **OK**. De huurverhoging wordt geëffectueerd voor de geselecteerde batch en geselecteerde OG Eenheden. 
7. Op het **Huurverhogingsoverzicht** is de **Verwerkingsstatus** van de geëffectueerde huurverhogingen aangepast naar *Geëffectueerd*. Het systeem heeft voor alle geselecteerde OG Eenheden een nieuwe contractregel aangemaakt waarvan de ingangsdatum gelijk is aan de huurverhogingsdatum. 
8. Om dit te controleren voor een OG Eenheid selecteert u de huurverhoging van die OG Eenheid op het **Huurverhoginsgoverzicht**. Klik op **Navigeren** en kies **Contractoverzicht**. Het contractoverzicht wordt geopend waarop alle contractregels van de geselecteerde OG Eenheid worden vermeld. De bovenste contractregel is de nieuwe contractregel die is aangemaakt door het effectueren van de huurverhoging.  


## Aanzeggen klant 
In deze stap genereert u huurverhogingsbrieven voor alle klanten die eenheden huren waarvan de nettohuur is aangepast. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de taak **Huurverhoging - Document**.  Een pagina met opties en filtermogelijkheden wordt geopend. 
2. Selecteer de **Huurverhogingsbatchnaam** van de indexeringsbatch waarvoor u de huurverhogingsbrieven wil genereren. 
3. Selecteer de **Documentdatum**. 
4. Geef in optie **Spec, woningwaardering afd.** aan of u een specificatie van de woningwaardering wil afdrukken als bijlage bij de huurverhogingsbrief. 
5. Geef in optie **Interactie registeren** aan of u wil dat het systeem al dan niet een interactie registreert voor elke klant waarvoor een huurverhogingsbrief wordt gegenereerd. 
6. Selecteer de **Huurverhogingsdatum** waarvoor u de huurverhogingsbrief wil genereren. 
7. Klik op **Afdrukken**. De huurverhogingsbrieven worden gegenereerd. 
8. Herhaal bovenstaande stappen voor de overige indexeringsbatchen die zijn gebruikt bij het uitvoeren van de jaarlijkse huurverhoging. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIyNjY1MzY4NiwtMjA5MzE2Mjk4NSwtMT
MxODM1MjIyNywtOTQyMzE5NDg2LC03MTQzOTQ3MTcsLTE1MTE3
NDUzMSw5NjU0NzU3MDcsMTA0ODgxOTU4OCw3ODQxNjI1NjQsLT
cyOTc3NzMzLC0yMDAzMDY4MDM1LC0yNzgxNTI2MzIsOTgzMzcy
NTIsLTE4OTA2NDEwMTAsMTI2MDU3ODY4OV19
-->