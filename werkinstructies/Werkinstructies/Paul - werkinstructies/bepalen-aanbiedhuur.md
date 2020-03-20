# Bepalen aanbiedhuur

De aanbiedhuur van de beschikbare verhuurbare eenheid wordt automatisch bepaald op basis van het voor die eenheid geldende huurbeleid. Indien nodig wordt de aanbiedhuur handmatig aangepast. Daarnaast wordt de huurprijsmutatie ingevuld en indien nodig gefiatteerd. 


## Processchema

## Berekenen nieuwe nettohuur conform huurbeleid 

In deze stap zorgt u ervoor dat het systeem automatisch de nieuwe nettohuur voor de beschikbare verhuurbare eenheid berekent op basis van het bij die eenheid ingestelde huurbeleid.

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Verhuurmutatieoverzicht**.
 2. Zoek de verhuurmutatie op waarvoor de aanbiedhuur moet worden bepaald.
 3. Open de detailpagina van de verhuurmutatie.
 4. Klik op **Nieuw** en kies voor **Verhuuraanbieding**. Het contractoverzicht van de OG Eenheid verschijnt met het leegstandscontract en het meest recente verhuurcontract van de vorige huurder. Selecteer de contractregel op basis waarvan  u de nieuwe verhuuraanbieding wilt aanmaken en klik op **OK**. 
 4. De verhuuraanbieding wordt aangemaakt met één of meer **Aaanbiedingscontracten** (zie onder het gelijknamige kopje op de aanbiedingskaart): één aanbiedingscontract voor elke exploitatievorm van het soort *Verhuur* dat is ingesteld bijEr verschijnt een popup met de vraag op basis van welke bestaande contractregel u die is gekoppeld aan de OG Eenheid. Elk aanbiedingscontract heeft één of meer nettohuurelementen waarvan het bedrag automatisch is bepaald op basis van het huurbeleid dat is ingesteld bij de OG Eenheid. Daarnaast kan elk aanbiedingscontract ook nog andere soorten elementen bevatten, bijvoorbeeld elementen met betrekking tot servicekosten en/of eenmalige kosten. Deze andere soorten elementen zijn overgenomen van de contractregel dist 4e u in stap 3 heeft geselecteerd of van het elementsjabloon dat is ingesteld voor de OG Eenheid of het cluster waartoe de OG Eenheid behoort.  
 5. Bepaal op basis van welk aanbiedingscontract u de OG Eenheid wilt publiceren en opnieuw verhuren. Verwijder eventueel de overige aanbiedingscontracten van dnieuwe verhuuraanbieding wil baseren. Selecteer het getoonde leegstandscontracten. 


## Aanpassen aanbiedhuur

In deze stap past u - indien nodig - handmatig de door het systeem berekende aanbiedhuur aan. Dit doet u door het bedrag vavn bestaande elementen aan te passen en/of of door het toevoegen van extra elementen aan het aanbiedingscontract en/of verwijderen van bestaande elementen uit het aanbiedingscontract. 

 1. Selecteer op de aanbiedingskaart onder kopje **Aanbiedingscontracten** het aanbiedingscontract en kies voorlik op **Aanbiedhuur** (u vindt deze actie in hetzelfde deel waar de contracten vermeld staan). Een nieuwe pagina wordt geopend waarop alle elementen van het aanbiedingscontract worden getoond. Elk element van het soort '*Element'* heeft een bedrag dat gelijk is aan **Eenheidprijs** vermenigvuldigd met **Aantal**. Bedragen kunnen niet direct worden gewijzigd, wel indirect via het wijzigen van het aantal en/of de eenheidprijs. 
 2. Als u het bedrag van een bestaand element wilt aanpassen, selecteer dan dat element en pas de waarde in kolom **Eenheidprijs** aan. 
3. Herhaal dit voor alle elementen waarvan u het bedrag wil aanpassen. 
4. Als u een bestaand element wilt verwijderen uit het aanbiedingscontract, selecteer dan dat element, klik op de drie verticale puntjes in de regel en klik op **Regel verwijderen**. 
5. Herhaal  dit voor alle elementen die u wilt verwijderen. 
6. Als u een extra element wilt toevoegen aan het aanbiedingscontract, klik dan in kolom **Soort** op een lege regel onderaan het overzicht met elementen. Selecteer een element uit het elementoverzicht en klik op **OKop **Nieuwe re
1. .

## Invullen huurprijsmutatie

1. Open pagina **Huurcontractopzeggingkaart** van de betreffende huuropzegging. Dit kan vanaf de pagina **Verhuurmutatieoverzicht** (selecteer de Verhuurmutatie die is aangemaakt tijdens de vorige stap en kies voor **Huuropzegging**).  ul een aarde in in kolom **Eenheidprijs**.**.  Vul een waarde in in kolom **EHet kan ook via overzichtspagina **Huuropzeggingeln**, (selecteer een elementnummer en vul in een eenheidprijs**. 
7. Herhaal dit voor alle extra elementen die u wilt toevoegen. 
8. Klik op **Sluiten**. 

## Invullen huurprijsmutatie

In deze stap vult u de huurprijsmutatie in. Hiermee specificeert u wat de reden is waarom de huurprijs van de verhuurbare eenheid wijzigt. Mocht de nieuwe nettohuur ongelijk zijn aan de streefhuur van de verhuurbare eenheid, specificeert u daarnaast dan ook wat de reden van die afwijking is. 

1. . Selecteer op de aanbiedingskaart het aanbiedingscontract en klik op **Huurprijsmutatie** (u vindt deze actie in hetzelfde deel waar de contracten vermeld staanvoorheen genoemd **Verhuurmutatie**). Een nieuwe pagina genaamd **Huurprijsmutatie** wordt geopend. Op deze pagina wordt o.a. de streefhuur van de OG Eenheid vermeld die geldig is op de ingangsdatum van het aanbiedingscontract, rekening houdend met de ingestelde streefhuurhorizon. 
2. Selecteer een reden in veld **Reden wijziging**. 
3. AlsIndien de nieuwe nettohuur afwijkt van de streefhuur, selecteer dan  een **Reden afwijking** onder het kopjein tabblad **Afwijkingsreden voor verschil tussen streefhuur en nieuwe nettohuur**.
4. K en klik op **Sluiten**. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MjU4Njk2MTAsLTQ5MDU5NTM4MiwtMj
AxNzE5ODUyMiwyMDgxMjMwNTYyLC03NTgzMDc4MjksLTIxMTc5
MDk0OTMsMTQ2NTc3Mzg3MSw5OTUyNTA5NTQsNDM5NjY5ODE4LD
g2NTQ3NTc3MywtNzY1NDAxMzgyXX0=
-->