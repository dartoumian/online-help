# Publiceren eenheid

De beschikbare eenheid wordt gepubliceerd, zodat woningzoekenden kunnen reageren op de eenheid. Hierbij wordt ervan uitgegaan dat de eenheid via de standaard VERA-WRV-koppeling wordt gepubliceerd in een extern woonruimteverdeelsysteem, zoals WoningNet of ZIG. 
Het publiceren gaat in twee stappen: voorbereiden van de xpublicatie in Dynamics Empire en daadwerkelijk publiceren van de eenheid in het woonruimteverdeelsysteem. Nadat de publicatie is gesloten, worden de reacties van de woningzoekenden verwerkt en wordt de rangorde van de kandidaten bepaald in het woonruimteverdeelsysteem.  


## Voorbereiden publicatie   

In deze stap bereidt u de publicatie van de beschikbare eenheid voor. Deze voorbereidende stap vindt plaats in Dynamics Empire. Daarbij verzamelt u alle details over de eenheid, de publicatie en de huurprijs waarvoor de eenheid wordt gepubliceerd. 

 1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Verhuurmutatieoverzicht**.
 2. Zoek de verhuurmutatie op waarvan de publicatie moet worden voorbereid en open de detailpagina van de verhuurmutatie door op het nummer te klikken. 
 3. Navigeer naar de **Beschikbare OG Eenheid**.  Een pagina verschijnt waarop alle details van de beschikbare OG Eenheid worden verzameld die naar het externe woonruimteverdeelsysteem worden verstuurd.  Mocht u in plaats daarvan een foutmelding krijgen, kies dan eerst voor **Verhuuraanbieding** en klik daarna op **Voorbereiden beschikbare OG Eenheid**.  Dan verschijnt de genoemde pagina alsnog.
 4. Op tabblad **Algemeen** wordt in veld **WRV-systeemcode** het woonruimteverdeelsysteem getoond waarin de beschikbare eenheid zal worden gepubliceerd. Het systeem selecteert het WRV-systeem automatisch aan de hand van de **Divisie** van de OG Eenheid. 
 5. Controleer de details op tabblad **Adres** van de beschikbare eenheid. Als deze details niet juist of volledig zijn, navigeer dan naar **OG Eenheid**. De onroerend goed eenheidkaart wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen of aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt. 
 6. Controleer de details op tabblad **OG Eenheid-eigenschappen**.  (Klik indien nog nodig op de naam op het tabblad te openen.) Dit tabblad bevat enkelvoudige en meervoudige VERA-eigenschappen. 
 7. **Enkelvoudige VERA-eigenschappen** zijn eigenschappen waarbij elke OG Eenheid maximaal één waarde kan hebben. Dit betreft de details **VERA-eenheidsoort** t/m **VERA-energielabel**.  Als deze enkelvoudige VERA-eigenschappen niet juist of volledig zijn, navigeer dan naar **OG Eenheid**. De onroerend goed eenheidkaart wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt. 
 8. **Meervoudige VERA-eigenschappen** zijn eigenschappen waarbij elke OG Eenheid 0, 1 of meer waarden kan hebben. Dit betreft de details **VERA-toegankelijksheidslabel** t/m  **VERA-eenheidenergievoorziening**.  Als deze meervoudige VERA-eigenschappen niet juist of volledig zijn, navigeer dan via de menu-opties naar de **VERA-eigenschappen**. De pagina met meervoudige VERA-eigenschappen wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, worden verzameld die naar het externe woonruimteverdeelsysteem worden verstuurd. 
 9. Controleer de details in het adres van de beschikbare eenheid. Als het adres niet juist of volledig is, navigeer dan naar **OG Eenheid**. De onroerend goed eenheidkaart wordt geopend waarop u het adres kunt aanpassen of aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt. 
 10. Controleer de OG-Eenheid-eigenschappen waarop de details automatisch zijn bijgewerkt. 
 11. De details op het tabbladdeel getiteld **Vertrekken** zijn afkomstig uit de versie van de **Woningwaardering** die geldig is op de **Verhuurbaar-per-datum**. Elke regel onder **Vertrekken** komt overeen met een **Vertrek** of **Overige ruimte** die aanwezig is in de woningwaardering van de OG Eenheid en die is gerelateerd aan een **VERA-ruimtesoort**. Let op: dit betekent dat een vertrek dat, of overige ruimte die, in de woningwaardering *niet* is gerelateerd aan een VERA-ruimtesoort, ook *niet* wordt getoond in het tabblad **Vertrekken**. 
 12. Als de details onder kopje **Vertrekken** niet juist of volledig zijn, navigeer dan naar de **Woningwaardering** van de OG Eenheid, maak een nieuwe versie aan van de woningwaardering waarin u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de details automatisch zijn bijgewerkt. 
 13. De details op het tabbladdeel getiteld **Elementen** zijn afkomstig uit het **Aanbiedingscontract** van de **Verhuuraanbieding**.  Als de verhuuraanbieding meerdere aanbiedingscontracten heeft, dan worden de details overgenomen uit het aanbiedingscontract met een ingevulde en gefiatteerde huurprijsmutatie. Elke regel onder **Elementen** komt overeen met een **Aanbiedingselement** dat is toegewezen aan een **VERA-prijscomponent**. Let op: dit betekent dat een aanbiedingselement dat in de lijst met standaard elementen *niet* is toegewezen aan een VERA-prijscomponent, ook *niet* wordt getoond onder kopje **Elementen** op de pagina **Voorbereiden beschikbare eenheid**.
 14. Voor het tabbladdeel getiteld **Prijscomponenten** geldt het volgende: als een element met **VERA-prijscomponentsoort** *Service* is, bepaalt het systeem wat het **VERA-prijscomponentdetailsoort** van dat element is: *Subsidiabele servicekosten* of *Niet-subsidiabele servicekosten*. Als het VERA-prijscomponentdetailsoort van een element *Subsidiabele servicekosten* is, dan bepaalt het systeem bovendien welke **Servicekostengroep** van toepassing is: *Energiekosten*, *Schoonmaakkosten*, *Huismeesterkosten* of *Kapitaal/onderhoudskosten*. Het systeem bepaalt bovenstaande op basis van de inrichting die is vastgelegd op pagina **Rekenhuurparameters**. 
 15. Als de details onder kopje **Elementen** niet juist of volledig zijn, sluit dan de pagina, navigeer naar de **Verhuuraanbieding** met status *Lopende aanbieding*, selecteer het juiste **Aanbiedingscontract** en klik op **Aanbiedhuur**. Als een element een verkeerd bedrag bevat, pas dan de eenheidsprijs van dat element aan. Als een element ontbreekt, voeg dan het element toe aan het aanbiedingscontract. Sluit de pagina. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de details automatisch zijn bijgewerkt. 
 16. De details onder kopje **Prijscomponenten** zijn automatisch afgeleid van de details onder kopje **Elementen** op dit tabblad. Deze afleiding gaat als volgt: het systeem toont een regel onder **Prijscomponenten** voor elke combinatie van VERA-prijscomponentsoort en VERA-prijscomponentdetailsoort die voorkomt onder **Elementen**. Per combinatie van **VERA-prijscomponentsoort** en **VERA-prijscomponentdetailsoort** telt het systeem de bedragen van de desbetreffende elementen bij elkaar op. In het geval van **VERA-prijscomponentsoort** *Service* houdt het systeem rekening met het maximumbedrag van de desbetreffende servicekostengroep. Als het totaalbedrag van de elementen groter is dan het maximumbedrag, dan wordt het gedeelte boven dat maximumbedrag automatisch overgeheveld naar de prijscomponent van het detailsoort *Niet-subsidiabele servicekosten*. 
 17. Tabblad **OG Eenheidvoorwaarden** bevat een specificatie van de voorwaarden waaraan een kandidaat moet voldoen, wil hij in aanmerking komen voor het huren van de OG Eenheid. De standaardwaarden van deze gegevens zijn afkomstig uit de **WRV-eenheidvoorwaardenset** die betrekking heeft op de **VERA-doelgroep** van de OG Eenheid. Als er een afwijkende WRV-eenheidvoorwaardenset beschikbaar is voor de VERA-eenheiddetailsoort van de OG Eenheid, wordt deze afwijkende set gebruikt. U kunt voor elke beschikbare OG Eenheid de standaardwaarden wijzigen op de pagina **Voorbereiden beschikbare OG Eenheid**. 
 18. Tabblad **Publicatie** bevat details over de publicatie van de eenheid in het woonruimteverdeelsystseem. Een deel van de details is afkomstig van de pagina **OG Eenheidkaart**, tabblad **WRB**, en alleen op die pagina wijzigbaar. De waarde van het detail **Opleverdatum** is gelijk aan de waarde van het detail **Verhuurbaar per datum** (zie tabblad **Algemeen**). 
 19. Tabblad **Vorige huurder** bevat details over de vorige huurder van de OG Eenheid. De **Vertrekdatum** is gelijk aan de einddatum van het opgezegde huurcontract, dat wil zeggen: het contract dat via de huuropzegging is gekoppeld aan de verhuuraanbieding. U kunt deze datum wijzigen. De overige details zijn afkomstig van de klant die is gekoppeld aan het opgezegde huurcontract. Om precies te zijn betreft het de gegevens van de persoon die binnen het betreffende huishouden de rol ‘contractant’ heeft. Als er binnen het huishouden meerdere personen zijn met de rol ‘contractant’, worden de gegevens overgenomen van de persoon bij wie de indicatie ‘Toon als eerst’ van toepassing is. 
 Als u deze velden leeg maakt op deze pagina, worden de gegevens over de vorige huurder niet naar het extern woonruimteverdeelsysteem gestuurd. 
 21. Zodra u constateert dat alle details juist en volledig zijn, klikt u op **Berichten versturen** | **Versturen beschikbaarheidsbericht**.  Zodoende stuurt u een bericht met alle getoonde details naar het woonruimteverdeelstysteem dat is vermeld op tabblad **Algemeen**.  
 

