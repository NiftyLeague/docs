---
id: šikovní rozbíječi
title: Šikovní Smashers
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Váš prohlížeč nepodporuje značku videa.
  </video>
  </div>

---

# **Obecné informace**

Připravte se na rvačku! Lokální multiplayerová verze **[Nifty Smashers](https://nifty-league.com/games)** byla zpřístupněna ihned po uvedení na trh a následovala online hra pro více hráčů.

Vybojujte si to mezi komunitou a dostaňte na své přátele co nejvíce bat bonks! Nifty Smashers se inspiruje klasickou hrou Super Smash Bros, jejímž cílem je srazit vaše protivníky z mapy a získat body.

Můžete hrát pomocí klávesnice nebo jakéhokoli jiného kompatibilního ovladače (Playstation, Xbox atd.). Vstupte do herní lobby a vyberte si DEGEN pro bitvu.

## Bodování

- Pokud je DEGEN zasažen jednou a zemře (spadne z mapy), získáte 1 bod.
- Pokud je DEGEN zasažen vícekrát, aniž byste se mohli zotavit, získáváte body tak často, jak často byl zasažen DEGEN (bez ohledu na to, zda předchozí zásahy provedl jiný DEGEN – takže přiložte poslední mega-bonk, abyste je trefili z mapy a vyzkoušejte si všechny body za kolo).
- Čím více je váš soupeř postupně bonkován, tím rychleji se odráží a tím více bodů za bonking získáte.
- Poslední zásah, který zabije DEGEN, získá všechny combo body.
- V současné době neexistuje žádný limit, jak často lze DEGEN zasáhnout (kombinovat), ale existuje limit pro počet bodů, které můžete získat (max 3 body: zápas 2 hráčů / max 5 bodů: 3&zápas 4 hráčů ).
- Zápas 2 hráčů vyžaduje 5 bodů k vítězství v kole.
- 3 & zápasů pro 4 hráče vyžaduje k vítězství v kole 10 bodů.
- Zápasy jsou nejlepší z 5 kol.
- Pokud je po 5. kole nerozhodný stav, hráči s nerozhodným výsledkem se přesunou do kola náhlé smrti, které mohou ostatní hráči sledovat z postranní čáry.

## Zpoždění

- Indikátor zpoždění ukazuje zpoždění (rychlost pingu) vašeho připojení.
- Prodleva typicky ukazuje, že rychlost pingu je vyšší než 100 ms.
- Obecně řečeno, zpoždění je vždy přítomno, kdykoli existuje fyzická vzdálenost mezi hráči na internetu. Čím větší vzdálenost, tím větší zpoždění.
- Existují různé techniky, které vývojáři používají ke kompenzaci a skrytí zpoždění.
- Implementovali jsme řadu těchto technik kompenzace zpoždění, které zakrývají zpoždění pro nejlepší možný zážitek.
- Začlenili jsme také řešení se servery po celém světě, abychom mohli porovnávat hráče, kteří jsou si nejblíže, abychom co nejvíce minimalizovali zpoždění. Máte-li zájem dozvědět se více o těchto technikách, podívejte se na [tento příspěvek](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) , který milujeme na Kompenzaci zpoždění od Gabriela Gambetty.

## Vlastní lobby

- Vlastní lobby lze použít k otevření zápasu ve zvolené oblasti. Tvůrce lobby může vidět kód na mapě lobby, který lze sdílet s ostatními.
- Pokud se do lobby chce připojit další degen, musí nejprve vybrat správný region a poté zadat kód lobby do vstupního pole.
- Při použití vlastního kódu lobby by se region měl přepnout automaticky.

## Změna regionů

- Smasher je rychlá hra, kde je rozhodující latence/ping. Čím blíže je vybraný region k umístění hráče, tím nižší je ping.
- Po změně regionu v aplikaci Web-GL nebo Desktop App se zobrazí aktuální ping.

# **Základy bitvy**

## Obecná rada

- Důrazně doporučujeme hrát s ovladačem (Playstation, Xbox nebo jakýkoli jiný ovladač, který váš PC/Mac rozpozná).

## Netopýr se houpe

- Pálkou lze houpat všemi možnými směry: doleva, doprava, nahoru, dolů, úhlopříčky.
- Pálkou lze máchnout kliknutím na tlačítko útoku.
- Delší stisk tlačítka způsobí, že pálka zasáhne tvrději.
- Pálkou lze houpat ve stoje, běhu nebo skákání.
- Hráči mohou během skoků dlouze stisknout útočné tlačítko - to je obvykle dobrý způsob, jak překvapit soupeře.

## Stěhování

- Ve 2D hře jsou směry pohybu vlevo/vpravo.
- Směry lze měnit během skoků/převalování (toho lze mnohem snadněji dosáhnout pomocí ovladače).

## Skákání

- Výšku skoku lze změnit stisknutím a trváním tlačítka skoku.
- Směry lze měnit během skoků/pádu.

## Létající hamburger

- Chytání létajícího hamburgeru způsobí, že váš DEGENův netopýr zasáhne mnohem silnější – to obvykle vede k přímému zabití.
- Zvažujeme omezení doby trvání burgerového bufu časem a/nebo zabitím.

# **Specifikace kmene**

_Všechny kmeny DEGEN mají speciální schopnost (“SA”), která bude konzistentní ve všech hrách Nifty League (živých i budoucích)._

## Seznam speciálních schopností

- **Ape** - Hoďte bumerangové banány
- **Mimozemšťan** - Teleport
- **Cat** - Pounge a získejte dočasně netopýří sílu a zvýšení rychlosti
- **Žába** - Hák na uchopení jazyka
- **Doge** - Hod mincí Doge
- **Člověk** – Hoďte dynamity, které explodují na povel

## Mimozemšťan

- Stisknutí tlačítka SA způsobí, že se Vetřelec může teleportovat na krátkou vzdálenost v zamýšleném směru (doleva, doprava, nahoru, dolů, úhlopříčky).
- V teleportovaném místě dojde k energetické explozi, která zasáhne protivníky, kteří stojí poblíž.

## Opice

- Stisknutí tlačítka SA hází banán zamířeným směrem (doleva, doprava, nahoru, dolů, úhlopříčky), dokud nezasáhne soupeře, nezasáhne část mapy nebo nevyletí z mapy.
- Opětovné stisknutí tlačítka SA způsobí, že banán poletí zpět k DEGENU, což umožní znovu zasáhnout protivníka.
- Banány lze zasáhnout pálkou a letět zamířeným směrem.

## Kočka

- Stisknutím SA se kočka vrhne. Po krátkém vrhání se kočka posílila.
- Posílený švih netopýrem znamená, že netopýr zasáhne tvrději.
- Silnější pohyb znamená, že kočka běží rychleji.
- Kočky mohou dvakrát skákat a skákat ve vzduchu.

## Dóže

- Stisknutím a podržením tlačítka SA se doge vrhne.
- Zasažení protivníka hodem doge způsobí, že vyletí nahoru ve směru hodu.
- Doge se bude létat a kutálet zamířeným směrem.
- Během doge rollu lze změnit směr třikrát, dokud neskončí doge roll.
- Doge roll po určité době také končí.

## Žába

- Stisknutí tlačítka SA způsobí, že žába vystřelí jazyk.
- Když jazyk zasáhne protivníka, je tento protivník vytažen směrem k žábě a letí o kus dále.
- Když jazyk narazí na kus mapy, žáby se přitáhnou k tomuto předmětu (např. stěnám, stropům atd.)
- Jazyk lze vystřelit v mířeném směru (doleva, doprava, nahoru, dolů, úhlopříčky).

### Člověk

- Stisknutí tlačítka SA odhodí bombu v namířeném směru (doleva, doprava, nahoru, dolů, úhlopříčky).
- Bomba má letmou křivku a neletí rovně jako banány (pokud není odpálena, zůstane na zemi).
- Bomba exploduje po nějaké době nebo po druhém stisknutí tlačítka SA.
- V současné době může bomba zasáhnout protivníka úderem nebo explozí.
- Bomby jsou jediné SA, které mohou svou explozí zasáhnout samotný vrhající DEGEN.
- Bomby lze zasáhnout pálkou a letět zamířeným směrem.
- Plánujeme aktualizovat hru tak, aby bomba vybuchla okamžitě po kontaktu s protivníkem. Pokud není zasažen žádný protivník, zůstane na zemi, dokud nevybuchne automaticky nebo po druhém stisknutí tlačítka SA.

Připojte se k našemu **[Discordu](https://discord.gg/niftyleague)** a poskytněte nám zpětnou vazbu a nápady, jak můžeme hru vylepšit a posunout ji na další úroveň.
