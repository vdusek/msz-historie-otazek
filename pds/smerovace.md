### Základní funkce směrovače, zpracování paketů ve směrovači, typy přepínání a architektur.

----------------------------------------

- Rok: 2021
- Zkoušel: Matoušek Petr, Ing., Ph.D., M.A.
- Známka: D
- Komentář: Co se deje v rychle ceste a co v pomale, ptal se co ktera cesta provadi s paketem, trochu sem vahal a pak sem rikal ze pomala děla trochu fragmentaci pri ruznem MTU, zabaluje provoz do VPN, pak sem rekl ze rychla dela sifrovani a pry ne (v hlavě sem si rikal hmm napad pro vylepšení :D), na to jeste dodal ze to dela nat atd.

----------------------------------------

- Rok: 2020
- Zkoušel: Polčák Libor, Ing., Ph.D.
- Známka: A
- Komentář: Architektura směrovačů - zde jsem na tabuli nakreslil to obecne schema, jake jsou tam tabulky a jake zaznamy v techto tabulkach najdeme. Pak se Polčák zeptal na to jak by to asi fungovalo v praxi (napr. jak ten paket prochazi siti), ale to byly asi spise takove rozsirujici otazky, myslim ze obecne veci co jsou v prednaskach uplne staci.

----------------------------------------

- Rok: 2020
- Zkoušel: Grégr Matěj, Ing., Ph.D.
- Známka: A
- Komentář: Směrovače - chtěl prinicip směrovačů, co se děje s paketem při příchodu do zařízení, jaké jsou architektury směrovačů (control plane, data plane).

----------------------------------------

- Rok: 2018
- Zkoušel: Veselý Vladimír, Ing. Ph.D
- Známka: E
- Komentář: Základní funkce směrovače - chtěl vrstvu na které pracuje, obsah směrovací tabulky a libovolnou architekturu. Tahal to ze mě co se dalo a nakonec to stačilo. Od obou zkoušejících skvělý přístup.

----------------------------------------

- Rok: 2020
- Zkoušel: Grégr Matěj, Ing., Ph.D.
- Známka: B
- Komentář: Funkce směrovače, zpracování paketů. Tohoto jsem se bál, protože jsem si moc nepamatoval, jak to tam vlastně funguje, ale bylo to spíš ve stylu otázka-odpověď. Začali jsem tím, co za zařízení je směrovač, co se tam děje s paketem (zpracování L2 a L3 hlaviček, z vstupu na výstup...) a pak jsme se motali kolem toho, podle čeho ví, kam dál poslat paket, co se děje s L2 hlavičkou (MAC adresa zkontrlována a zahozena) a pak jsme se motali kolem L3 hlavičky, co všechno se v ní dá zpracovat a jak to je s kontrlním součtem u ipv6. Fajn zkoušení, místama jsem si nebyl jistý se svojima odpověďma, ale Grégr vypadal spokojeně s touto diskuzí ve stylu otázka/odpověď.

----------------------------------------

