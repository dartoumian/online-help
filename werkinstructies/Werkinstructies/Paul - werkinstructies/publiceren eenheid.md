# Publiceren eenheid

De beschikbare eenheid wordt gepubliceerd, zodat woningzoekenden kunnen reageren op de eenheid. Hierbij wordt ervan uitgegaan dat de eenheid via de standaard VERA-WRV-koppeling wordt gepubliceerd in een extern woonruimteverdeelsysteem, zoals WoningNet of ZIG. 
Het publiceren gaat in twee stappen: voorbereiden publicatie in Dynamics Empire en daadwerkelijk publiceren van de eenheid in het woonruimteverdeelsysteem. Nadat de publicatie is gesloten, worden de reacties van de woningzoekenden verwerkt en wordt de rangorde van de kandidaten bepaald in het woonruimteverdeelsysteem.  


## Voorbereiden publicatie   

In deze stap bereid u de publicatie van de beschikbare eenheid voor. Deze voorbereidende stap vindt plaats in Dynamics Empire. Daarbij verzamelt u alle details over de eenheid, de publicatie en de huurprijs waarvoor de eenheid wordt gepubliceerd. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Verhuurmutatieoverzicht**.
2. Zoek de verhuurmutatie op waarvan de publicatie moet worden voorbereid.
3. Open de detailpagina van de verhuurmutatie door op het nummer te klikken. 
4. Klik op **Navigeren** | **Beschikbare OG Eenheid**.  Een pagina verschijnt waarop alle details van de beschikbare OG Eenheid worden verzameld die naar het externe woonruimteverdeelsysteem worden verstuurd.  Mocht u in plaats daarvan een foutmelding krijgen, kies dan eerst voor **Verhuuraanbieding** en klik daarna op **Voorbereiden beschikbare OG Eenheid**.  Dan verschijnt de genoemde pagina alsnog.  In tabblad **Algemeen** wordt in veld **WRV-systeem** het woonruimteverdeelsysteem getoond waarin de beschikbare eenheid zal worden gepubliceerd. Het systeem selecteert het WRV-systeem automatisch aan de hand van de **Divisie** van de OG Eenheid. 
5. Controleer de details in het tabblad **Adres** van de beschikbare eenheid. Als deze details niet juist of volledig zijn, klik dan op **Navigeren** en **OG Eenheid**. De onroerend goed eenheidkaart wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt. 
56. Klik op **Voorbereiden beschikbare OG Eenheid**. Een pagina verschijnt waarop alleControleer de details in tabblad **OG-Eenheid-eigenschappen**. Dit tabblad bevat enkelvoudige en meervoudige VERA-eigenschappen. 
7. **Enkelvoudige VERA-eigenschappen** zijn eigenschappen waarbij elke OG Eenheid maximum 1 waarde kan hebben. Dit betreft de details **VERA-eenheidssoort** t/m  **VERA-energergielabel**.  Als deze enkelvoudige VERA-eigenschappen niet juist of volledig zijn, klik dan op **Navigeren** en **OG Eenheid**. De onroerend goed eenheidkaart wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt. 
8. **Meervoudige VERA-eigenschappen** zijn eigenschappen waarbij elke OG Eenheid 0, 1 of meer waarden kan hebben. Dit betreft de details **VERA-toegankelijksheidslabel** t/m  **VERA-eenheidenergievoorziening**.  Als deze meervoudige VERA-eigenschappen niet juist of volledig zijn, klik dan op **Navigeren** en **VERA-eigenschappen**. De pagina met meervoudige VERA-eigenschappen wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, worden verzameld die naar het externe woonruimteverdeelsysteem worden verstuurd. 
6. Controleer de details in hhet adres van de beschikbare eenheid. Als het adres niet juist of volledig is, klik dan op **Navigeren** en **OG Eenheid**. De onroerend goed eenheidkaart wordt geopend waarop u het adres kan aanpassen of aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt. 
7. Controleer de OG-Eenheid-eigenschappenaarop de details automatisch zijn bijgewerkt. 
9. De details in het tabblad **Vertrekken** zijn afkomstig uit de versie van de **Woningwaardering** die geldig is op de **Verhuurbaar-per-datum**. Elke regel in dit tabblad komt overeen met een **Vertrek** of **Overige ruimte** die aanwezig is in de woningwaardering van de OG Eenheid en die is gerelateerd aan een **VERA-ruimtesoort**. Let op: dit betekent dat een vertrek of overige ruimte die in de woningwaardering *niet* is gerelateerd aan een VERA-ruimtesoort, ook *niet* wordt getoond in het tabblad **Vertrekken**. 
10. Als de details in tabblad **Vertrekken** niet juist of volledig zijn, navigeer dan naar de **Woningwaardering** van de OG Eenheid, maak een nieuwe versie aan van de woningwaardering waarin u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de details automatisch zijn bijgewerkt. 
11. De details in het tabblad **Elementen** zijn afkomstig uit het **Aanbiedingscontract** van de **Verhuuraanbieding**.  Als de verhuuraanbieding meerdere aanbiedingscontracten heeft, dan worden de details overgenomen uit het aanbiedingscontract met een ingevulde en gefiatteerde huurprijsmutatie. Elke regel in dit tabblad komt overeen met een **Aanbiedingselement** dat is toegewezen aan een **VERA-prijscomponent**. Let op: dit betekent dat een aanbiedingselement die in de lijst met standaard elementen *niet* is toegewezen aan een VERA-prijscomponent, ook *niet* wordt getoond in het tabblad **Elementen** op de pagina **Voorbereiden beschikbare eenheid**.
12. In het geval van een element met **VERA-prijscomponentsoort** *Service* bepaalt het systeem wat het **VERA-prijscomponentdetailsoort** van dat element is: *Subsidiabele servicekosten* of *Niet-subsidiabele servicekosten*. In het geval het VERA-prijscomponentdetailsoort van een element *Subsidiabele servicekosten* is, dan bepaalt het systeem bovendien welke **Servicekostengroep** van toepassing is: *Energiekosten*, *Schoonmaakkosten*, *Huismeesterkosten* of *Kapitaal/onderhoudskosten*. Het systeem bepaalt bovenstaande op basis van de inrichting die is vastgelegd op pagina **Rekenhuurparameters**. 
13. Als de details in tabblad **Elementen** niet juist of volledig zijn, sluit de pagina, navigeer naar de **Verhuuraanbieding** met status *Lopende aanbieding*, selecteer het juiste **Aanbiedingscontract** en klik op **Aanbiedhuur**. Als een element een verkeerd bedrag bevat, pas dan de eenheidsprijs van dat element aan. Als een element ontbreekt, voeg dan het element toe aan het aanbiedingscontract. Sluit de pagina. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de details automatisch zijn bijgewerkt. 
14. De details in tabblad **Prijscomponenten** zijn automatisch afgeleid van de details in tabblad **Elementen**. Deze afleiding gaat als volgt: Het systeem toont een regel in tabblad **Prijscomponenten** voor elke combinatie van VERA-prijscomponentsoort en VERA-prijscomponentdetailsoort die voorkomt in tabblad **Elementen**. Per combinatie van **VERA-prijscomponentsoort** en **VERA-prijscomponentdetailsoort** telt het systeem de bedragen van de desbetreffende elementen bij elkaar op. In het geval van **VERA-prijscomponentsoort** *Service* houdt het systeem rekening met het maximumbedrag van de desbetreffende servicekostengroep. Als het totaalbedrag van de elementen groter is dan het maximumbedrag, dan wordt het gedeelte boven dat maximumbedrag automatisch overgeheveld naar de prijscomponent van het detailsoort *Niet-subsidiabele servicekosten*. 
15. Tabblad **OG Eenheidsvoorwaarden** bevat een specificatie van de voorwaarden waaraan een kandidaat moet voldoen, wil hij in aanmerking komen voor het huren van de OG Eenheid. De standaardwaarden van deze gegevens zijn afkomstig uit de **WRV-eenheidvoorwaardenset** die betrekking heeft op de **VERA-doelgroep** van de OG Eenheid. Als er een afwijkende WRV-eenheidsvoorwaardenset beschikbaar is voor de VERA-eenheiddetailsoort van de OG Eenheid, wordt deze afwijkende set gebruikt. U kunt voor elke beschikbare OG Eenheid de standaardwaarden wijzigen op de pagina **Voorbereiden beschikbare OG Eenheid**. 
16. Tabblad **Publicatie** bevat details over de publicatie van de eenheid in het woonruimteverdeelsystseem. Een deel van de details is afkomstig van de pagina **OG Eenheidkaart**, tabblad **WRB**, en alleen op die pagina wijzigbaar. De waarde van het detail **Opleverdatum** is gelijk aan de waarde van het detail **Verhuurbaar per datum** (zie tabblad **Algemeen**). 
17. Tabblad **Vorige huurder** bevat details over de vorige huurder van de OG Eenheid. De **Vertrekdatum** is gelijk aan de einddatum van het opgezegde huurcontract, dat wil zeggen het contract dat via de huuropzegging is gekoppeld aan de verhuuraanbieding. U kunt deze datum wijzigen. De overige details zijn afkomstig van de klant die is gekoppeld aan het opgezegde huurcontract. Om precies te zijn betreft het de gegevens van de persoon die binnen het betreffende huishouden de rol ‘contractant’ heeft. Als er binnen het huishouden meerdere personen zijn met de rol ‘contractant’, worden de gegevens overgenomen van de persoon bij wie de indicatie ‘Toon als eerst’ van toepassing is. Ook deze overige details kunt u wijzigen.  op de pagina **Voorbereiden beschikbare OG Eenheid**. Als u deze velden leeg maakt op deze pagina, worden de gegevens over de vorige huurder niet naar het extern woonruimteverdeelsysteem gestuurd. 
18. Zodra u constateert dat alle details juist en volledig zijn, klikt u op **Berichten sturen** en **Versturen beschikbaarheidsbericht**.  Zodoende stuurt u een bericht met alle getoonde details naar het woonruimteverdeelstysteem dat is vermeld in tabblad **Algemeen**.  
 

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
eyJoaXN0b3J5IjpbNDg2ODQ4ODE2LDE5NTExMzQ4NywtMTIxMz
Q4MDg2OCwxMjI0MDc5MDg5LC0xODY1NTAyOTE4LC0zMTMzNjE1
MjYsMTgyNDY4MTcwMSw4ODg0NzA4OTgsLTk5MzMzMzY0MSwtMT
I3MTY4NDAxLDEzMTIxMjYzMiwtMTY0NjczNjM1NCwtMjk2MjIy
NDU2LDQxNTY3NjczMiwzNzY1NzU3MjAsLTE3MTYzMDkwMDksMT
E3NjAxMjAzNywtNzkzNjc1ODIzLC01MjY5MTg1NzksMTczMDI1
MjQ1OF19
-->