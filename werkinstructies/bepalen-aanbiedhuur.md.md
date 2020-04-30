
# Bepalen aanbiedhuur

De aanbiedhuur van de beschikbare verhuurbare eenheid wordt automatisch bepaald op basis van het voor die eenheid geldende huurbeleid. Indien nodig wordt de aanbiedhuur handmatig aangepast. Daarnaast wordt de huurprijsmutatie ingevuld en indien nodig gefiatteerd.

## Berekenen nieuwe nettohuur conform huurbeleid

In deze stap zorgt u ervoor dat het systeem automatisch de nieuwe nettohuur voor de beschikbare verhuurbare eenheid berekent op basis van het bij die eenheid ingestelde huurbeleid en de bij de doelgroep van de eenheid  ingestelde doelgroeplimiet.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verhuurmutatieoverzicht**.
2. Zoek de verhuurmutatie op waarvoor de aanbiedhuur moet worden bepaald.
3. Open de detailpagina van de verhuurmutatie.
4. Klik op **Nieuw** en kies voor **Verhuuraanbieding**. Het contractoverzicht van de OG Eenheid verschijnt met het leegstandscontract en het meest recente verhuurcontract van de vorige huurder. Selecteer de contractregel op basis waarvan  u de nieuwe verhuuraanbieding wilt aanmaken en klik op **OK**.
5. De verhuuraanbieding wordt aangemaakt met één of meer **Aanbiedingscontracten** (zie onder het gelijknamige kopje op de aanbiedingskaart): één aanbiedingscontract voor elke exploitatievorm van het soort *Verhuur* dat is ingesteld bij de OG Eenheid. 
	- Elk aanbiedingscontract heeft één of meer nettohuurelementen waarvan het totaalbedrag gelijk is aan de zogenoemde referentie-nettohuur. Deze referentie-nettohuur wordt automatisch berekend door toepassing van het huurbeleid dat is ingesteld bij de OG Eenheid, gevolgd door aftopping op het effectieve limietbedrag van de doelgroep die is toegewezen aan de OG Eenheid (alleen als er een doelgroep is toegewezen aan de OG Eenheid). Als toepassing van het huurbeleid ertoe leidt dat de streefhuur van de OG Eenheid wordt gebruikt als uitgangspunt voor de referentie-nettohuur, dan wordt die streefhuur berekend met als peildatum de huurbeleid-referentiedatum. Deze huurbeleid-referentiedatum datum wordt berekend door de streefhuurhorizon op te tellen bij de verhuurbaar-per-datum die is ingevuld bij de huuropzegging. 
	- Daarnaast kan elk aanbiedingscontract ook nog andere soorten elementen bevatten, bijvoorbeeld elementen met betrekking tot servicekosten en/of eenmalige kosten. Deze andere soorten elementen zijn overgenomen van de contractregel die u in stap 4 heeft geselecteerd of van het elementsjabloon dat is ingesteld voor de OG Eenheid of het cluster waartoe de OG Eenheid behoort.  
6. Bepaal op basis van welk aanbiedingscontract u de OG Eenheid wilt publiceren en opnieuw verhuren. Verwijder eventueel de overige aanbiedingscontracten van de verhuuraanbieding.

## Aanpassen aanbiedhuur

In deze stap past u - indien nodig - handmatig de door het systeem berekende aanbiedhuur aan. Dit doet u door het bedrag van bestaande elementen aan te passen en/of of door het toevoegen van extra elementen aan het aanbiedingscontract en/of verwijderen van bestaande elementen uit het aanbiedingscontract. Let op: als u nettohuur-elementen toevoegt, wijzigt of verwijdert, dan heeft dat tot gevolg dat de nieuwe nettohuur afwijkt van de referentie-nettohuur die is berekend op moment van aanmaken van de verhuuraanbieding. 

1. Selecteer op de aanbiedingskaart onder kopje **Aanbiedingscontracten** het aanbiedingscontract en kies voor **Aanbiedhuur** (u vindt deze actie in hetzelfde deel als waar de contracten vermeld staan). Een nieuwe pagina wordt geopend waarop alle elementen van het aanbiedingscontract worden getoond. Elk element van het soort '*Element'* heeft een bedrag dat gelijk is aan **Eenheidprijs** vermenigvuldigd met **Aantal**. Bedragen kunnen niet direct worden gewijzigd, wel indirect via het wijzigen van het aantal en/of de eenheidprijs.
2. Als u het bedrag van een bestaand element wilt aanpassen, selecteer dan dat element en pas de waarde in kolom **Eenheidprijs** aan.
3. Herhaal dit voor alle elementen waarvan u het bedrag wil aanpassen.
4. Als u een bestaand element wilt verwijderen uit het aanbiedingscontract, selecteer dan dat element, klik op de drie verticale puntjes in de regel en klik op **Regel verwijderen**.
5. Herhaal  dit voor alle elementen die u wilt verwijderen.
6. Als u een extra element wilt toevoegen aan het aanbiedingscontract, klik dan in kolom **Soort** op een lege regel onderaan het overzicht met elementen. Selecteer een element uit het elementoverzicht en klik op **OK**. Vul een waarde in in kolom **Eenheidprijs**.
7. Herhaal dit voor alle elementen die u wilt toevoegen.

