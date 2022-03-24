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

### [Als klant wil ik items van mijn bestelling kunnen halen zodat wanneer ik mijn gedachten verander tijdens het bestellen, mijn bestelling nog kan aanpassen.](https://github.com/nelisriebezos/planning-repo/issues/14)
Domein model: <br>
![Userstory 14](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/domeinmodel/US14_ClassDiagram.png) <br>
Beschrijving: <br>
Het moet mogelijk zijn om tijdens het bestellen een item van de bestellijst te verwijderen om te voorkomen dat klanten items bestellen die ze toch niet will of perongeluk aangeklikt hebbem.

|Vertalingstabel| |
|-----|-----|
|OrderList | Bestellingslijst |
|OrderItem | Bestellingsonderdeel |
|Amount | Hoeveelheid |
|MenuItem | Menu onderdeel |
|Name | Naam |
|RemoveItem | Verwijder onderdeel |

### [Als klant wil ik een bestelling kunnen annuleren, als er nog niet gestart is aan de bereiding, zodat ik geen ongewenste bestellingen krijg.]
(ttps://github.com/nelisriebezos/planning-repo/issues/10)
Domein model: <br>
![Userstory 10](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/domeinmodel/US10_ClassDiagram.png) <br>
Beschrijving: <br>
Het moet mogelijk zijn om een bestelling te annuleren als de bestelling nog niet verwerkt wordt.
|Vertalingstabel| |
|-----|-----|
|Orderstatus | Bestellingstatus |


### [Als klant wil ik allergeneninformatie kunnen lezen zodat ik niet gerechten bestel waarvoor ik een allergie heb.](https://github.com/nelisriebezos/planning-repo/issues/17)
Domein model: <br>
**N.V.T** <br>
Beschrijving: <br>
Van elk menu item moet de informatie omtrent allergenen getoont worden zodat klanten met een allergie weten welke menu items ze kunnen bestellen.
