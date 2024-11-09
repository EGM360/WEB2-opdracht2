#### Opdracht 2

#### Instructies
1. Stel document root in op _YOUR_PROJECT/public_, op die manier wordt de site geladen vanaf _public/index.php_
   * Je moet alle andere bestanden opnemen/vereisen in _index.php_, dat is het hoofdbestand
   * APP_PATH, FILES_PATH & VIEWS_PATH zijn constanten die zijn gedefinieerd in _index.php_ om te helpen bij het openen en verwerken van de bestanden
2. De hoofdcode zou in de app-map moeten staan. Er is een App.php gemaakt.
   * U dient daar meerdere functies te definiëren die **alle** bestanden in de _transaction_files_ directory zullen lezen en verwerken. Het is aan jou hoe je die bestanden wilt lezen, maar het doel is om alle bestanden in die map te lezen
   * Alle bestanden in de directory zijn.csv-bestanden.
3. Sla gegevens op in een array
   * Eerste kolom is de datum van de transactie
   * Tweede kolom is het vinkje # dat optioneel is
   * De derde kolom is transactiebeschrijving
   * De vierde kolom is het bedrag (negatief getal geeft aan dat het een uitgave is, positief getal geeft aan dat het een inkomen is)
4. Bereken het totale inkomen, de totale kosten en het netto totaal (totale inkomsten - totale kosten)
5. Maak een eenvoudige HTML-tabel aaan met alle gegevens uit de bestanden
   * Het html-skelet wordt geleverd in het bestand views/transactions.php
   * De datum van de transactie moet in dit formaat "4 januari 2021" zijn
   * Toon inkomensbedragen in groene kleur & toon uitgavenbedragen in rood
6. Maak gebruik van Bootstrap om er een mooi geheel van te maken.