De referentie-nettohuur bevat een waarde die is berekend op het moment dat het huurbeleid de laatste keer was toegepast. Deze huidige waarde kan inmiddels achterhaald zijn, bijvoorbeeld doordat: 
 - Bij de OG Eenheid een ander huurbeleid of andere doelgroep is ingesteld;
 - De doelgroeplimiet is gewijzigd;  
 - De ingangsdatum of het subsidiabel servicebedrag van het aanbiedingscontract is gewijzigd. 
 
In dat geval kunt u de waarde van de referentie-nettohuur van het aanbiedingscontract opnieuw laten berekenen door het huurbeleid opnieuw toe te laten passen op basis van de actuele situatie.  
1. Selecteer het aanbiedingscontract 
2. Klik op de knop **Huurbeleid verschillen**. Een pagina verschijnt waarop de huurbeleidsparameters worden getoond met hun huidige waarde (berekend en opgeslagen de laatste keer dat het huurbeleid was toegepast) en hun nieuwe waarde (conform de actuele situatie). 
3. Klik op de knop **Huurbeleid opnieuw toepassen**. Het systeem voert de volgende acties uit: 
	- De nieuwe waarden van de huurbeleidsparameters (inclusief referentie-nettohuur) opslaan bij het geselecteerde aanbiedingscontract; 
	- De nettohuur van het geselecteerde aanbiedingscontract gelijk maken aan de nieuwe waarde van de referentie-nettohuur; 
	- De huurprijsmutatie van het aanbiedingscontract verwijderen. 


## Invullen huurprijsmutatie

In deze stap vult u de huurprijsmutatie in. Hiermee specificeert u wat de reden is waarom de huurprijs van de verhuurbare eenheid wijzigt. Mocht de nieuwe nettohuur ongelijk zijn aan de referentie-nettohuur van de verhuurbare eenheid, specificeert u daarnaast dan ook wat de reden van die afwijking is.

1. Selecteer op de aanbiedingskaart het aanbiedingscontract en klik op **Huurprijsmutatie** (u vindt deze actie in hetzelfde deel waar de contracten vermeld staan, voorheen genoemd **Verhuurmutatie**). Een nieuwe pagina genaamd **Huurprijsmutatie** wordt geopend. Op deze pagina wordt o.a. de referentie-nettohuur van de OG Eenheid vermeld, plus alle uitgangspunten op basis waarvan het systeem de referentie-nettohuur heeft berekend.
2. Selecteer een reden in veld **Reden wijziging**.
3. Als de nieuwe nettohuur afwijkt van de referentie-nettohuur, selecteer dan  een **Reden afwijking** onder het kopje **Afwijkingsreden voor verschil tussen referentie-nettohuur en nieuwe nettohuur**.
4. Klik op **Sluiten**.


## Fiatteren nettohuur 

In deze stap fiatteert u de nieuwe nettohuur. Hierbij wordt ervan uitgegaan dat de verhuuraanbieding al is gemaakt en de huurprijsmutatie al is ingevuld. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verhuurmutatieoverzicht**.
2. Zoek de verhuurmutatie op waarvoor de nieuwe nettohuur moet worden gefiatteerd.
3. Open de detailpagina van de verhuurmutatie.
4. Stel vast dat de mijlpaal **Aanbiedhuur is gefiatteerd** nog niet is bereikt, d.w.z. de waarde *Nee* heeft. De waarde van deze mijlpaal heeft de vorm van een link. 
5. Klik op deze link. De pagina met details van de huurprijsmutatie wordt geopend. 
6. Zet het schuifje van het veld **Fiat** naar rechts. 
7. Klik op **Sluiten**. U keert terug op de detailpagina van de verhuurmutatie. Stel vast dat de mijlpaal **Aanbiedhuur is gefiatteerd** nu wel is bereikt.
8. Sluit de pagina. 



## Zie ook

[Aanbieden eenheid](../aanbieden-eenheid/)  
[Beheren verhuurbare eenheidsinformatie](../beheren-verhuurbare-eenheidsinformatie/)  
[Innemen eenheid](../innemen-eenheid/)  
[Ondertekenen huurovereenkomst](../ondertekenen-huurovereenkomst/)  
[Opleveren eenheid](../opleveren-eenheid/)
[Opstellen eindafrekening](../opstellen-eindafrekening/)  
[Registreren huuropzegging](../registreren-huuropzegging/)  
[Verantwoorden verhuring](../verantwoorden-verhuring/)  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3OTk1NTY0NzFdfQ==
-->