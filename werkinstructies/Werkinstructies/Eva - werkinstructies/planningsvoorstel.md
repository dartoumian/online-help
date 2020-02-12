# Planningsvoorstel

In dit detailproces wordt beschreven hoe een transferorder kan worden aangemaakt via een planningsvoorstel om artikelen te kunnen verplaatsen van het hoofdmagazijn naar een submagazijn. 

## Processchema

## Planningsvoorstel

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de lijst **Planningsvoorstellen**.
2. Kies voor de functie **Regeneratief plan berekenen**.
3. De pagina **Plan berekenen - Planningsvoorstel** opent. Vul hier de volgende velden:
	* **MRP:** Dient altijd aangevinkt te zijn.
	* **Begindatum:** Vul hier de datum van vandaag in.
	* **Einddatum:** Kies hier een datum die twee weken vanaf de begindatum in de toekomst ligt.
	* **Planningsparameters voor uitzonderingswaarschuwingen respecteren:** Dient aangevinkt te worden.
4. Klik op **OK**. Het planvoorstel wordt berekend. 

## Planningsboodschap uitvoeren

Het rapport kan zowel geaccepteerde als niet-geaccepteerde regels geven. Geaccepteerde regels kunnen 'verplaatst' worden en niet-geaccepteerde regels moeten na controle verwijderd worden, of alsnog geaccepteerd worden. U gaat nu inkoop/transferorders aanmaken.

 1. Klik op **Planningsboodschap uitvoeren**.
 2. Vul de volgende velden op het scherm dat verschijnt:
	* **Inkooporder:** Kies voor Inkooporders aanmaken.
	* **Transferorder:** Kies voor Inkooporders aanmaken.
	* **Transferorders combineren:** Dit is een keuzeveld. 
 3. Klik op **OK**. Er zullen nu nieuwe orders worden aangemaakt. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM0ODA5NzE4OCwxMTE1NjQ2NjQxXX0=
-->