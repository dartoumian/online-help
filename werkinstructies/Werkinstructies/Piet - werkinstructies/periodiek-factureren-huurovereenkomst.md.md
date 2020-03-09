# Periodiek factureren huurovereenkomst

In dit detailproces word de periodieke huur gefactureerd, ook wel **Prolongeren** genoemd.

## Processchema

## Controleren huurmutaties

Voordat u de huurovereenkomst gaat factureren kunt u de huurprijsmutaties die van invloed zijn op de te factureren periode controleren. U kunt bijvoorbeeld bepalen of er geen uitzonderlijke mutaties plaatsgevonden hebben, of u kunt controleren of alle mutaties geaccordeerd zijn.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Verwachte mutaties in de te prolongeren maand**. 
2. De gelijknamige pagina opent. Vul hier de volgende waarden in:
	* **Periode:** Dit betreft de te factureren maand.
	* **Clusternr.:** (leeg laten)
	* **Elementnr.:** (leeg laten)
	* **Toon afwijkingsredenen verhuurmutatie:** 'Aan'.
	* **Elementen:** 'Uit'.
	* **Cluster - elementen:** 'Uit'.
	* **Eenheid - elementen:** 'Aan'.
3. Klik op de knop **Voorbeeld** om een voorbeeld van het rapport te openen of klik op de knop **Verzenden** en selecteer vervolgens **Excel** om het rapport in Excel te openen.
4. In het rapport dat opent vindt u de volgende zaken:
	* de datum van de wijziging;
	* de gewijzigde huurelementen;
	* de oude en nieuwe bedragen per huurelement;
	* de datum waarop de wijziging opgevoerd is;
	* wat de reden voor wijziging is;
	* door wie en wanneer de wijziging geaccordeerd is;
	* of er afwijkende verhuurmutatieredenen zijn en wie deze heeft ingevoerd.
