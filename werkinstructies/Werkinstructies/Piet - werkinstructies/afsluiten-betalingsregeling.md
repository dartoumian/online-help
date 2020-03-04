# Afsluiten betalingsregeling

In dit werkproces wordt de aanvraag van een betalingsregeling beoordeeld en indien mogelijk een betalingsregeling aangemaakt.

## Processchema

## Aanmaken betalingsregeling via sjabloon
U kunt de standaard betalingsregelingen aanmaken door het vullen van een betalingsregelingsjabloon. Betalingsregelingen met afwijkende termijnen of die niet binnen de voorwaarden van een sjabloon passen kunnen handmatig aangemaakt worden **[Aanmaken betalingsregeling zonder sjabloon](#aanmaken-betalingsregeling-zonder-sjabloon)**. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Klanten**. 
2. Selecteer de klant waarvoor u een betalingsregeling aan wilt maken en klik op **Betalingsregeling maken**. De pagina **Betalingsregelingwizzard** opent. Vul de volgende velden: 
	-	**Sjablooncode**: Selecteer het sjabloon wat u wilt gebruiken
	-	**Mandaatcode**: Selecteer de mandaatcode voor automatische incasso. Heeft de klant nog geen mandaatcode voer dan eerst de processtap **[Aanmaken nieuwe mandaatcode](#aanmaken-nieuwe-mandaatcode)** uit. 
	-	**Totaalbedrag Regeling**:
		-	Kik op de drie puntjes. Het scherm **Betalingsregelingwizzard** opent. 
		-	Selecteer de posten die u op wilt nemen in de betalingsregeling
		-	Klik op **OK**
	-	**Aantal termijn**: Geef het aantal termijnen voor de betalingsregeling op (het termijnbedrag wordt automatisch berekend
	**OF**
	-	**Termijnbedrag**: Geef het bedrag per termijn op (het aantal termijnen wordt automatisch berekend
2. Klik op **Termijnen aanmaken**. Er wordt een betalingsregeling aangemaakt. De betalingsregeling kan gecontroleerd (**[Controleren betalingsregeling](#controleren-betalingsregeling)**) en geactiveerd (**[Activeren betalingsregeling](#activeren-betalingsregeling)**) worden. U keer terug naar de pagina **Klanten.**


## Aanmaken betalingsregeling zonder sjabloon
Wanneer u een betalingsregeling met afwijkende termijnen aan wilt maken of wanneer u een betalingsregeling die niet binnen de sjabloonwaarde past aan wilt maken kunt u zonder een sjabloon en betalingsregeling aanmaken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Klanten**. 
2. Selecteer de klant waarvoor u een betalingsregeling aan wilt maken en klik op **Betalingsregeling**. De pagina **Betalingsregeling** opent. Wanneer u op Enter klikt krijgt de betalingsregeling een nummer. 
3. Selecteer in het veld **Code transactiewijze** de transactiewijze in waarmee de betalingsregeling betaald moet worden. 
4. Wanneer de betalingsregeling automatisch geïncasseerd dient te worden geef dan in het veld **Mandaatcode** de mandaatcode die gebruikt dient te worden op. Heeft de klant nog een mandaatcode maak deze dan aan via de processtap **[Aanmaken nieuwe mandaatcode](#aanmaken-nieuwe-mandaatcode)**.
5. Klik in pagina**Betalingsregeling** op **Posten selecteren**. De pagina **Klantposten** opent. Selecteer de klantposten die opgenomen moeten worden in de betalingsregeling en klik op **OK**. U keert terug naar de pagina **Betalingsregeling**. Onder het kopje **Klantposten** worden de opgenomen posten getoont. 
6. Klik op **Termijnen aanmaken**. De pagina **Betalingsregelingtermijnvoorstel** opent. Vul de volgende velden:
	- **Datum eerste termijn**: De datum waarop de betalingsregeling in gaat. Dit is ook de datum waarop de eerste termijn betaald dient te worden. Gebruikelijk is om hier de eerste dag van de volgende maand in te vullen. 
	- **Betalingsconditie**: 0D, hiermee geeft u aan dat de betalingsregeling op de eerste van de maand betaald dient te worden.
	- **Frequentie**: 1M. Dit betekend dat er elke maand een termijn betaald dient te worden. 
	- **Aantal termijnen**: Het aantal termijn van de betalingsregeling. Het veld **Termijnbedrag** wordt automatisch berekend. 
	- **Termijnbedrag**. Is automatisch gevuld o.b.v. de opgegeven waarde in het veld **Aantal termijnen**. U kunt het bedrag aanpassen. Het aantal termijnen zal opnieuw berekend worden o.b.v. het opgegeven bedrag. 
	- **Restbedrag**: Wanneer er een restbedrag overblijft geeft u hier aan met welke termijn het restbedrag verrekend moet worden. 
7. Klik op **Termijnen aanmaken**. De termijnen worden aangemaakt. U keert terug naar de pagina **Betalingsregeling**. Onder het kopje **Termijnen** worden de aangemaakte termijnen getoont.
8.  U kunt in het veld **Te betalen** het te betalen bedrag per termijn opgeven. Let op! Wanneer u termijnen aanpast en het totaal bedrag van de termijnen is lager dan het totaalbedrag van de opgenomen posten dan blijft een deel van de opgenomen posten open staan. 

## Aanmaken nieuwe mandaatcode

Wanneer u een betalingsregeling af wilt sluiten en u wilt de betalingsregelingstermijn automatisch incasseren maar heeft de klant nog geen mandaat voor automatische incasso volg dan de volden stappen uit.

1. Klik in veld waar u een mandaat moet selecteren op de knop **Nieuw**. Het scherm **Mandaat incasso** opent. 
2. Klik op enter. Er wordt een nummer gevuld in het veld **Code**
3. Vul de volgende velden:
	- **Rede incasso**: Selecteer een incasso rede
	- **Doorlopend**: Ja
	- **Datum tekening**: Wordt automatisch gevuld met de datum van vandaag
	- **Onze bankrekening**: Vul de bankrekening in vanaf waar geïncasseerd wordt. 
3. Klik op **OK**. Het mandaat wordt aangepast en wordt gevuld in het veld vanaf waar u het nieuwe mandaat aangemaakt is. 


## Controleren betalingsregeling

Betalingsregelingen kunnen op verschillende wijze aangemaakt zijn (via klantportaal, o.b.v. betalingsregeling sjabloon of handmatig). Voordat u de betalingsregeling activeert kunt u de betalingsregeling nog controleren. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Betalingsregelingoverzicht**.  De pagina **Betalingsregelingoverzicht** opent. 
2. Stel een filter in op het veld **Status**. De status dient gelijk te zijn aan **Aangemaakt**. U heeft nu een overzicht van de nog niet geactiveerde betalingsregelingen. 
3. Klik op een regel om de desbetreffende betalingsregeling te openen. 
4. Controleer of de betalingsregeling correct is en geactiveerd kan worden. 
5. Wilt u de betalingsregeling aanpassen kijk in de processtap **[Aanmaken betalingsregeling zonder sjabloon](#aanmaken-betalingsregeling-zonder-sjabloon)** hoe u de gegevens aan kunt passen.
6. Wilt u de betalingsregeling verwijderen informeer de klant hier over en klik op **Verwijderen**. De betalingsregeling wordt verwijderd. U keert terug naar de pagina **Betalingsregelingoverzicht**.
7. Is de betalingsregeling akkoord dan kunt u verder gaan naar de stap **[Activeren betalingsregeling](#activeren-betalingsregeling)**. 

## Activeren betalingsregeling
Wanneer u de betalingsregeling gecontroleerd heeft kunt u de betalingsregeling activeren. 

1. Vanaf de pagina betalingsregeling klikt u op **Activeren**. U krijgt een bevestigingsvraag die u met Ja beantwoord. U keer terug naar het scherm **Betalingsregeling**. De status van de betalingsregeling is aangepast naar **Geactiveerd**. 
2. Klik op Worddocument. Het scherm **Word-sjablonen** opent. Selecteer het sjabloon voor een nieuwe betalingsregeling en klik op **OK**. 
3. U krijgt een vraag op u het document wilt downloaden en bewerken. Klik op **Nee**. Het scherm **Vragenlijst** opent. Vul in de kolom **Antwoord** de vragen op de antwoorden in en klik op **Sluiten**. 
4. Klik op **Word**. Het scherm voor aanmaken van een WordLink brief open. Selecteer het sjabloon voor het bevestigen van een nieuwe betalingsregeling en vul de benodigde vragen is. 
5. Verstuur het document naar de klant. De betalingsregeling is nu geactiveerd en de klant is geïnformeerd. 



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUzODk2NjEwNyw1NTAyNjU3MzFdfQ==
-->