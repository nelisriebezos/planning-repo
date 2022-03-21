[<-- terug](https://github.com/nelisriebezos/planning-repo/tree/main/documentatie)

# Toestandsdiagrammen
In dit hoofdstuk staan alle toestandsdiagrammen met daaronder een toelichting.

## [Category toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/Categorie.png)
![Category toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/Categorie.png)<br>
Een categorie kan aangemaakt worden door een admin. De categorie kan tussendoor veranderd worden door de naam en/of de beschrijving aan te passen. Een categorie heeft geen toestand meer als het verwijderd is.

## [Location toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/location.png)
![Location toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/location.png)<br>
Een locatie kan aangemaakt worden door een admin. Een admin kiest dan waar een gerecht bereid wordt. Vervolgens zou het kunnen dat de locatie veranderd, daarom kan een admin een locatie veranderen. Een locatie heeft geen toestand meer als het verwijderd is.

## [menuItem toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/menuItem.png)
![menuItem toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/menuItem.png)<br>
Een menuItem begint wanneer deze wordt toegevoegd door de administrator. Een adinistrator kan een menuItem aanpassen, maar dit veranderd de toestand niet. Een administrator kan een menuItem publishen, hierdoor veranderd de toestand naar 'publishedState'. Ook kan een menuItem unpublished gemaakt worden, waardoor hij terug veranderd naar initalState. Een menuItem kan vanuit elke toestand worden verwijderd.

## [orderItem toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/orderItem.png)
![orderItem toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/orderItem.png)<br>
Een klant plaatst een order, hierdoor wordt een order aangemaakt. Wanneer een klant afrekent wordt het verwijderd.

## [orderList toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/orderlist.png)
![orderList toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/orderlist.png)<br>
Een klant doet een bestelling waardoor een order aangemaakt word, een order kan worden afgerekend of geannuleerd daarna heeft de order geen toestand meer.

## [visitor toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/visitor.png)
![visitor toestandsdiagram](https://github.com/nelisriebezos/planning-repo/blob/main/documentatie/toestandsdiagram/visitor.png)<br>
Een visit begint wanneer een klant een bestelling doet, tijdens de visit kan het tafelnummer worden gewijzigd. Een visit eindigt en is toestandloos wanneer er is afgerekend.