- Rok: 2018
- Zkoušel: Veselý Vladimír, Ing. Ph.D
- Známka: A
- Komentář: Pan doktor Veselý působil příjemně a začal otázku tak, že se zeptal, co se tedy vlastně stane s paketem, když přijde na směrovač. Tak jsem tedy popsal stručně části zpracování - co se děje na vstupním rozhraní, co se musí ověřit, kam se to ukládá, kam se to přenáší, co se tam dále s paketem děje a tak a popsal jsem kontext paketu - po mém monologu mi pan doktor řekl, že to zní dobře, ale jedna věc se mu nelíbila (uvedl jsem, že se paket přesměruje na základě přepínací tabulky) a tak jsme se dostali, jaké ty tabulky vlastně na tom routeru jsou. Popsal jsem mu směrovací tabulku, která leží u CPU a co v ní je (podle slidů). U toho mě pan doktor přerušil a zeptal se mne, jaké další položky se tam dále vyskytují. Zmínil jsem, že například metrika a byla položena další otázka: k čemu ta metrika vlastně je. Tak jsem řekl něco ve smyslu, že je to ohodnocení cesty k tomu dalšímu hopu (routeru) a že mne zajímají cesty s nejlepší (nejmenší) metrikou. Doplňující otázka pak byla, že kdybych měl více záznamů se stejnou metrikou, ale jeden například přes RIP a druhej přes OSPF, tak jak bych rozhodl, který použít. Řekl jsem, že kdybych měl zodpovědět, tak bych si vymýšlel, ale zvolil bych si OSPF. To se panu doktorovi líbilo a řekl, že obecně záleží na implementaci, ale volba je to dobrá. Pak chtěl slyšet, když už jsme mluvili o tom, co je u CPU, co se stane, když je TTL = 0. Tak jsem řekl, že je paket zpracován u CPU, aby mohla být odeslána ICMP odpověd. Zeptal se co dalšího se zpracovává na CPU: uvedl jsem ještě ARP a směrovací protokoly a pak jsem na výzvu další střelil QoS - QoS už se nelíbil. Mám pocit, že mezitím zazvonil budík, ale jeli jsme dál. Ještě se zeptal, jaký jsou teda ty možnosti přepínání, tak jsem zmínil tu se společným procesorem, že je to pomalý, protože to jede přes CPU, ale že když tam dáme cache, tak to pak nemusí jít přes CPU. Na to se zeptal, co je v tý cache, tak jsem řekl, že MAC adresa vstupního rozhraní a výstupního rozhraní a síť (nebo něco v tom smyslu), s tím byl pan doktor spokojený a neměl již další otázky.

----------------------------------------

- Rok: 2018
- Zkoušel: Veselý Vladimír, Ing. Ph.D
- Známka: A
- Komentář: Na papieriku bolo niekoľko podotázok, ale začal som tou prvou a to je cesta paketu cez smerovač. Tak som to popísal, že to ide cez vstupne rozhranie, kde prebieha kontrola checksumov (opýtal sa ma čo sa stane ak checksum nesedí -> zahodí sa) a hlavičiek L2, L3, TTL a vytvorí sa kontext paketu. Odtiaľ to ide do forwarding enginu, používa sa forwarding tabuľka (spýtal sa ma čo tam je -> prefix siete, výstupné rozhranie a MAC adresa), backplane, queue manager, traffic manager (opýtal sa ma čo znamená policing a shaping) a výstupné rozhranie. Nakoniec sme sa bavili o tom čo je v routing tabuľke (prefix siete, adresa next hopu a metrika, metrika buďto na základe hop countu alebo vzdialenosti). Tie podotázky čo som tu popísal v zátvorkách som len cca tušil, ale nikdy som to nevedel naisto. Keď však stále prikyvoval tak som si hovoril v hlave, že dobre tipujem. Nakoniec ešte chcel počuť rozdiel medzi slow path a fast path a šiel som von.

----------------------------------------

- Rok: 2012
- Zkoušel: Matoušek Petr, Ing., Ph.D., M.A.
- Známka: E
- Komentář: "Popište co je to směrovač, vyberte si jednu architekturu a tu popište." Začal jsem tak nějak obecně, něco jsem odříkal, sem tam něco doplnil. Pak jsme se dostali na to, co je to kontext a tady mě začal dusit na to co všechno obsahuje. Něco jsem řekl, ale nevzpomněl jsem si na všechno. Zkoušel jsem to okecávat ze všech stran, ale nenapověděl ani slovíčkem. Klečel na mně s otázkou, co ještě to obsahuje. Následovala chvilka trapného ticha, načež mi to pověděl. Pak se ještě zeptal na pomalé a rychlé zpracování paketů - to jsem nějak popsal, ale taky jsem si nebyl moc jistej a místama mě musel doplnit. Následovalo něco ve stylu "Já myslím, že to stačilo. Dál už se ptát nebudu."

----------------------------------------