5. Zijn er naar aanleiding van de controle zaken die aangepast dienen te worden, ga dan verder naar de processtap **[Uitvoeren huurprijsaanpassingen](#uitvoeren-huurprijsaanpassingen)**.
6. Blijkt naar aanleiding van de controle dat alle huurprijsmutaties akkoord zijn, ga dan verder naar de processtap **[Instellen te factureren contracten voorgaande periode](#instellen-te-factureren-contracten-voorgaande-periode)**.

## Uitvoeren huurprijsaanpassingen

Heeft u in de voorgaande stap mutaties gevonden die gecorrigeerd dienen te worden, dan vindt u in het onderstaand vermelde detailproces hoe u deze aanpassingen doorvoert.

(LINK NAAR DETAILPROCES UITVOEREN HUURMUTATIES)

## Instellen te factureren contracten voorgaande periode

Voordat u de huur voor de komende periode (maand) gaat prolongeren, dient u eerst de huurprijsmutaties die betrekking hebben op de voorgaande periode, maar die nog niet gefactureerd zijn, te factureren.  In deze zogenaamde 'veegprolongatie' kunnen nog niet gefactureerde TWK (terugwerkendekracht)- mutaties naar voren komen. U  factureert de mutaties die betrekking hebben op de voorgaande periode eerst om ervoor te zorgen dat voor de komende periode (maand) alleen de huur voor de komende periode (maand) in rekening wordt gebracht. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Prolongatierunoverzicht**.
2. De gelijknamige pagina **Prolongatierunoverzicht** opent; klik op **Nieuw**.
3. De kaartpagina **Prol.-run kaart** opent. Vul op deze pagina de volgende velden:
	* **Prol. periodenaam:** De laatst gefactureerde maand (de te factureren maand -1). De velden **Boekingsdatum** en **Documentdatum** worden automatisch gevuld.
	* **Alleen controleren:** 'Uit'.
	* **Erfpacht:** 'Uit'.
	* **Huur:** 'Aan'.
	* **Direct boeken:** 'Uit'.
4. Ga verder naar de processtap **[Genereren facturen](#genereren-facturen)**.

## Genereren facturen

Nadat u in de voorgaande stap aangegeven heeft welke periode gefactureerd dient te worden, kunnen de facturen gegenereerd worden. 

1. Klik op de pagina **Prol.-run kaart** op actie/functie **Uitvoeren/boeken**. De facturen worden gegenereerd, maar nog niet geboekt.
2. Nadat de facturen gegenereerd zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (kolom **Boekingsstatus** in de prolongatieregels) de status getoond.
	* Wanneer de status op de prolongatiekaart gelijk is aan 'Prol gereed' zijn alle facturen zonder problemen aangemaakt. U kunt verder naar processtap **[Boeken facturen](#boeken-facturen)**. Als de status op de prolongatiekaart niet gelijk is aan 'Prol gereed', dan zijn er één of meerdere facturen die niet juist aangemaakt zijn. Ga in dit geval verder naar processtap **[Controleren en oplossen fouten bij facturatie](#controleren-en-oplossen-fouten-bij-facturatie)**.

## Controleren en oplossen fouten bij facturatie

Wanneer er tijdens het genereren van de facturen fouten zijn ontstaan dient u deze te controleren en te corrigeren. 

1. Navigeer op de pagina **Prol.-run kaart** naar **Alle fouten**. De pagina **Fouten bij prolongation** opent. 
2. In dit scherm ziet u de foutmelding en bij elke eenheid en contractregel of klant het probleem dat zich voordoet. 
3. U dient deze fouten op te lossen. 
4. Wanneer dit is gebeurd klikt u op de pagina **Prol.-run kaart** opnieuw op **Uitvoeren/boeken**. De facturen die fouten veroorzaakten worden opnieuw gegenereerd.
5. Nadat de facturen gegenereerd zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (kolom **Boekingsstatus** in de prolongatieregels) de status getoond. 
	* Als de status op de prolongatiekaart gelijk is aan **Prol gereed** zijn alle facturen zonder problemen aangemaakt. U kunt verder naar processtap **[Boeken facturen](#boeken-facturen)**.
	* Als de status op de prolongatiekaart *niet** gelijk is aan **Prol gereed** zijn er één of meerdere facturen die niet juist aangemaakt zijn. Voer in dit geval opnieuw de processtap **[Controleren en oplossen fouten bij facturatie](#controleren-en-oplossen-fouten-bij-facturatie)** uit. 

## Boeken facturen

Wanneer er tijdens het genereren van de facturen geen fouten zijn ontstaan kunt u de gegenereerde facturen boeken.  

1. Klik op de pagina **Prol.-run kaart** op **Uitvoeren/boeken**. De facturen worden geboekt. 
2. Nadat de facturen geboekt zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (Kolom **Boekingsstatus** in de prolongatieregels) de status getoond. 
	* Als de status op de prolongatiekaart gelijk is aan **Boeken gereed** zijn alle facturen zonder problemen geboekt. 
	*  Als de prolongatie die u geboekt heeft de prolongatie voor de *voorgaande periode* was, ga dan verder bij de processtap **[Instellen te factureren contracten komende periode](#instellen-te-factureren-contracten-komende-periode)**. 
	* Als de prolongatie die u geboekt heeft de prolongatie voor de *komende periode* was, ga dan verder bij processtap **[Verzenden facturen](#verzenden-facturen)**.
	* Als de status op de prolongatie kaart *niet* gelijk is aan **Boeken gereed** zijn er één of meerdere facturen die niet zijn geboekt. Ga in dit geval verder naar processtap **[Controleren en oplossen fouten bij boeken](#controleren-en-oplossen-fouten-bij-boeken)**.

## Controleren en oplossen fouten bij boeken

Wanneer er tijdens het boeken van de facturen fouten zijn ontstaan dient u deze te controleren en te corrigeren. 

1. Klik op de pagina **Prol.-run kaart** op **Alle fouten**. De pagina **Fouten bij prolongatie** opent.
2. In dit scherm ziet u de foutmelding en bij elke eenheid en contractregel of klant het probleem dat zich voordoet.
3. U dient deze fouten op te lossen.
4. Wanneer dit is gebeurd klikt u op de pagina **Prol.-run kaart** opnieuw op **Uitvoeren/boeken**. Er wordt  geprobeerd om de facturen die fouten veroorzaakten te boeken.
5. Nadat de facturen geboekt zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (kolom **Boekingsstatus** in de prolongatieregels) de status getoond. 
	* Als de status op de prolongatiekaart gelijk is aan **Boeken gereed** zijn alle facturen zonder problemen geboekt. 
	*  Als de prolongatie die u geboekt heeft de prolongatie voor de *voorgaande periode* was, ga dan verder bij de processtap **[Instellen te factureren contracten komende periode](#instellen-te-factureren-contracten-komende-periode)**. 
		*  Als de prolongatie die u geboekt heeft de prolongatie voor de *komende periode* was, ga dan verder bij processtap **[Verzenden facturen](#verzenden-facturen)**.
	*  Als de status op de prolongatiekaart *niet* gelijk is aan **Boeken gereed** zijn er één of meerdere facturen die niet zijn geboekt. Voer in dit geval opnieuw de processtap **[Controleren en oplossen fouten bij boeken](#controleren-en-oplossen-fouten-bij-boeken)** uit. 

## Instellen te factureren contracten komende periode

Wanneer u de facturen voor de voorgaande periode verwerkt hebt kunt u de prolongatierun voor de komende periode instellen. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **prolongatierunoverzicht**.
2. De pagina **Prolongatierunoverzicht** opent. Klik op **Nieuw**.
3. De pagina **Prol.-run kaart** opent. Vul op deze pagina de volgende velden:
	* **Prol. periodenaam:** De te facture maand. De velden **Boekingsdatum** en **Documentdatum** worden automatisch gevuld.
	* **Alleen controleren:** Uit.
	* **Erfpacht:** Uit.
	* **Huur:** Aan.
	* **Direct boeken:** 'Nee'.
4. Ga verder naar de processtap **[Genereren facturen](#genereren-facturen)**.

## Verzenden facturen

Wanneer u de facturen voor de komende periode geboekt heeft kunt u wanneer van toepassing de facturen en digitale betaalverzoeken versturen. 

1. Klik op de pagina **Prol.-run kaart** op **Postex**. De pagina **Prolongatiefactuur PROL+** opent. 
2. Klik op **OK**. Voor de klanten waarvoor u heeft ingesteld dat zij een factuur of betaalverzoek moeten krijgen, wordt via Postex het betaalverzoek of de factuur verstuurd. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MTI4NzMzMTEsLTEwNzU3NjgyODIsLT
EzMDYyMTI0MCw3NjQ3MzE1OSwxNDUzODgzMjU4LDE4NjIxNTA5
MTAsLTIxMDY4OTk5NTksLTEzODIxMzUyNTIsLTE4MTMzMjEyNz
ksLTE0MDk1MjIyLDEwMzAxMjM0NDUsMTg2MDY3NTk3NCw0NTM5
MTcwMDgsMTQ2MjM3MjY4NywxNzc2NjAzODg4LDE2NjUwMzYyNS
w3ODU0NjI1MTksLTE4NjkzNTM0MTddfQ==
-->