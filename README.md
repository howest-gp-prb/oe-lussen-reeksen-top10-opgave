# oe-lussen-reeksen-top10-opgave

## Opgave
Schrijf een applicatie waar je jouw top 10's kan bijhouden voor bepaalde categorieën.
Zorg er dus zeker voor dat de lijst maximaal 10 items kan bevatten!

De gebruiker selecteert een categorie in een ComboBox waarna de top 10 ervan wordt weergeven. Selecteer hij iets anders, dan wordt de andere categorie mét de ingevoerde waardes getoond.

![example](img/top10.gif)

## Aandachtspunten
* De categorieën worden __hardgecodeerd__. Dit wil zeggen dat je ze letterlijk vastlegt in je code. Indien je een array gebruikt, lees je dus iets zoals:
```
categories = new string[6] { 
                "Movies", 
                "Music albums",
                "Series",
                "Computer games",
                "Board games",
                "Books"
            };
```

* Schrijf een __methode__ die een getal retourneert met het aantal top 10 items voor de categorie.
Toon vervolgens in `lblNumberOfItems` hoeveel items er werden toegevoegd aan de top 10. Bv.:
```
2/10
```
* Voor deze oefening heb je een array van `List` nodig.
* Maak gebruik van een klassevariabele `MaxItems` die het maximale aantal items bijhoudt (dat is hier 10). Aangezien deze waarde tijdens het uitvoeren van je programma nooit zal veranderen, kan je die op de volgende manier declareren: 
```
//Hierbij staat de const voor constante (iets dat niet kan veranderen).
const int MaxItems = 10;
```
* Voorzie code die de gebruiker op de hoogte stelt van foutieve ingave.

