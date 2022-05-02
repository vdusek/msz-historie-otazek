### Symetrická kryptografie. Vlastnosti, vlastnosti bezpečného algoritmu, délka klíče, útok silou, příklady symetrických algoritmů, Feistelovy šifry, DES, režimy činnosti, proudové šifry.

----------------------------------------

- Rok: 2021
- Zkoušel: Malinka Kamil, Mgr., Ph.D.
- Známka: A
- Komentář: Symetrická kryptografia, jej vlastnosti, podrobne popísať AES, reverzibilitu jeho operácií, ako sa generuje Ki (to som úplne nevedel, vraj sú tam interné SBOXy a podobne), počet iterácií pre 128 a 256b kľúč, popísať rozdiely OFB a CFB, ako sa v nich progaguje chyba a za koľko iterácií a ktorá z nich je schopná sa samosynchronizovať.

----------------------------------------

- Rok: 2021
- Zkoušel: Malinka Kamil, Mgr., Ph.D.
- Známka: F
- Komentář: Symetrická kryptografie (AES, 3DES), ptal se nejdřív obecně, na Avalanche effect, v podstatě celé se to točilo kolem AES, dál jsme se nedostali, ptal se kolik kol má AES, jednotlivé operace, shiftrows jsem popsal, chtěl vědět mixcolumns, to jsem nevěděl, rozhodně se nedá říct, že by pomáhal, pak to skončil, že prý mu to stačí... Byl jsem dost nasraný a stále jsem, rozhodně když jsem odcházel z místnosti, tak jsem měl pocit, že jsem toho řekl docela dost aspoň na to E...

----------------------------------------

- Rok: 2021
- Zkoušel: Malinka Kamil, Mgr., Ph.D.
- Známka: E
- Komentář: Na papieriku bilo špecifikované konkrétne zameranie na blokové a prúdové šifry. Začal som klasicky základmi. Čo je to, čo zaručuje. Potom povedal Malinka, že "toto môžme preskočiť, to každý vie". A začal sa ma pýtat rovno na blokové šifry. Myslím že hneď bola prvá otázka na to, že prečo nechceme aby sa bloky šifrovali nezávisle. Snažil som sa na to dôjsť ale už ani sám netuším, či som sa dopracoval k správnemu výsledku. Potom sme prešli na CBC. To som nakreslil na tabulu správne a zbežne popísal. Potom sa ma spýtal ako prebieha dešifrovanie - opačné poradie subkľúčov, čo ale NESTAČILO. Tak som povedal, že na vstupy kde normálne ide message privediem cipher. To ale bolo zle, tak som sa trochu zamyslel, a nahlas rozmýšľal. Nakoniec som sa dopracoval k správnemu výsledku a to že výstupy, z kadiaľ nám ide šifra, sú pri dešifrovaní vstupy. A potom sa ma začal pýtať, čo sa stane keď nastane chyba v jednom bite pri šifrovaní. To som sa snažil tiež odvodiť ale už som sa začínal zamotávať. Nepovedal som to správne ale nakoniec sme sa spoločne dostali k výsledku. A ani som si neuvedomil a zrazu sa ma zrejme pýtal na dešifrovanie ale myslel, že chcel to ešte raz zopakovať ucelené. Takže som to zopakoval. No ale odpoveď na jeho otázku to bolo nesprávna. Takže zase sme sa snažili spoločne dostať k tomu ale už som sa zamotával viac a viac. Skúšanie bolo v pohode ale väčšinou sa pýtal podla mňa na úplne detaily ktoré som čakal, že komisia pýta keď sa nevedia rozhodnúť medzi A a B. Ale OMYL dostal som E s tým že mali k tomu nejaké poznámky a neviem či mi nechceli dat F.

----------------------------------------

- Rok: 2021
- Zkoušel: Malinka Kamil, Mgr., Ph.D.
- Známka: B
- Komentář: Na papírku bylo: "Symetrická kryptografie - 3DES, proudové šifry". Chtěl jsem začít obecně o symetrické kryptografii no Malinka mě zastavil, že ať jdu rovnou na 3DES. Tak jsem začal že to je 3x DES a tím se dostal k DESu, řekl jsem, že má 16 kol a základem každého kola je v podstatě Feistelova šifra - tu jsem nakreslil na tabuli a řekl co musí splňovat ta funkce (aby to fungovalo nic - může to být i jednocestná funkce, aby to bylo bezpečné musí skrývat vlastnosti klíče a plaintextu). No zas mě vrátil k 3DES ať nakreslím schéma... tak jsem nakreslil tři obdélníčky za sebou spojený a do každého šel zvlášť klíč (vlastně stačí jen dva klíče a šifruje se na střídačku, ale nechal mě u těch tří). Pak se ptal, že jestli je to optimální zapojení a jestli to nejde jinak. Nic jinýho mě nenapadlo, tak jsem řekl, že nevím a on že jsou režimy jako např. EDE (jakože napřeskáčku Encryption a Decryption jiným klíčem a že jsou různé kombinace). Budík už zazvonil tak před minutou, no ještě po mně chtěl nakreslit PRNG s polynomem x^4+x+1 (já nakreslil XOR i k té jedničce úplně napravo, tak to mě opravil, ale jinak mu to stačilo.

----------------------------------------
