# Nieuw artikel opvoeren

Zodra er een nieuw artikel beschikbaar is, of reeds in gebruik, is het zaak dat deze ook in Dynamics Empire wordt vastgelegd, zodat de vakmannen het artikel kunnen verbruiken en het ook als kosten op het onderhoudsverzoek kan worden vastgelegd.

## Processchema

## Nieuw artikel opvoeren

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar de pagina **Artikelen**.
2. Klik op  **Nieuw**.
3. Druk op **Tab** of **Enter**: er wordt automatisch een artikelnummer aangemaakt. Vul de volgende velden:
	* **Omschrijving:** Geef de omschrijving van het artikel in. 
	* **Basiseenheid:** Geef de eenheid op die voor het artikel van toepassing is. 
	* **Artikelcategoriecode** Selecteer de juiste artikelcategorie. 
4.  Ga nu naar het tabblad **Facturering**. Vul het volgende veld:
	* **Vaste verrekenprijs:** Geef hier de prijs inclusief BTW voor het artikel op. 
5.  Ga nu naar het tabblad **Prijs en boeking**. Vul de volgende velden:
	* **Artikel toeslag verbruik%:** Geef hier de toeslag op die wordt berekend over de kostprijs van het artikel. 
	* **Prijs/winst berekenen:** Geef de waarde **Verkoopprijs = Kostprijs + Winst** in. 
6.  Ga naar het tabblad **Aanvulling**. Vul de volgende velden:
	* **Leveranciersnummer:** Geef hier de leverancier op waar het artikel normaal gesproken wordt ingekocht. 
 	* **Artikelnr. Leverancier:** Geef het nummer op waaronder het artikel bekend is bij de leverancier. 
 	* **Ink. -eenheid:** Geef de eenheid op waaronder de leverancier het artikel levert. 
7.  Ga nu naar het tabblad **Planning**. Vul het volgende veld:
	* **Bestelbeleid:** Geef hier het maximum qua bestellen in. 
8. Klik op de actie **Speciale prijzen instellen**. Geef de inkoopprijs per leverancier op. 

### Scanbaar maken van artikel

Om een artikel scanbaar te maken voor de vakmannen is het nodig om een barcode aan het artikel te koppelen.

 1. List item
 2. Navigeer via het Lint naar **Kruisverwijzingen**. Vul de volgende velden:
	* **Kruisverwijzingssoort:** Kies hier voor **Barcode**. 
	* **Kruisverwijzingsnr.:** Geef hier het nummer van de barcode in. 

### Stock Keeping Unit (SKU) aanmaken
In de basis maak je voor elke vestiging een SKU aan. 

10. Navigeer via het Lint naar **SKU maken**.
11. Geef in het filter **Maken per** aan dat het gaat om 'per vestiging'. 
12. Klik op **OK**. De SKU's worden per vestiging aangemaakt. 



<hr>

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkzNTk3NTUyLC03MzYzODYwOTZdfQ==
-->