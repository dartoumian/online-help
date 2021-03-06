# Periodiek factureren huurovereenkomst

In dit detailproces word de periodieke huur gefactureerd, ook wel **Prolongeren** genoemd.

## Controleren huurmutaties

Voordat u de huurovereenkomst gaat factureren kunt u de huurprijsmutaties die van invloed zijn op de te factureren periode controleren. U kunt bijvoorbeeld bepalen of er geen uitzonderlijke mutaties plaatsgevonden hebben, of u kunt controleren of alle mutaties geaccordeerd zijn.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar het rapport **Verwachte mutaties in de te prolongeren maand**. 
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

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Prolongatierunoverzicht**.
2. De gelijknamige pagina **Prolongatierunoverzicht** opent; klik op **Nieuw**.
3. De kaartpagina **Prol.-run kaart** opent. Vul op deze pagina de volgende velden:
	* **Prol. periodenaam:** De laatst gefactureerde maand (de te factureren maand -1). De velden **Boekingsdatum** en **Documentdatum** worden automatisch gevuld.
	* **Alleen controleren:** 'Uit'.
	* **Erfpacht:** 'Uit'.
	* **Huur:** 'Aan'.
	* **Direct boeken:** ''.
4. Ga verder naar de processtap **[Genereren facturen](#genereren-facturen)**.

## Genereren facturen

Nadat u in de voorgaande stap aangegeven heeft welke periode gefactureerd dient te worden, kunnen de facturen gegenereerd worden. 

1. Klik op de pagina **Prol.-run kaart** op actie/functie **Uitvoeren/boeken**. De facturen worden gegenereerd, maar nog niet geboekt.
. Nadat de facturen gegenereerd zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (kolom **Boekingsstatus** in de prolongatieregels) de status getoond.
	*Als de status op de prolongatiekaart gelijk is aan Prol gereed zijn alle facturen zonder problemen aangemaakt. U kunt verder naar processtap **[Boeken facturen](#boeken-facturen)**.
	* Als de status op de prolongatiekaart *niet* gelijk is aan 'Prol gereed, dan zijn er één of meerdere facturen die niet juist aangemaakt zijn. Ga in dit geval verder naar processtap **[Controleren en oplossen fouten bij facturatie](#controleren-en-oplossen-fouten-bij-facturatie)**.

## Controleren en oplossen fouten bij facturatie

Wanneer er tijdens het genereren van de facturen fouten zijn ontstaan dient u deze te controleren en te corrigeren. 

 1. i op de pagina **Prol.-run kaart**  **Alle fouten**. De pagina **Fouten bij prolongatin** opent. 
 2. In dit scherm ziet u de foutmelding en bij elke eenheid en contractregel of klant het probleem dat zich voordoet. U dient deze fouten op te lossen. 
. Wanneer dit is gebeurd klikt u op de pagina **Prol.-runkaart** opnieuw o **Uitvoeren/oeken**. De facturen die fouten veroorzaakten worden opnieuw gegenereerd.
. Nadat de facturen gegenereerd zijn wordt op zowel veld **Status**) als op de individuele facturen (kolom **Boekingsstatus** in de prolongatieregels) de status getoond. 
	* Als de status op de prolongatiekaart gelijk is aan Prol gereed zijn alle facturen zonder problemen aangemaakt. U kunt verder naar processtap **[Boeken facturen](#boeken-facturen)**.
	* Als de status op de prolongatiekaart *niet** gelijk is aan Prol gereed zijn er één of meerdere facturen die niet juist aangemaakt zijn. Voer in dit geval opnieuw de processtap **[Controleren en oplossen fouten bij facturatie](#controleren-en-oplossen-fouten-bij-facturatie)** uit. 

## Boeken facturen

Wanneer er tijdens het genereren van de facturen geen fouten zijn ontstaan kunt u de gegenereerde facturen boeken.  

1. Ki op de pagina **Prol.-runkaart** voor de actie **Uitvoeren / Boeken**. De facturen worden geboekt.
2. Nadat de facturen geboekt zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (olom **Boekingsstatus** in de prolongatieregels) de status getoond. 
	* Als de status op de prolongatiekaart gelijk is aan Boeken gereed zijn alle facturen zonder problemen geboekt. 
	*  Als die u geboekt heeft voor de *voorgaande periode* was, ga dan verder bij de processtap **[Instellen te factureren contracten komende periode](#instellen-te-factureren-contracten-komende-periode)**. 
	* Als de prolongatie die u geboekt heeft voor de *komende periode* was, ga dan verder bij processtap **[Verzenden facturen](#verzenden-facturen)**.
	* Als de status op de prolongatiekaart *niet* gelijk is aan Boeken gereed zijn er één of meerdere facturen die niet zijn geboekt. Ga in dit geval verder naar processtap **[Controleren en oplossen fouten bij boeken](#controleren-en-oplossen-fouten-bij-boeken)**.

## Controleren en oplossen fouten bij boeken

Wanneer er tijdens het boeken van de facturen fouten zijn ontstaan dient u deze te controleren en te corrigeren. 

 1. Ki op de pagina **Prol.-run kaart** vo **Alle fouten**. De pagina **Fouten bij prolongatierun** opent.
 2. In dit scherm ziet u de foutmelding en bij elke eenheid en contractregel of klant het probleem dat zich voordoet. U dient deze fouten op te lossen.
. Wanneer dit is gebeurd kit u op de pagina **Prol.-run kaart** opnieuw voor de actie **Uitvoeren/boeken**. Er wordt  geprobeerd om de facturen die fouten veroorzaakten te boeken.
 4. Nadat de facturen geboekt zijn wordt op zowel de prolongatiekaart (veld **Status**) als op de individuele facturen (kolom **Boekingsstatus** in de prolongatieregels) de status getoond. 
	* Als de status op de prolongatiekaart gelijk is aan Boeken gereed zijn alle facturen zonder problemen geboekt. 
	*  Als de prolongatie die u geboekt heeft voor de *voorgaande periode* was, ga dan verder bij de processtap **[Instellen te factureren contracten komende periode](#instellen-te-factureren-contracten-komende-periode)**. 
		*  Als die u geboekt heeft voor de *komende periode* was, ga dan verder bij processtap **[Verzenden facturen](#verzenden-facturen)**.
	*  Als de status op de prolongatiekaart *niet* gelijk is aan 'Boeken gereed zijn er één of meerdere facturen die niet zijn geboekt. Voer in dit geval opnieuw de processtap **[Controleren en oplossen fouten bij boeken](#controleren-en-oplossen-fouten-bij-boeken)** uit. 

## Instellen te factureren contracten komende periode

Wanneer u de facturen voor de voorgaande periode verwerkt hebt kunt u voor de komende periode instellen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de liongnoin.
2. De gelijknamige pagina opent. Klik op **Nieuw**.
3. De pagina **Prol.-run kaart** opent. Vul op deze pagina de volgende velden:
	* **Prol. periodenaam:** De te factureren maand. De velden **Boekingsdatum** en **Documentdatum** worden automatisch gevuld.
	* **Alleen controleren:** 'Uit'.
	* **Erfpacht:** 'Uit'.
	* **Huur:** 'Aan'.
	* **Direct boeken:** ''.
4. Ga verder naar de processtap **[Genereren facturen](#genereren-facturen)**.

## Verzenden facturen

Wanneer u de facturen voor de komende periode geboekt heeft kunt u wanneer van toepassing de facturen en digitale betaalverzoeken versturen. 

1. Ki op de pagina **Prol.-run kaart** voor de act **Postex**. De pagina **Prolongatiefactuur PROL+** opent. 
2. Klik op **OK**. Voor de klanten waarvoor u heeft ingesteld dat zij een factuur of betaalverzoek moeten krijgen, wordt via Postex het betaalverzoek of de factuur verstuurd. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA0MDc0OTg0OSwtMTcwNjQ5NjU2MSwtNT
YyNDUzNTUxLC0xNzA4MTQzNjA0LDIzNjY3NDYxMCwtMTA3NTc2
ODI4MiwtMTMwNjIxMjQwLDc2NDczMTU5LDE0NTM4ODMyNTgsMT
g2MjE1MDkxMCwtMjEwNjg5OTk1OSwtMTM4MjEzNTI1MiwtMTgx
MzMyMTI3OSwtMTQwOTUyMjIsMTAzMDEyMzQ0NSwxODYwNjc1OT
c0LDQ1MzkxNzAwOCwxNDYyMzcyNjg3LDE3NzY2MDM4ODgsMTY2
NTAzNjI1XX0=
-->