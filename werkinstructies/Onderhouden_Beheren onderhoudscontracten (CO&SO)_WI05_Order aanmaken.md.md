# Vastleggen inkooporder

## Omschrijving
Het vastleggen van inkooporders in Dynamics Empire kan door de inkoopofferte om te zetten naar een inkooporder of door het rechtstreek aanmaken van een inkooporder.

## Processchema (H2)
(Hier komt link naar Mavim of plaatje van proces.)

## Processtappen
### Rechtstreeks aanmaken inkooporders
Deze werkinstructie behandelt het rechtstreeks aanmaken van een inkooporder. Dit doet u wanneer de inkoopprijs op een andere wijze is verkregen dan via een inkoopofferte, bijvoorbeeld bij meer–minderwerk, met behulp van eenheidsprijzen of een contract. 
 1. Ga voor het vastleggen van inkoopoorders naar het **Projectoverzicht** en open met **Bewerken** in het lint het project van uw keuze.
 2. Dynamics Empire zal op de projectkaart openen. Deze projectkaart bestaat uit vier tabbladen (midden), feitenblokken (rechts) en een lint met knoppen (boven).
 3. Selecteer op tabblad **Budgetregels** de budgetregel(s) waarvoor u een order wilt aanmaken.
 4. Klik op de actie **Inkooporder aanmaken** (tabblad **Budgetregels > Functies - Inkoop - Inkooporder aanmaken** in het lint).
 5. Dynamics Empire vraagt uw bevestiging voor een inkoopoorder op de betreffende budgetregel, klik op **Ja**.
 6. U komt in een overzicht met leveranciers, waarin je de betreffende leverancier kunt opzoeken met het snelfilterveld en kunt selecteren voor de offerteaanvraag.
 7. Zoek en selecteer de gewenste leverancier en klik op **OK**. Dynamics Empire zal een offertekaart aanmaken die aan het project gekoppeld is.
 8. Klik op **OK** om de melding hiervan te sluiten.
 9. Bij een planmatigonderhoudsproject wordt de status van het project omgezet in 3 Order. De aangemaakte inkooporder is te vinden vanuit het feitenblok via item Werkderden. Het aantal in dit feitenblok is toegenomen en geeft het aantal inkoopregels weer die zijn aangemaakt vanuit het project.
 10. Klik op het aantal in feitenblok Budgetgegevens (als het een VGO-project betreft) of feitenblok projectgegevens (als het een Onderhoudsproject betreft) om de inkooporder te openen.
 11. U komt daarmee in een overzicht genaamd **Werkderdenoverzicht**. Dit overzicht toont alle inkoopstukken die zijn aangemaakt vanuit het project en de budgetregel. Een inkooporder kan uit meerdere inkoopregels bestaan. De regels worden afzonderlijk weergegeven omdat de status van beide regels op enig moment kan verschillen. Eén regel kan gegund zijn, terwijl de andere regel is gereed gemeld. Door beide regels te tonen heb je overzicht over de status van de regels.
 
 *Tip!*
*Mocht u een order hebben aangemaakt voor een verkeerde leverancier, dan kunt u als volgt deze inkooporder verwijderen:*
	*- Selecteer één van de orderregels in het **Werkderdenoverzicht** en klik op **Kaart** in het lint.*
	*-Druk vervolgens op prullenbak-icoon midden bovenaan de inkooporderkaart.*
	*- Als een deel van de inkooporder al gefactureerd is, kan de order niet worden verwijderd. Klik dan op Inkooporder afhandelen	(tabblad **Algemeen**, veld **Status** naar **Afgehandeld**)*  
 
 12. U gaat nu de orderkaart invullen met relevante gegevens. Selecteer één van de orderregels in het **Werkderdenoverzicht** en klik op **Kaart** om de orderkaart te openen.
 13. Vul in de inkooporderregels de **Directe kostprijs** als orderbedragen excl. BTW.
 14. Als de order aangemaakt is vanuit een offerte, dan zijn de directe kostprijzen reeds ingevuld. Pas eventueel de Directe kostprijs aan als u onderhandeld heeft over de offerteprijs.
 15. Als het ingevulde bedrag Directe kostprijs excl. BTW hoger is dan het budgetbedrag excl. BTW zal Dynamic Empire hiervan   melding doen: "het budget ........wordt € xx,xx overschreden". Tevens kleurt de orderregel rood.
 16. Inkooporderregels kunnen opgesplitst worden ten behoeve van termijnen. Dit moet echter binnen de structuur van de aanwezige orderregels, rekening houdend met de volgorde waarin de werkzaamheden worden uitgevoerd.
 17. Kies binnen het tabblad **Regels** inkooporderregel(s) die u wilt opdelen in termijnen door in het lint van het tabblad naar **Regel -  Termijnen toevoegen** te gaan.
 18. Het scherm Termijnen toevoegen wordt geopend.
 19. Om met 2 termijnen te werken vult u bij **Extra aantal termijnen** de waarde 1 in.  
 20. De inkooporderregel zal gesplitst worden.
 21. Pas het veld **Directe kostprijs** aan als de termijnen niet evenredig zijn. Let op! Dynamics Empire rekent het aanpassen van de directe kostprijs niet door naar andere regels. Bedenk dus, voordat je deze handeling gaat doen, wat het bedrag per termijn zal zijn. Mocht de inkooporder uit meer regels bestaan die je wilt opdelen t.b.v. termijnen, selecteer dan alle regels.
 22. Voer in kolom **Omschrijving 2** een omschrijving in van de termijnen.
 23. Voer een verwachte factuurdatum per termijn op in kolom **Verwachte factuurdatum**. 
### Inkoopofferte omzetten in order
 1. Ga voor het omzetten van een inkoopofferte naar een  inkoopoorders naar het **Projectoverzicht** en open met **Bewerken** in het lint het project van uw keuze.
 2. Dynamics Empire zal op de projectkaart openen. Deze projectkaart bestaat uit vier tabbladen (midden), feitenblokken (rechts) en een lint met knoppen (boven).
 3. Klik in het feitenblok projectgegevens op het item **Werkderden**. U komt hiermee in het Werkderdenoverzicht.
 4. Selecteer in het Werkderdenoverzicht de inkoopofferte die u wilt omzetten en klik in het lint op **Kaart** om de offertekaart te openen.
 5. Klik via het lint op **Verwerken - Order maken**.
 6. Dynamics Empire vraagt of u de offerte wilt omzetten. Klik hier op **Ja**.
 7. Sluit de offertekaart. U komt hiermee terug in het Werkderdenoverzicht. In dit overzicht zijn nieuwe regels te zien met regelsoort = Order . Tevens is te zien dat de status van de offerte is veranderd in Omgezet. De offerte is gearchiveerd in Dynamics Empire en niet meer te wijzigen. De inkooporder heeft status = Open.
 8. Sluit het werkderdenoverzicht. U komt hiermee terug in het projectoverzicht (of op de projectkaart). Hier is te zien dat de status van het project is veranderd in 3 Order.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5Nzc0Njk0OF19
-->