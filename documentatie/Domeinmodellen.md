[<-- terug](https://github.com/nelisriebezos/planning-repo/tree/main/documentatie)
# Domein model
In dit hoofdstuk lichten we toe hoe onze userstories worden vertaald naar code.

## User stories
Link naar de domein klassen: [Domein klassen]()

### [Als klant wil ik een item op mijn bestellijst kunnen zetten zodat ik mijn bestellingen goed kan overzien.](https://github.com/nelisriebezos/planning-repo/issues/8)
Domein model: <br>
![Userstory 8](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/domeinmodel/US8_ClassDiagram.png)
<br>
Beschrijving: <br>
Een klant moet een item op zijn / haar bestellijst kunnen zetten zodat hij / zij een duidelijk overzicht heeft van wat hij /zij gaat bestellen.

|Vertalingstabel| |
|-----|-----|
|OrderList | Bestellingslijst |
|Additem | Voeg item toe |
|OrderItem | Bestellingsonderdeel |
|Amount | Hoeveelheid |
|MenuItem | Menu onderdeel |
|Name | naam |

### [Als klant wil ik een qr code kunnen scannen zodat ik het menu kan zien.](https://github.com/nelisriebezos/planning-repo/issues/9)
Domein model: <br>
-
Beschrijving: <br>
Een klant moet een qr code kunnen scannen, wanneer die qr code gescand is moet de klant op de website komen waar hij/zij het menu kan zien.


### [Als klant wil ik mijn bestellijst in kunnen zien zodat ik een overzicht heb van wat ik heb besteld en hoe duur het was.](https://github.com/nelisriebezos/planning-repo/issues/16)
Domein mode: <br>
![Userstory 16](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/domeinmodel/US16_ClassDiagram.png)
<br>
Beschrijving: <br>
Bestellingen zijn opgedeeld in rondes, zodat een klant kan bijbestellen voordat hij / zij gaat betalen. KLanten kunnen een overzicht opvragen van de bestellingen die zij gemaakt hebben. Dit is een lijst met alle rondes daarin. De rondes bevatten de prijs per product, per ronde. Ook word de totaal prijs getoond.

|Vertalingstabel| |
|-----|-----|
|Visit | Bezoek |
|TableNumber | Tafelnummer |
|StartTime | Starttijd |
|CalculatePrice | Bereken prijs |
|OrderList | Bestellingslijst |
|OrderItem | Bestellingsonderdeel |
|Amount | Hoeveelheid |
|MenuItem | Menu onderdeel |
|Name | Naam |
|Price | Prijs |
