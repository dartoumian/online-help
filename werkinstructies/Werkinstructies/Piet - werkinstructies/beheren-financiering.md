# Beheren financiering

In dit werkproces worden nieuwe leningen aangetrokken en bestaande leningen gemuteerd.

## [](https://github.com/NielsBlikman/Test/blob/master/Financi%C3%ABn/Treasury/Beheren-financiering/index.md#vastleggen-basisgegevens)Vastleggen basisgegevens

Wanneer u een nieuwe financiering aantrekt dient u als eerste de basisgegevens te registreren.

1.  Navigeer via het zoekveld  [![zoeken icon](https://github.com/NielsBlikman/Test/raw/master/assets/images/zoeken.png "zoeken icon")](https://github.com/NielsBlikman/Test/blob/master/assets/images/zoeken.png)  naar  **Financieringenoverzicht**  en klik op  **+Nieuw**.
2.  Vul in het scherm dat opent de volgende velden:
    -   **Nr.**: Het nummer van de financiering.
    -   **Extern nummer:**  Het nummer dat wordt gehanteerd door de geldgever.
    -   **Omschrijving**
    -   **Status**: Wanneer u de lening mee wilt nemen in de prolongatie zet u de status op  **Akkoord**.
    -   **Fin. boekingsgroep**: Selecteer hier het type lening.
    -   **Geldgever ID**: Vul het contactnummer van de geldgever.
    -   **Code transactiewijze**: Selecteer de transactiewijze voor leningen.
    -   **Code bankrekening**: Selecteer het bankrekeningnummer waarop de rente en aflossingen van de lening betaald dienen te worden.
3.  Op tabblad  **WSW**  kunt u desgewenst extra informatie m.b.t. het WSW kwijt. De velden op dit tabblad zijn niet verplicht.
4.  Klik in het feitenblok op het getal achter  **Kasstromen (act.model)**  en kies in het scherm dat opent voor  **+Nieuw**.
5.  Vul in het veld  **Ingangsdatum**  de datum van de storting van de leningen in.
6.  Kies in het veld  **Soort kasstroom**  de kasstroom voor het storten van de hoofdsom.
7.  Vul in het veld  **Bedrag**  het bedrag dat gestort wordt op deze datum.
8.  Sluit het scherm voor kasstromen om terug te keren naar het scherm met de algemene gegevens van de financiering.

## [](https://github.com/NielsBlikman/Test/blob/master/Financi%C3%ABn/Treasury/Beheren-financiering/index.md#opvoeren-financieringsvorm)Opvoeren financieringsvorm

Nadat u de basisgegevens geregistreerd hebt kunt u de wijze van aflossing, rentebetaling en de rentepercentages opgeven.

1.  Navigeer via het zoekveld  [![zoeken icon](https://github.com/NielsBlikman/Test/raw/master/assets/images/zoeken.png "zoeken icon")](https://github.com/NielsBlikman/Test/blob/master/assets/images/zoeken.png)  naar  **Financieringenoverzicht**  en kies via  **Beheren**  voor  **Verwerken**. Klik in het feitenblok op het getal achter  **Fin.vormen (act.model)**  en kies in het scherm dat opent voor  **+Nieuw**. Vul de volgende velden in het scherm dat opent:
    -   **Begindatum:**  Stortingsdatum van de financiering.
    -   **Looptijd (jaren/maanden)**: De looptijd in jaren.
    -   **Aflossingswijze**
    -   **Periode rentebetaling**: Geef aan om de hoeveel maanden rente betaald dient te worden.
    -   **Periode rentebepaling**: Hier geldt dezelfde waarde als in veld  **Periode rentebetaling**.
    -   **Periode aflossingen**: Geef aan om de hoeveel maanden de aflossing betaald wordt (indien van toepassing).
    -   **Rente prognose**
    -   **Rente conventie**
    -   **Verschuiving coupondatum**
2.  Navigeer naar de  **Rentepercentages**. Vul het rentepercentage voor de eerste periode in het veld  **Percentage**.
3.  Geef in het veld  **Rente vast tot**  op tot wanneer het rentepercentage geldig is. Wanneer deze datum voor de einddatum van de financieringsvorm ligt wordt er automatisch een regel met code  **Renteconversie**  aangemaakt. U kunt de velden in deze regel leeg laten.
4.  Sluit het scherm voor rentepercentages en vervolgens het scherm  **Financieringsvorm**  om terug te keren naar het scherm  **Financiering**.
5.  Klik op  **Bijwerken**. Op schermdeel/tabblad  **Rente/Aflossingsschema**  wordt het vervalschema getoond.

## [](https://github.com/NielsBlikman/Test/blob/master/Financi%C3%ABn/Treasury/Beheren-financiering/index.md#controleren-en-accorderen-vervalschema)Controleren en accorderen vervalschema

Nadat u de basisgegevens en de financieringsvorm opgevoerd heeft kunt u het vervalschema controleren en accorderen.

1.  Op de kaart  **Financiering**  wordt op schermdeel/tabblad  **Rente/Aflossingsschema**  het vervalschema getoond. Vergelijk de datums en de kasstromen met het aflossingsschema dat u van de geldgever gekregen heeft.
2.  Wanneer de gegevens akkoord zijn kunt u de financieringsgegevens (laten) accorderen. Klik op  **Accorderen**.
3.  Staat het veld  **Status**  nog niet op  **AKKOORD**, vul deze waarde nu dan in dit veld.

## [](https://github.com/NielsBlikman/Test/blob/master/Financi%C3%ABn/Treasury/Beheren-financiering/index.md#controleren-en-accorderen-vervalschema-1)Controleren en accorderen vervalschema

Wanneer er een extra aflossing of extra storting voor de leningen plaatsvindt kunt u deze registreren door middel van het opvoeren van een handmatige kasstroom.

1.  Navigeer via het zoekveld  [![zoeken icon](https://github.com/NielsBlikman/Test/raw/master/assets/images/zoeken.png "zoeken icon")](https://github.com/NielsBlikman/Test/blob/master/assets/images/zoeken.png)  naar  **Financieringenoverzicht**  en open de lening waarvoor u de extra kasstroom op wilt voeren.
2.  Klik in het feitenblok op het getal achter  **Kasstromen (act.model)**  en klik in het scherm dat opent op  **Nieuw**.
3.  Vul in het veld  **Ingangsdatum**  de datum van de extra aflossing/storting van de leningen in.
4.  Kies in het veld  **Soort kasstroom**  de soort kasstroom die van toepassing is.
5.  Vul in het veld  **Bedrag**  het bedrag dat gestort/afgelost wordt op deze datum. Aflossingen voert u op als negatief bedrag.
6.  Sluit het scherm voor kasstromen om terug te keren naar de pagina  **Financiering**.
7.  Klik op  **Bijwerken**. Op schermdeel/tabblad  **Rente/Aflossingsschema**  wordt het opnieuw berekende vervalschema getoond.
8.  Wanneer het vervalschema correct is kunt u de kasstroom (laten) accorderen. Klik in het feitenblok op het getal achter  **Kasstromen (act.model)**  en open de kasstroom die u wilt accorderen. Klik vervolgens op  **Accorderen**.

## [](https://github.com/NielsBlikman/Test/blob/master/Financi%C3%ABn/Treasury/Beheren-financiering/index.md#wijzigen-rentepercentage)Wijzigen rentepercentage

Wanneer het rentepercentage van een lening wijzigt voert u dit nieuwe percentage op bij de financieringsvorm.

1.  Navigeer via het zoekveld  [![zoeken icon](https://github.com/NielsBlikman/Test/raw/master/assets/images/zoeken.png "zoeken icon")](https://github.com/NielsBlikman/Test/blob/master/assets/images/zoeken.png)  naar  **Financieringenoverzicht**  en open de lening waarvoor u het rentepercentage wilt wijzigen.
2.  . Klik op de pagina  **Financiering**  in het feitenblok op het getal achter  **Fin.vormen (act.model)**. Klik op  **Rentepercentages**. Vul het nieuwe rentepercentage in op een nieuwe regel.
3.  Sluit het scherm voor rentepercentages en vervolgens het scherm  **Financieringsvorm**  om terug te keren naar pagina  **Financiering**.
4.  Klik op  **Bijwerken**. Op schermdeel/tabblad  **Rente/Aflossingsschema**  wordt het vervalschema getoond.
5.  Wanneer het vervalschema correct is kunt u het nieuwe rentepercentage (laten) accorderen.
6.  Klik op de kaart  **Financiering**  in het feitenblok op het getal achter  **Fin.vormen (act.model)**. Klik op  **Rentepercentages**. Selecteer het rentepercentage dat u wilt accorderen. Klik vervolgens op  **Accorderen**.


<!--stackedit_data:
eyJoaXN0b3J5IjpbNDI2NzkwODI5XX0=
-->