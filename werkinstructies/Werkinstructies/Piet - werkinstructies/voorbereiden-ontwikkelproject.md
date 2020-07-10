
# Voorbereiden ontwikkelproject

Er is besloten om met het project te starten en er is een goedgekeurde investeringsbegroting.

# Aanmaken projectmodel

## Omschrijving
Wanneer de uitgangspunten van de Stichtingskosten (STIKO) zijn gedefinieerd en per fase zijn vastgelegd kunnen deze gegevens worden opgevoerd in het projectmodel in Dynamics Empire. Om in de toekomst voorbereid te zijn op mogelijke wijzigingen is het advies om altijd een gemengd projectmodel aan te maken. 

## Vastleggen projectmodel (enkel)
 1. Ga voor het aanmaken van een projectmodel naar **Projectmodel aanmaken** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit het overzicht voor welk projecttype het model aangemaakt moet worden. 
 3. Vervolgens opent de projectmodelkaart.
 4. Invullen projectgegevens in het tabblad **Algemeen**:
  * **Projectmodelnr.** dit kan automatisch gevuld worden d.m.v. TAB maar advies is om hier een "eigen" nummer te kiezen. 
  * **Naam** van het project. 
  * **Omschrijving** van het project.
  * **Besluit**, maak een keuze uit de tabel welke fase geldt.
  * **Startdatum**, wanneer is het project gestart?
  * **Opleverdatum**, wanneer wordt verwacht het project opgeleverd te zijn?
  * **Clusternr.**, kies hier het aangemaakte projectcluster.
  * **Startjaar**, jaar wanneer het project start.
  * **Jaar van oplevering**, wanneer het project is afgesloten.
 5. Na het vullen van het tabblad **Algemeen** ga je naar het lint en kies **Acties** vervolgens **Functies** en dan **Exploitatiemodel ophalen**.
 6. Kies het exploitatiemodel die voor dit project geldt.
 

##Vastleggen projectmodel (gemengd)

    Bij een GEMENGD project herhaal de stappen 1 t/m 5 die beschreven staan bij vastleggen projectmodel (enkel). Het Exploitatiemodel is de eerste keer altijd "GEMENGD"! Bij terugkeren op het overzicht **Projectmodeloverzicht** selecteer de regel die zojuist is aangemaakt en vervolgens in het lint **Nieuw** en dan **+Nieuw**. 
    
 1. Vul het tabblad **Algemeen** met dezelfde informatie als het eerste projectmodel (acties vermeld onder punt 4) met als uitzondering het veld **Projectmodelnr.**, hier voer je het eerste nummer in welke je al hebt aangemaakt met als toevoeging het exploitatiemodelnummer voor het onderdeel wat je gaat opvoeren. Voorbeeld: VGO-562-1002 (1002 staat voor NDAEB NTV)
 2. Na het vullen van het tabblad **Algemeen** ga je naar het lint en kies **Acties** vervolgens **Functies** en dan **Exploitatiemodel ophalen**.
 3. Kies het exploitatiemodel die voor dit project geldt.
 4. Indien nodig herhaal de stappen 1 tot en met 3.

Als de modellen zijn aangemaakt moeten deze gekoppeld worden onder het "GEMENGD" model.

1. Ga voor het koppelen van de projectmodellen naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
2. Kies het projecttype waarvoor het gemengde project hebt aangemaakt.
3. Kies uit de lijst het projectmodel met de exploitatiemodelomschrijving "GEMENGD".
4. Ga naar het lint bovenin en kies **Navigeren** en vervolgens **Projectmodel** en tot slot **Onderdeel van cumulatief model**.
5. In dit overzicht zoek je bij kolom **Modelnr.** in het veld met behulp van de opzoekwaarde (...) het onderdeel wat gekoppeld moet worden.
6. Vul op de regel bij het veld **Verdeelsleutel%** het percentage in wat geldt voor dat model.
7. Herhaal 5 en 6 indien er meerdere onderdelen gekoppeld moeten worden.
8. Met het pijltje links bovenin ga je terug naar het GEMENGD project.
9. De volgende stap is in het lint **Acties** en dan **Functies** en als laatste **Cumuleren budgetonderdelen** 
10. Systeem vraagt: Wilt u de budgetten van de onderdelen cumuleren? actie **JA**

In de lijst Projectmodeloverzicht staat het projectmodel herkenbaar aan de regel in het vet gedrukt.

#Aanmaken cluster

##Omschrijving
Voor het aanmaken van een projectmodel is het raadzaam om van te voren het cluster aan te maken. 

De beschrijving van het aanmaken van een cluster is opgenomen in het werkproces: "Beheren clusterinformatie".
Met als toevoeging dat bij Vastgoedontwikkeling er géén OGE's worden toegevoegd in het cluster en de clusterverdeelsleutel "liniair" is. Uitzondering hierop kan een herstructurering-project zijn, dan dient het toevoegen van de OGE mogelijk voor uitkering van vergoedingen.

#Registreren investeringsbegroting

##Omschrijving
Wanneer de uitgangspunten van de Stichtingskosten (STIKO) zijn gedefinieerd en per fase zijn vastgelegd kunnen deze gegevens worden opgevoerd in het projectmodel in Dynamics Empire.  

