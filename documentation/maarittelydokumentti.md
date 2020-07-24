# Määrittelydokumentti

## Sovelluksen tarkoitus

Sovelluksen tarkoitus on verrata reittihakualgortimien tehokkuutta.
Aluksi toteutan Dijkstran ja  A* algoritmit ja vertailen näiden tehokkuutta.
Jos aika riitää, lisään joko Bellmanin ja Fordin algoritmin tai Floyd ja Warshallin algoritmin,

## Algoritmit ja tietorakenteet

Käytän Dijkstran ja A* algoritmejä.
Ensimmäinen käyttää tietorankenteena minimikekoa.
Jälkimmäisessä käytetään myös minimikekoa sekä sen lisäksi heuristiikkafunktiota.

## Syötteet

Ohjelma saa syötteenä 2-ulotteisen taulukon. 
Kartta ajatellaan verkkona, missä ruudut ovat verkon solmuja

## Aikavaativuudet

Dikkstran algoritmin aikavaatimus on O(n + m log n) ja A* algoritmin aikavaatimus on O(n).
n on solmujen lkm ja m on kaarien lukumäärä.

## Lähteet

Tietorakenteet ja Algoritmit kirja (Antti Laaksonen 2020)

[Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm) Wikipedia

[Introduction to A*](http://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html)

[Kartat](https://www.movingai.com/benchmarks/grids.html)
