# Periodiek actualiseren clusterverdeelsleutels

In dit werkproces worden de clusterverdeelsleutels geactualiseerd op basis van de status van de eenheden in het cluster.

## Actualiseren verdeelsleutels

In deze processtap worden clusterverdeelsleutels in bulk geactualiseerd.

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Verhuurde of leegstaande eenheden niet in meest recente clusterverdeelsleutel**. 
2. Wanneer u eerst een overzicht wilt opvragen van de verdeelsleutels zonder dat deze gelijk geactualiseerd worden kunt u de optie **Alleen controleren** aan laten staan. Wilt u de verdeelsleutels gelijk actualiseren dan zet u deze optie uit. 
3. Wanneer u alleen bepaalde type verdeelsleutels wilt actualiseren kunt u dit aangeven in het veld **Verdeelsleutel type**.
4. Klik op **Verzenden naar...** en kies voor **Microsoft Excel document**.  Klik op **OK**. De verdeelsleutels worden geactualiseerd. Er wordt ook een rapport gegenereerd met de geactualiseerde verdeelsleutels. 
5. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de pagina **Clusterverdeelsleuteloverzicht**. 
6. Stel een filter in op veld **Status** = Voorlopig. En een filter op het veld **Verdeelsleuteltype** <> LINEAIR. Dit zijn de verdeelsleutels die geactualiseerd zijn en waaraan nieuwe eenheden toegevoegd zijn waarvoor een wegingsfactor opgegeven dient te worden. 
7. Open de eerste verdeelsleutel. Stel een filter in voor de kolom **Teller** = 0. Dit zijn alleen eenheden in de clusterverdeelsleutel dit als wegingsfactor 0 hebben en die u eventueel een wegingsfactor toe dient te kennen,
8. Klik op de pijl naar rechts aan de rechterkant van uw scherm om de volgende verdeelsleutel waarvoor u wegingsfactoren toe dient te wijzen te openen. Het filter **Teller** = 0 blijft actief. 
9. Wanneer u alle wegingsfactoren toegekend heeft  kunt u de verdeelsleutels activeren. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Clusterverdeelsleutels in bulk activeren**. 
10. Vul in het scherm dat opent in het veld **Start datum** de ingangsdatum van de te activeren verdeelsleutels in. Deze dient altijd in de toekomst te liggen. Klik op **Verzenden naar...** en kies voor **Microsoft Excel document**. De verdeelsleutels worden geactiveerd en er wordt een rapport gegenereerd met de geactiveerde verdeelsleutels. 
11. In de voorgaande stappen zijn de verdeelsleutels geactualiseerd waarin nieuwe eenheden opgenomen zijn. De volgende stap is het actualiseren van verdeelsleutels waaruit eenheden weg gevallen zijn. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Geactiveerde clusterverdeelsleutels met OG Eenheden die niet-verhuurd zijn of niet-leegstaan **. 
12.  Wanneer u eerst een overzicht wilt opvragen van de verdeelsleutels zonder dat deze gelijk geactualiseerd worden kunt u de optie **Alleen controleren** aan laten staan. Wilt u de verdeelsleutels gelijk actualiseren dan zet u deze optie uit. 
13. Wanneer u alleen bepaalde type verdeelsleutels wilt actualiseren kunt u dit aangeven in het veld **Verdeelsleutel type**.
14. Klik op **Verzenden naar...** en kies voor **Microsoft Excel document**.  Klik op **OK**. De verdeelsleutels worden geactualiseerd. Er wordt ook een rapport gegenereerd met de geactualiseerde verdeelsleutels. 
15. Omdat in deze stap alleen eenheden uit verdeelsleutels verdwijnen hoeft u geen wegingsfactoren aan te passen en kunt u de nieuwe verdeelsleutels direct activeren. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar het rapport **Clusterverdeelsleutels in bulk activeren**. 
10. Vul in het scherm dat opent in het veld **Start datum** de ingangsdatum van de te activeren verdeelsleutels in. Deze dient altijd in de toekomst te liggen. Klik op **Verzenden naar...** en kies voor **Microsoft Excel document**. De verdeelsleutels worden geactiveerd en er wordt een rapport gegenereerd met de geactiveerde verdeelsleutels. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg3NDYxNjEyOF19
-->