## Opvoeren, handmatig, van de investeringsbegroting (enkel)
 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het projectmodel waarvoor de investeringsbegroting is bedoeld.
 4. Vervolgens naar het tabblad **Regels**.
 5. Vervolgens per werksoortcode de investeringsbegroting opvoeren d.m.v. het vullen van de volgende velden:    
	 a. Indien er geen aantallen zijn maar alleen een "totaal" bedrag dan het veld **Kostprijs** vullen, dit bedrag is dan ook zichtbaar in de kolom "Begroot" en "Budget".
	 b. Indien er wel aantallen zijn dan kolom **Aantal** vullen en vervolgens een bedrag bij kolom **Kostprijs**, bij kolom "Begroot" en "Budget" is de uitkomst de waarde van Aantal x Kostprijs.
 6.  De volgende stap in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Herberekenen (formules)**. 
 7. Vervolgens in het tabblad **Algemeen** de knop **Bevroren** versie" naar rechts zetten.
 8. In het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.

Het project is aangemaakt en is zichtbaar in de lijst "Projecten".
##Opvoeren, middels synchroniseren, van de investeringsbegroting of besluitfase (enkel)
##Omschrijving
Het opvoeren van de begroting en budgetten wordt middels synchroniseren met expertsysteem zoals REAFORCE uitgevoerd.

 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het projectmodel waarvoor de investeringsbegroting is bedoeld.
 4. Vervolgens boven in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Synchroniseren vanuit projectcalculatiesysteem**.

Dynamics Empire zal de goedgekeurde begroting en budgetten overhalen, het model bevriezen. Vervolgens moet nog de stap in het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.


## Opvoeren, handmatig, van de investeringsbegroting (gemengd)
1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het onderliggende projectmodel van het gemengde project waarvoor de investeringsbegroting is bedoeld. Herkenbaar aan het soort "Onderdeel".
 4. Vervolgens naar het tabblad **Regels**.
 5. Vervolgens per werksoortcode de investeringsbegroting opvoeren d.m.v. het vullen van de volgende velden:    
	 a. Indien er geen aantallen zijn maar alleen een "totaal" bedrag dan het veld **Kostprijs** vullen, dit bedrag is dan ook zichtbaar in de kolom "Begroot" en "Budget".
	 b. Indien er wel aantallen zijn dan kolom **Aantal** vullen en vervolgens een bedrag bij kolom **Kostprijs**, bij kolom "Begroot" en "Budget" is de uitkomst de waarde van Aantal x Kostprijs.
 6.  De volgende stap in het lint bovenin **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Herberekenen (formules)**. 
 7. Herhaal eventueel bij meer dan 1 onderliggend projectmodel de stappen 3 t/m 6!
 8. Vervolgens terug naar het projectmodeloverzicht, daar kies je de "vet" gedrukte regel van het gemengd project. Herkenbaar aan het soort "Cumulatief". 
 9. Vervolgens in het lint bovenin **Meer opties** en/of vervolgens**Acties** vervolgens **Functies** vervolgens **Cumuleren budgetonderdelen** en tot slot **Herberekenen (formules)**.
 10. Vervolgens in het tabblad **Algemeen** de knop **Bevroren** versie" naar rechts zetten.
 11. In het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.

Het project is aangemaakt en is zichtbaar in de lijst "Projecten".
##Opvoeren, middels synchroniseren, van de investeringsbegroting of besluitfase (gemengd)
##Omschrijving
Het opvoeren van de begroting en budgetten wordt middels synchroniseren met expertsysteem zoals REAFORCE uitgevoerd.

 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het gemengde projectmodel waarvoor de investeringsbegroting is bedoeld.
 4. Vervolgens boven in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Synchroniseren vanuit projectcalculatiesysteem**.

Dynamics Empire zal de goedgekeurde begroting en budgetten overhalen, het model bevriezen. Vervolgens moet nog de stap in het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.


# Aanpassen van de investeringsbegroting handmatig (enkel)

##Omschrijving

Indien er een aanpassing van het budget en of begrotingswijzing moet plaats vinden dan pas je de versie van het projectmodel aan. Deze stap is ook van toepassing indien er een nieuwe besluitfase is genomen. 

##Aanpassen, handmatig, van de investeringsbegroting of besluitfase (enkel)
 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het projectmodel waarvoor de investeringsbegroting is bedoeld.
 4. Vervolgens boven in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Nieuwe versie**.
 5. Systeem opent direct een nieuwe versie. Herkenbaar in het tabblad **Algemeen** bij veld versienummer een hogere versie staat dan ervoor.
 6. Vervolgens in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Projectmodel kopiëren** 
 7. In het veld **Bron modelnr.** zoek met de ... (opzoekwaarde) de juiste regel waarvan je wilt kopiëren (is altijd één versienummer lager dan wordt aangemaakt).
 8. Bij het veld **Inclusief kop** zet je de schakelaar naar RECHTS dan OK.
 9. In het tabblad **Regels** pas je de regels aan die van toepassing zijn. Werkwijze beschreven en uitvoeren zoals bij "Opvoeren van de begrotingsregels" , het betreft de punten 5 en 6. 
 10. In het tabblad **Algemeen** kies bij veld **Besluit** de juiste fase en vervolgens de knop **Bevroren versie** naar rechts zetten. 
 11. In het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.
 12. Vervolgens met de pijl links bovenin het scherm ga je terug naar de versie waarvan de kopie is, deze openen. 
 13. In het tabblad **Algemeen** bij het veld **Niet actief** de knop naar rechts zetten. Hiermee zal deze versie van het projectmodel uit de lijst verdwijnen. 
 