## Publiceren eenheid 

In deze stap publiceert u daadwerkelijk de eenheid, zodat woningzoekende de eenheid kan vinden en kan reageren op de eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem.  

1. Login in het externe woonruimteverdeelsysteem 
2. Zoek de voorbereide eenheid op waarvan u de gegevens vanuit Dynamics Empire naar het woonruimteverdeelsysteem hebt gestuurd. 
3. Controleer de gegevens op juistheid en volledigheid. Als blijkt dat er nog gegevens uit Dynamics Empire ontbreken, ga dan terug naar de vorige stap **Voorbereiden publicatie**. 
4. Vul daar waar nodig de publicatie van de eenheid aan met extra gegevens, zoals foto's. 
5. Als alle gegevens juist en compleet zijn, publiceer dan de eenheid.  


## Verwerken reacties  

In deze stap verwerkt u de reacties van woningzoekenden op de gepubliceerde eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem. 


## Bepalen rangorde  

In deze stap bepaalt u de rangorde van de kandidaten die hebben gereageerd op de gepubliceerde eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ0MjU5MDU0LC01MDIzMzQwNTAsLTYwMj
IyMjU1NiwtMTMyNjMwNDc4MiwxMTYxNTU5NTU0LDEwODcxMTky
OTQsOTE2MjI0NDcxLDEzNTMyOTQ4NTQsMTcyMTU5Nzk3OCwyOT
I3MzAyODYsOTAzNzE3MTM3LC0zNTc1Nzc1MjldfQ==
-->