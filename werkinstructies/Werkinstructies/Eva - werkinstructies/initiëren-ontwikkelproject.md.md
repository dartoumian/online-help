

## Aanmaken projectmodel

## Omschrijving
In Dynamics Empire worden in de projectenadministratie de projectmodellen aangemaakt. De projectmodellen zijn typen projecten. Het is in Dynamics Empire mogelijk om enkelvoudige en gemengde projectmodellen aan te maken.

## Processchema

## Processtappen
### Enkelvoudig project
Deze werkinstructie behandelt het aanmaken van een enkelvoudig renovatieproject, waarbij zes appartementen in Zeist zullen worden gerenoveerd.
- Projectnummer: P2000
- Projectnaam: Renovatie Geisenlaan
- Projectomschrijving: Renovatie 6 appartementen te Zeist

Het project bestaat uit huurwoningen DAEB. Voor de huurwoningen geldt een BTW-regime Niet terugvorderbaar.

De werkinstructie behandelt het opstellen van een investeringsbegroting en budget in Dynamics Empire. Wanneer je de Reaforce- of Ortec-koppeling gebruikt zijn deze stappen nog steeds van toepassing, met uitzondering van het daadwerkelijk opvoeren van begroting en budgetbedragen. De begroting en budgetten worden met een druk op de knop overgehaald van het expertsysteem. Deze instructie legt uit hoe.

 1. Navigeer via het zoekveld naar de lijst **projectmodeloverzicht**.
 2. Kies het projecttype waarmee u een projectmodel wilt aanmaken en selecteer bijvoorbeeld **Investeringen bestaand bezit in exploitatie**.
 3. Er verschijnt een lijstpagina met eerder aangemaakte projectmodel van het betreffende projecttype. 
 4. Klik op **Nieuw** in het lint van deze lijstpagina.
 5. Dynamics Empire zal een nieuwe lege projectmodelkaart aanmaken. Op de kaart is slechts een versienummer (1) en een projecttype ingevuld.
 6. Vul op het tabblad **Algemeen** de onderstaande velden op projectmodelkaart:
	* **Projectmodelnr.** P2000
	* **Projectnaam** Renovatie Geisenlaan
	* **Projectomschrijving** Gemengd
	* **Besluit** Initiatiefase
	* **Start- en opleverdatum** Naar eigen inzicht
	* **Clusternr.** P2000
 7. Navigeer in het lint van de projectmodelkaart via **Acties - Functies - Exploitatiemodel ophalen** naar de lijst met exploitatiemodellen.
 8. Kies het exploitatiemodel waarmee u een projectmodel wilt aanmaken en selecteer bijvoorbeeld **Huurwoning DAEB NTV** en druk op **OK**.
 9.  Dynamics Empire zal het tabblad **Regels** vullen met budgetregels (STIKO). Met het selecteren van een exploitatiemodel is tevens voor het projectmodel bepaald wat de boekingsgang is en default BTW percentage per werksoort. Dit is te herkennen aan de Werksoortboekingsgroepen in de regels van het projectmodel. 01_N21 staat voor Huurwoningen DAEB, Niet-terug vorderbare BTW en 21% BTW.
 10. Sluit de kaart van het projectmodelkaart. U komt daarmee terug in de lijst met het **projectmodeloverzicht** waarin het zojuist aangemaakte projectmodel zichtbaar is.

<hr>

>#### Uitlichten van tip/extra aandachtspunt o.i.d. (H4)
>
>Bij het ophalen van het exploitatiemodel wordt het sjabloon met Cashflowprognose fase verdeelsleutels overgenomen naar het Projectmodel. De gegevens van de tabel “Cashflowprognose fase verdeelsleutel sjabloon” worden overgenomen naar de tabel “Projectmodel Cashflowprognose fase verdeelsleutel”. Daarmee worden alle voorkeursinstellingen met betrekking tot het verdelen van de cashflowprognose over verschillende projectfase gekoppeld aan het gekozen projectmodel. Klik op Cashflowprognose fase verdeelsleutel in het lint om de initiële verdeling te bekijken en eventueel project specifiek te maken.


<hr>

## Zie ook (links naar andere werkprocessen uit dezelfde bedrijfsfunctie) (H2)
Werkinstructie X  
Werkinstructie Y  
Werkinstructie Z
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MDg0MTg3ODNdfQ==
-->