Het project met een verhoogd versienummer is aangemaakt en is zichtbaar in de lijst "Projecten".
##Aanpassen, middels synchroniseren, van de investeringsbegroting of besluitfase (enkel)
##Omschrijving
Gewijzigde begroting en budgetten synchroniseren met expertsysteem zoals REAFORCE.

 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het projectmodel waarvoor de investeringsbegroting is bedoeld.
 4. Vervolgens boven in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Synchroniseren vanuit projectcalculatiesysteem**.

Dynamics Empire zal de goedgekeurde begroting en budgetten overhalen, het model bevriezen. Vervolgens moet nog de stap in het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.
Vervolgens met de pijl links bovenin het scherm ga je terug naar de versie die is gekopieerd, deze openen. 
In het tabblad **Algemeen** bij het veld **Niet actief** de knop naar rechts zetten. Hiermee zal deze versie van het projectmodel uit de lijst verdwijnen. 

##Aanpassen, handmatig, van de investeringsbegroting of besluitfase (gemengd)
 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het projectmodel waarvoor de investeringsbegroting is bedoeld.
 4. Vervolgens boven in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Nieuwe versie**.
 5. Systeem opent direct een nieuwe versie. Herkenbaar in het tabblad **Algemeen** bij veld versienummer een hogere versie staat dan ervoor.
 6. Vervolgens in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Projectmodel kopiëren** 
 7. In het veld **Bron modelnr.** zoek met de ... (opzoekwaarde) de juiste regel waarvan je wilt kopiëren (is altijd één versienummer lager dan wordt aangemaakt).
 8. Bij het veld **Inclusief kop** zet je de schakelaar naar RECHTS dan OK.
 9. In het tabblad **Regels** pas je de regels aan die van toepassing zijn. Werkwijze beschreven en uitvoeren zoals bij "Opvoeren van de begrotingsregels" staat beschreven, het betreft de punten 5 en 6. 
 10. In het tabblad **Algemeen** kies bij veld **Besluit** de juiste fase en vervolgens de knop **Bevroren versie** naar rechts zetten. 
 11. In het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.
 12. Vervolgens met de pijl links bovenin het scherm ga je terug naar de versie die is gekopieerd, dezen openen. 
 13. In het tabblad **Algemeen** bij het veld **Niet actief** de knop naar rechts zetten. Hiermee zal deze versie van het projectmodel uit de lijst verdwijnen. 
 
Het project met een verhoogd versienummer is aangemaakt en is zichtbaar in de lijst "Projecten".

##Aanpassen, middels synchroniseren, van de investeringsbegroting of besluitfase (gemengd)
##Omschrijving
Gewijzigde begroting en budgetten synchroniseren met expertsysteem zoals REAFORCE.

 1.Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor de investeringsbegroting is bedoeld.
 3. Kies uit de lijst het projectmodel waarvoor de investeringsbegroting is bedoeld, het gemende model.
 4. Vervolgens boven in het lint **Meer opties** en/of vervolgens **Acties** vervolgens **Functies** en tot slot **Synchroniseren vanuit projectcalculatiesysteem**.

Dynamics Empire zal de goedgekeurde begroting en budgetten overhalen, het model bevriezen. Vervolgens moet nog de stap in het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.
Vervolgens met de pijl links bovenin het scherm ga je terug naar de versie die is gekopieerd. 
In het tabblad **Algemeen** bij het veld **Niet actief** de knop naar rechts zetten. Hiermee zal deze versie van het projectmodel uit de lijst verdwijnen.  

# Aanmaken Project

## Omschrijving
Wanneer de Stichtingskosten (STIKO) zijn gedefinieerd en per fase zijn vastgelegd en opgevoerd in het projectmodel in Dynamics Empire kan er een project aangemaakt worden.  

## Aanmaken project 
 1. Ga naar **Projectmodeloverzicht** dit kan via de ZOEKKNOP rechts bovenin. 
 2. Kies uit de lijst het projecttype waarvoor je een project wilt aanmaken.
 3. Kies uit de lijst het projectmodel waarvoor je een project wilt aanmaken.
 4. Vervolgens bij het tabblad **Algemeen**.
 5. De knop **Bevroren versie** naar rechts zetten.
 6. In het lint **meer Opties** dan/of **Acties** vervolgens **Functies** en tot slot **Versie doorzetten**, het systeem vraagt "Wilt u deze versie doorzetten" actie **Ja**.

Het project is aangemaakt en is zichtbaar in de lijst "Projecten".
 
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQxMTk0MDMzNV19
-->