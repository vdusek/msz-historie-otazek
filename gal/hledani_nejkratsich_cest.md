### Hledání nejkratších cest ze zdrojového uzlu do všech ostatních uzlů grafu (Bellman-Fordův algoritmus, Dijkstrův algoritmus).

----------------------------------------

- Rok: 2021
- Zkoušel: Křivka Zbyněk, Ing., Ph.D.
- Známka: A
- Komentář: Orientované grafy v zátvorke silná súvislosť a Dijskstra, pýtal sa tiež na to ako je to so súvislosťou a chcel počuť, že Dijsktra nie je vhodný pre záporné ohodnotenie hrán.

----------------------------------------

- Rok: 2021
- Zkoušel: Kolář Dušan, doc. Dr. Ing.
- Známka: D
- Komentář: Dijstra a úvod do problematiky.

----------------------------------------

- Rok: 2021
- Zkoušel: Smrž Pavel, doc. RNDr., Ph.D.
- Známka: C
- Komentář: Orientované grafy: Začal som definíciou. To bolo OK. Potom zrazu chcel popísať algoritmus Floyd-Warshala. Povedal som čo robí, pre aké uzly (aj s kontrastom oproti Dijkstru). Dodal že som zabudol niečo definovať. Pozeral som sa na ňho nechápavo, veď som povedal všetko. Potom naznačil, že hrany by mali niečo mať. Doplnil som že ohodnotenie. Potom bola otázka na zložitosť, ktorú som zároveň vysvetlil aj na kóde (3 zanorené cykli a výpočet D[i][j]). Myslím že bez chyby aj keď poznamenal že n^(2,8) je presnejšie. A dodal som že funguje aj so záporným ohodnotením hrán, čo Dijkstra nie. Na to sa ma spýtal prečo Dijkstra nevie pracovať so zápornými hranami? Ale dodal, že on si myslí, že by mohol (WTF). Pokúšal som sa na to na mieste prísť a myslím že som nebol ďaleko od pravdy, nakoniec povedal, že problém je so zápornými kružnicami.

----------------------------------------

- Rok: 2020
- Zkoušel: Čadík Martin, doc. Ing., Ph.D.
- Známka: A
- Komentář: Orientované grafy: obecný úvod, jaké používáme reprezentace orientovaných grafů v algoritmech (zmínil jsem seznamy sousednosti a matice), pak pojmy jako orientovaný sled, orientovaný tah, co to je Eulerův a Hamiltonovský graf, souvislost a silná souvislost. Nakonec jsme se dostali k Dijkstrovu algoritmu (popsat na příkladu inicializaci, jak funguje, složitost, čím se liší od Floyd-Warshalla - hledáme nejkratší cesty mezi konkrétním uzlem "A" a zbylými uzly v grafu) a pak ještě zhruba ukázat jak funguje Floyd-Warshall (nakreslit matici a vysvětlit proč je to O(n^3) - pro všechny dvojice uzlů zkoušíme postupně vést cestu přes každý další uzel v grafu).

----------------------------------------

- Rok: 2020
- Zkoušel: Čadík Martin, doc. Ing., Ph.D.
- Známka: C
- Komentář: Neorientované grafy, popsat co to je, jak se to reprezentuje v PC (matice sousedů či co), tah, cesta, sled, souvislost, Kruskal a Prim. Stačilo neformálně na obrázku, na lepší známku by to chtělo popsat více matematicky, C.

----------------------------------------

- Rok: 2020
- Zkoušel: Burget Lukáš, doc. Ing., Ph.D.
- Známka: A
- Komentář: Dijkstra a F-W - k čemu to je, popsat oba algoritmy jak fungují.

----------------------------------------

- Rok: 2020
- Zkoušel: Češka Milan, RNDr., Ph.D.
- Známka: A
- Komentář: Orientované grafy -- silně souvislá komponenta, hledání minimální cesty. Neformálně jsem popsal orientované grafy, potom jsem popsal silnou souvislost ale asi ne moc dobře, tak jsem měl nakreslit nesouvislý graf a potom souvislý graf a potom silně souvislý graf. Potom jsme řešili složitost hledání silně souvislé komponenty a jak bych to implementoval. Řekl jsem, že bych prohledával všechny možné cesty pro každý uzel, algoritmus BFS a polynomiální složitost. Správně to bylo DFS a chtěl jakou přesně to má složitost. Myslím že jsem nakonec řekl kvadratickou ale asi to jde efektivněji. Potom chtěl popsat Dijkstra algoritmus, potom co jsem to popsal tak se zeptal jaké znám další algoritmy. Řekl jsem Floyd-Warshall ale chtěl slyšet Bellman-Ford ale nevadilo mu to. Stačilo jenom říct jaké má vlastnosti.

----------------------------------------
