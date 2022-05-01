### Hašovací funkce, klíčovaný haš a MAC a jejich použití a vlastnosti.

----------------------------------------

- Rok: 2021
- Otázka: Hašovací funkce, klíčovaný haš a MAC a jejich použití a vlastnosti
- Zkoušel: Drábek Vladimír, doc. Ing., CSc.
- Známka: A
- Komentář: Povidal jsem asi 5 minut sam, vsechny podminky, vlastnosti, MDC, MAC, nakreslil schema se sym. sifrou a pak se me zeptal jaka ta funkce je, coz jsem moc nechapal tak jsem rikal ze treba DES je ta sym. sifra, aby to bylo rychle, a on porad jaka ta funkce je, pak jestli algebraicka nebo jaka tak rikam ano, pak mi trochu pomohl doc. Hanacek ze je to ta kompresni iterovana funkce a rikal jsem, ze redukuje informaci a jeste jsem dorekl druhy, avalanche efekt a slo se dal.

----------------------------------------

- Rok: 2018
- Otázka: Hašovací funkce, klíčovaný haš a MAC a jejich použití a vlastnosti
- Zkoušel: Hanáček Petr, doc. Dr. Ing.
- Známka: A
- Komentář: Začal jsem takové obecné kecy a rychle se přesunul na požadavky/vlastnosti, které chceme aby hashovací funkce měla. Popsal jsem First Preimage, Second Preimage a Collision Resistance. Pak jsme docela dlouho zůstali viset na rozdílu mezi second preimage a collision resistance. Celkově se mi pan docent snažil naznačit, jak mám mezi nimi tedy určit ten rozdíl. Ptal se mne pak jak je to s útoky, tak jsem zmínil, že je zde Birthday paradox, a uvedl jsem, že na 160 bitech stačí typicky projít 2^80 možností než dojdu ke kolizi. Na to myslím, námitky nebyly a přesunuli jsme se ke klíčovanému haši. Někde na začátku zazvonil budík, ale jeli jsme dál. Řekl jsem, že tam je ten klíč, a řekl jsem, že jsme si uvedli některé typy použití, ale nejvýznamnější je HMAC. Zeptal jsem se, zda jej chce popsat, což nechtěl. Načež byl dotaz -- K čemu ten klíčovaný hash slouží, tak jsem řekl že autentizaci. S tím pan docent souhlasil. Zeptal se mne, že co to znamená pro útočníka z hlediska bezpečnosti, tak jsem řekl, že je to pro něj horší, protože nezná klíč, což sice částečně potvrdil, ale chtěl pak ještě něco, ale to už si napamatuji a nevěděl jsem to.

----------------------------------------

- Rok: 2018
- Otázka: Hašovací funkce, klíčovaný haš a MAC a jejich použití a vlastnosti
- Zkoušel: Hanáček Petr, doc. Dr. Ing.
- Známka: B
- Komentář: Prvně jsem uvedl co je hašovací funkce (základní definice, first preimage resistance, second preimage resistance, collision resistance). P. Hanáček se následně začal doptávat na vztah mezi second preimage resistance a collision resistance včetně potřebné síly útoku. Kolem tohoto tématu jsme se točili asi další 2 minuty. Následně se P. Hanáček dotázal na klíčovaný haš a MAC, což jsem obecně popsal. Zmínil jsem také jakým způsobem se klíč přidává ke zprávě a částečně jsem popsal HMAC. Následně se P. Hanáček zeptal, k čemu je klíčovaný haš dobrý - uvedl jsem, že zajišťuje integritu dat a autentizaci, což se při neklíčovaných hašovacích funkcí musí zajistit například podpisem pomocí asymetrické šifry. Tím také zkoušení skončilo. Trvalo 5-6 minut. Přestože, jsem byl na tuto otázku připraven, nebylo zkoušení moc příjemné a P. Hanáček mě občas dokázal docela znejistit.

----------------------------------------

- Rok: 2015
- Otázka: Hašovací funkce, klíčovaný haš, MAC
- Zkoušel: Hanáček Petr, doc. Dr. Ing.
- Známka: E
- Komentář: Začal jsem tím, co je to hašovací funkce, jaké jsou na ní kladené podmínky (preimage resistance, ...). Tam mě Hanáček přerušil a začal se ptát, kolik pokusů musí útočník vyzkoušet při útoku hrubou silou, aby pokořil každou z těch podmínek. Úplně jsem se do toho zamotal, rozklepal jsem se a nebyl schopen kloudného slova. Hanáčkův poker face v tom taky nijak nepomáhal, ale asi se snažil nějak pomoct (To n značí prostor vstupních dat? Jak chcete, jen se ptám.), a ačkoli jsem to věděl, nebyl jsem v tu chvíli schopen formulovat odpověď. Nechal mě v tom ještě hodnou chvíli koupat a pak to ukončil.

----------------------------------------

- Rok: 2014
- Otázka: Hašovací funkce, klíčovaný haš a MAC a jejich použití a vlastnosti
- Zkoušel: Hanáček Petr, doc. Dr. Ing.
- Známka: E
- Komentář: Co jsem k tomu rekl(a)/na co se ptali/co mne vytkli: Ptal se na MAC, říkal jsem že slouží pro podpis a začal jmenovat ty 3 potřebné podmínky pro hash.funkce. Tím sem si sám naběhl, protože jsem zapomněl 2nd preimage. Na to, co jsem místo toho "vyvařil", řekl, že to je ale 1st preimage, a chtěl to vědět správně, nakonec to musel říct za mě. Dál se ptal na sílu hashe, takové to, co bylo i letos na zkoušce, že pro útok vůči collision resistance je složitost 2^80 i když hash má délku 2^160. Patlal jsem se v tom, tak nakonec chtěl přesně vědět jak se na každou věc útočí a jakou složitost to bude mít.

----------------------------------------

- Rok: 2013
- Otázka: Haš, klíčovaný haš, HMAC
- Zkoušel: Hanáček Petr, doc. Dr. Ing.
- Známka: E
- Komentář: Zacal jsem definici hasovaci funkce, ten slajd, pak padla otázka klíčovaný has, tak zas definice co to je a tak. Potom chtěl vědět útoky a složitost útoku a jeho pravděpodobnost. K tomu jsme se s jeho značnou pomocí úspěšně dobrali. Dost pomáhal.

----------------------------------------
