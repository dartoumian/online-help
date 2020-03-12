# Dichtzetten periode

In dit werkproces worden perioden dichtgezet zodat er niet meer in deze periode geboekt kan worden. In eerste instantie zullen nog wel een aantal gebruikers toegang moeten hebben om de activiteiten met betrekking tot het afsluiten van deze periode uit te voeren en uiteindelijk zal de periode voor alle gebruikers worden dicht gezet.

## Dichtzetten periode

Wanneer u een periode dicht wilt zetten doet u dat altijd eerst voor de gehele boekhouding. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Boekhoudinstelling**.
2. Vul in het veld **Boeken toegestaan vanaf** de datum vanaf wanneer u boeken toe wilt staan. 
3. Bepaal of u het veld **Boeken toegestaan tot** ook aan wilt passen. 

## Opvoeren uitzonderingen per gebruiker

De velden **Boeken toegestaan vanaf** en **Boeken toegestaan tot** uit de **boekhoudinstellingen** gelden voor alle gebruikers. In de **gebruikersinstellingen** kunt u uitzonderingen op de algemene instelling opgegeven worden. Op de **gebruikersinstellingen** komen ook de velden **Boeken toegestaan vanaf** en **Boeken toegestaan tot** terug. Zijn deze bij een gebruiker leeg dan gelden de instellingen uit de **Boekhoudinstellingen**. Zijn er waardes ingevuld in de **gebruikersinstellingen** dan hebben deze prioriteit boven de instellingen in de **Boekhoudinstellingen**

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Gebruikersinstellingen** en zoek de gebruiker op waarvoor u een uitzondering op wilt voeren. Open de kaart voor deze gebruiker. 
2. Vul in het veld **Boeken toegestaan vanaf** de datum vanaf wanneer u boeken toe wilt staan voor deze gebruiker.
3. Bepaal of u het veld **Boeken toegestaan tot** ook aan wilt passen. 

## Verwijderen uitzonderingen per gebruiker

Wanneer u in de voorgaande stap uitzonderingen per gebruiker opgevoerd heeft en de periode dient ook afgesloten te worden voor de gebruiker waarvoor u de uitzonderingen heeft opgevoerd dient u de **Gebruikersinstellingen** voor deze gebruiker aan te passen. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Gebruikersinstellingen** en zoek de gebruiker op waarvoor u de uitzondering ongedaan wilt maken. Open de kaart voor deze gebruiker. 
2. Maak het veld **Boeken toegestaan vanaf** leeg. 
3. Bepaal of u het veld **Boeken toegestaan tot** aan wilt passen. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU1MjU4MjAzMF19
-->