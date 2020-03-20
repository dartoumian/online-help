# Afsluiten betalingsregeling

In dit werkproces wordt de aanvraag van een betalingsregeling beoordeeld en indien mogelijk een betalingsregeling aangemaakt.

## Aanmaken betalingsregeling via sjabloon
U kunt de standaard betalingsregelingen aanmaken door het vullen van een betalingsregelingsjabloon. Betalingsregelingen met afwijkende termijnen of die niet binnen de voorwaarden van een sjabloon passen kunnen handmatig aangemaakt worden (zie **[Aanmaken betalingsregeling zonder sjabloon](#aanmaken-betalingsregeling-zonder-sjabloon)**).

 1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon de lijst **Klanten**.
 2. Selecteer de klant waarvoor u een betalingsregeling aan wilt maken en klik op **Betalingsregeling maken**. De pagina **Betalingsregelingwizard** opent. Vul de volgende velden: 
	-	**Sjablooncode**
	-	**Mandaatcode**: Dit is de mandaatcode voor automatische incasso. Heeft de klant nog geen mandaatcode, voer dan eerst de processtap **[Aanmaken nieuwe mandaatcode](#aanmaken-nieuwe-mandaatcode)** uit. 
	-	**Totaalbedrag Regeling**:
		-	Klik op de drie puntjes. et scherm **Betalingsregelingwizard** opent. 
		-	Selecteer de posten die u op wilt nemen in de betalingsregeling.
		-	Klik op **OK**.
	-	**Aantal termijn**: Geef het aantal termijnen voor de betalingsregeling op (het termijnbedrag wordt automatisch berekend).
	**OF**
	-	**Termijnbedrag**: Geef het bedrag per termijn op (het aantal termijnen wordt automatisch berekend.
 3. Klik op op **Termijnen aanmaken**. Er wordt een betalingsregeling aangemaakt. De betalingsregeling kan worden gecontroleerd (**[Controleren betalingsregeling](#controleren-betalingsregeling)**) en geactiveerd (**[Activeren betalingsregeling](#activeren-betalingsregeling)**). U keert terug naar de pagina **Klanten**.


## Aanmaken betalingsregeling zonder sjabloon
Wanneer u een betalingsregeling met afwijkende termijnen aan wilt maken, of wanneer u een betalingsregeling die niet binnen de sjabloonwaarde past aan wilt maken, kunt u dit zonder een sjabloon doen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken ico de lijst **Klanten**. 
2. Selecteer de klant waarvoor u een betalingsregeling aan wilt maken en klik op **Betalingsregeling** (*Meer opties - Acties - Nieuw document*). De gelijknamige pagina opent. Wanneer u op **Enter** drukt krijgt de betalingsregeling een nummer. 
3. Selecteer in het veld **Code transactiewijze** op tabblad **Facturering** de transactiewijze waarmee de betalingsregeling betaald moet worden. 
4. Wanneer de betalingsregeling automatisch geïncasseerd dient te worden, vul dan het veld **Mandaatcode** met de juiste code. Heeft de klant nog geen mandaatcode, maak deze dan aan via de processtap **[Aanmaken nieuwe mandaatcode](#aanmaken-nieuwe-mandaatcode)**.
5. Kies op pagina **Betalingsregeling** voor **Posten selecteren** (*Meer opties - Acties - Functies*). De pagina **Klantenposten** opent. Selecteer de klantenposten die opgenomen moeten worden in de betalingsregeling (met behulp van de Ctrl-toets) en klik op **OK**. U keert terug naar de pagina **Betalingsregeling**. Onder het kopje **Klantenposten** worden de opgenomen posten getoond.
6. Klik op **Termijnen aanmaken**. De pagina **Betalingsregelingtermijnvoorstel** opent. Vul de volgende velden:
	- **Datum eerste termijn**: De datum waarop de betalingsregeling ingaat. Dit is ook de datum waarop de eerste termijn betaald dient te worden. Gebruikelijk is om hier de eerste dag van de volgende maand in te vullen. 
	- **Betalingsconditie**: Met '0D' geeft u aan dat de betalingsregeling op de eerste van de maand betaald dient te worden.
	- **Frequentie**: Met '1M' geeft u aan dat er elke maand een termijn betaald dient te worden.
	- **Aantal termijnen**: Het aantal termijnen van de betalingsregeling. Het veld **Termijnbedrag** wordt automatisch berekend.
	- **Termijnbedrag**: Dit is automatisch gevuld o.b.v. de opgegeven waarde in het veld **Aantal termijnen**. U kunt het bedrag aanpassen. Het aantal termijnen zal opnieuw berekend worden o.b.v. het opgegeven bedrag. 
	- **Restbedrag**: Wanneer er een restbedrag overblijft geeft u hier aan met welke termijn het restbedrag verrekend moet worden.
7. Klik op **Termijnen aanmaken**. De termijnen worden aangemaakt. U keert terug naar de pagina **Betalingsregeling**. Onder het kopje **Termijnen** worden de aangemaakte termijnen getoond.
8.  U kunt in het veld **Te betalen** het te betalen bedrag per termijn opgeven.
>**Let op!** Wanneer u termijnen aanpast en het totaalbedrag van de termijnen is lager dan het totaalbedrag van de opgenomen posten, dan blijft een deel van de opgenomen posten openstaan.

## Aanmaken nieuwe mandaatcode

Wanneer u een betalingsregeling af wilt sluiten en u wilt de betalingsregelingstermijn automatisch incasseren, maar de klant heeft nog geen mandaat voor automatische incasso, voer dan de volgende stappen uit.

1. Klik op de betalingsregelingkaart op tabblad **Facturering** inet ld Mana atcode**; u krijgt nu de optie om op **Nieuw** te klikken in een popup-schermpje. Daarmee verschijnt het scherm **Selecteren - Mandaat incasso**.
2. Druk op **Enter**. Er wordt een nummer gevuld in het veld **Code**.
3. Vul de volgende velden:
	- **Reden incasso**
	- **Doorlopend**: 'an'
	- **Datum tekening**: Wordt automatisch gevuld met de datum van vandaag.
	- **Onze bankrekening**: Vul de bankrekening in vanaf waar geïncasseerd wordt. 
3. Klik op **OK**. Het mandaat wordt aangepast en wordt gevuld in het veld vanaf waar het nieuwe mandaat is aangemaakt. 

## Controleren betalingsregeling

Betalingsregelingen kunnen op verschillende wijzen aangemaakt zijn: via het Klantportaal, o.b.v. een betalingsregelingssjabloon of handmatig. Voordat u de betalingsregeling activeert kunt u de betalingsregeling nog controleren. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon naar el de lijst **Betalingsregelingoverzicht**.  De gelijknamige pagina opent.
2. Stel een filter in (via ![fFilter picon](/assets/image:/togram](https://docs.microsoft.com/nl-nl/dynamics365/business-central/media/ui-search/filter-icon.png " iconPictogram Filter") rechtsboven in het scherm, gevolgd door een klik op **+ Filteren...**) op het veld **Status**. Deze dient gelijk te zijn aan **Aangemaakt**. U heeft nu een overzicht van de nog niet geactiveerde betalingsregelingen. 
3. Klik op een regel om de desbetreffende betalingsregeling te openen. 
4. Controleer of de betalingsregeling correct is en geactiveerd kan worden. 
5. Wilt u de betalingsregeling aanpassen, kijk dan in de processtap **[Aanmaken betalingsregeling zonder sjabloon](#aanmaken-betalingsregeling-zonder-sjabloon)** hoe u de gegevens aan kunt passen.
6. Wilt u de betalingsregeling verwijderen, informeer de klant hier dan over en klik op **Verwijderen**. De betalingsregeling wordt verwijderd. U keert terug naar de pagina etalingsregelingoverzicht**.
7. Is de betalingsregeling akkoord, dan kunt u verder gaan naar de stap **[Activeren betalingsregeling](#activeren-betalingsregeling)**. 

## Activeren betalingsregeling
Wanneer u de betalingsregeling gecontroleerd heeft kunt u deze activeren. 

1. Vanaf de kaartpagina **Bbetalingsregeling** klikt u op **Activeren**. U krijgt een bevestigingsvraag die u met **Ja** beantwoordt. U keert terug naar het scherm **Betalingsregeling**. De status van de betalingsregeling is aangepast naar **Geactiveerd**. 
2. Klik op **Worddocument**, waarna het scherm **Word-sjablonen** opent. Selecteer het sjabloon voor een nieuwe betalingsregeling en klik op **OK**. 
3. U krijgt de vraag of u het document wilt downloaden en bewerken. Klik op **Nee**. Het scherm **Vragenlijst** opent, waar u in de kolom **Antwoord** de vragen op de antwoorden invoert. Klik daarna op **Sluiten**. 
4. Klik op **Word**. Het scherm voor aanmaken van een WordLinkbrief opent. Selecteer het sjabloon voor het bevestigen van een nieuwe betalingsregeling en vul de benodigde vragen in. 
5. Verstuur het document naar de klant. De betalingsregeling is nu geactiveerd en de klant is geïnformeerd.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMwNDE1MDMwMiw2NjUwMjQ5MDksMTU4Mj
YxNTY1OSwzODA2NTQyNzcsNjIzMDA1NzM5LC0xMzQxOTUyNDUy
LDE0NjE5NjY3MjYsNDg5MTI5ODEyLDgwNjg4OTAxOSwtMjA1MT
Q1ODYxNiwtNjkyNTQ4OTM4LDEwNDUwODkzNTIsMTQyNjg4OTUy
MSwtMTQyMDg1MDU3MSwtNTM4OTY2MTA3LDU1MDI2NTczMV19
-->