---
id: ügyes-smashers
title: Ügyes Smashers
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Az Ön böngészője nem támogatja a videocímkét.
  </video>
  </div>

---

# **Általános információ**

Készülj fel a verekedésre! **[Nifty Smashers](https://nifty-league.com/games)** helyi többjátékos verziója azonnal elérhetővé vált az induláskor, majd az online többjátékos.

Küzdj meg vele a közösségben, és szerezz minél több denevér bonkot a barátaidnak! A Nifty Smashers a klasszikus Super Smash Bros játékból merít ihletet, ahol a cél az, hogy ellenfeleidet leütd a térképről, hogy pontokat szerezz.

Játszhatsz a billentyűzeteddel vagy bármilyen más kompatibilis kontrollerrel (Playstation, Xbox stb.). Lépj be a játék előcsarnokába, és válaszd ki a DEGEN-edet a csatához.

## Pontozás

- Ha egy DEGEN-t egyszer eltalálják és meghal (leesik a térképről), 1 pontot kapsz.
- Ha egy DEGEN-t többször eltalálják anélkül, hogy képes lennél helyreállni, akkor pont annyiszor kapsz pontot, ahányszor a DEGEN-t eltalálják (függetlenül attól, hogy a korábbi találatokat egy másik DEGEN ütötte-e – szóval tedd le az utolsó mega-bonkot, hogy leüthesd őket a térképről, és igényeld forduló összes pontját).
- Minél többet botlik egymás után az ellenfeled, annál gyorsabban ugrál, és annál több pontot szerezhetsz.
- Az utolsó találat, amelyik megöli a DEGEN-t, megkapja az összes kombinált pontot.
- Jelenleg nincs korlátozva, hogy egy DEGEN-t hányszor lehet eltalálni (kombinált), de a megszerezhető pontok számának korlátozása van (max 3 pont: 2 játékos meccs / max 5 pont: 3&4 játékos meccs ).
- Egy 2 fős meccsen 5 pont szükséges a kör megnyeréséhez.
- 3 & 4 fős meccsek esetén 10 pont szükséges egy kör megnyeréséhez.
- A mérkőzések 5 körből a legjobbak.
- Ha az 5. kör után döntetlen van, a döntetlen játékosok egy hirtelen halál körbe lépnek, amelyet a többi játékos az oldalvonalról nézhet.

## Lemaradás

- A késésjelző a kapcsolat késését (ping sebességét) mutatja.
- A késés általában azt jelzi, hogy a ping sebessége meghaladja a 100 ms-ot.
- Általánosságban elmondható, hogy a késés mindig jelen van, ha fizikai távolság van a játékosok között az interneten. Minél nagyobb a távolság, annál nagyobb a késés.
- A fejlesztők különböző technikákat alkalmaznak a késés kompenzálására és elrejtésére.
- Számos késéskompenzációs technikát alkalmaztunk, amelyek a lehető legjobb élmény érdekében elfedik a késést.
- A világ különböző pontjain lévő szerverekkel is beépítettünk megoldásokat, hogy egymáshoz legközelebb eső játékosokat párosíthassuk, hogy a lehető legkisebbre csökkentsük a késést. Ha többet szeretne megtudni ezekről a technikákról, nézze meg [ezt a bejegyzést](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) amit szeretünk a késés kompenzációjáról Gabriel Gambetta.

## Egyedi előcsarnok

- Egy egyéni lobby használható a mérkőzés megnyitására a kiválasztott régióban. Az előcsarnok létrehozója a lobby térképen láthat egy kódot, amelyet megoszthat másokkal.
- Ha egy másik degen szeretne csatlakozni a lobbyhoz, először ki kell választania a megfelelő régiót, majd be kell írnia a lobby kódját a beviteli mezőbe.
- Egyéni lobby kód használata esetén a régiót automatikusan át kell váltani.

## Változó régiók

- A Smasher egy gyors tempójú játék, ahol a késleltetés/ping kulcsfontosságú. Minél közelebb van a kiválasztott régió a játékos helyéhez, annál alacsonyabb a ping.
- Miután megváltoztatta a régiót a Web-GL-ben vagy az asztali alkalmazásban, megjelenik az aktuális ping.

# **Harc alapjai**

## Általános Tanács

- A játék kontrollerrel erősen ajánlott (Playstation, Xbox vagy bármely más, a PC/Mac által felismert kontrollerrel).

## Denevérhinták

- Az ütő minden lehetséges irányba forgatható: balra, jobbra, fel, le, átlósan.
- Az ütőt a támadás gombra kattintva lehet lendíteni.
- A gomb hosszabb lenyomása erősebbé teszi az ütőt.
- Az ütő állva, futva vagy ugrálva lendíthető.
- A játékosok hosszan lenyomhatják a támadás gombot ugrások közben – ez általában jó módja annak, hogy meglepje ellenfeleit.

## Mozgó

- 2D-s játékként a mozgási irányok balra/jobbra vonatkoznak.
- Az irányok megváltoztathatók ugrások/buktatás közben (ez sokkal könnyebben megvalósítható kontrollerrel).

## Ugrás

- Az ugrás magassága az ugrás gomb megnyomásával módosítható.
- Az irány megváltoztatható ugrások/buktatás közben.

## Repülő Hamburger

- A repülő hamburger elkapása sokkal erősebbé teszi a DEGEN ütőjét – ez általában közvetlen ölést eredményez.
- Azt fontolgatjuk, hogy korlátozzuk a hamburgerbuff időtartamát az idő és/vagy az ölés alapján.

# **A törzs sajátosságai**

_Minden DEGEN törzs rendelkezik speciális képességgel ("SA"), amely az összes Nifty League-játékban (élőben és jövőben) is egységes lesz._

## Különleges képességek listája

- **Ape** – Dobj bumeráng banánt
- **Alien** - Teleportál
- **Cat** – Ugrálj, és ideiglenesen növeld az ütőerőt és a sebességet
- **Béka** - A nyelvmarkoló horog
- **Doge** - Doge érme tekercs
- **Ember** - Dobj dinamitokat, amelyek parancsra felrobbannak

## Idegen

- Az SA gomb megnyomásával az Alien kis távolságra teleportálhat a megcélzott irányba (balra, jobbra, fel, le, átlók).
- Energiarobbanás történik a teleportált helyen, ami eltalálja a közelben álló ellenfeleket.

## Emberszabású majom

- Az SA gomb megnyomása a banánt a megcélzott irányba dobja (balra, jobbra, fel, le, átlók), amíg el nem találja az ellenfelet, el nem találja egy térképrészt, vagy le nem repül a térképről.
- Az SA gomb újbóli megnyomásával a banán visszarepül a DEGEN-be, ami lehetővé teszi, hogy ismét eltaláljon egy ellenfelet.
- A banánt ütővel lehet ütni és a megcélzott irányba repülni.

## Macska

- Az SA megnyomására a macska felpattan. Rövid ütés után a macska megerősödött.
- A megerősített denevérlengés azt jelenti, hogy az ütő erősebben üt.
- Az erős mozgás azt jelenti, hogy a macska gyorsabban fut.
- A macskák képesek duplán ugrani és levegőben ugrani.

## Dózse

- Az SA gomb lenyomásával és nyomva tartásával a doge felgurul.
- Ha dózsadobással ütik el az ellenfelet, az a dobás irányába felfelé repül.
- Doge repülni fog a megcélzott irányba.
- Doge roll közben az irány háromszor változtatható, amíg a doge roll véget nem ér.
- A Doge tekercs egy bizonyos idő után véget is ér.

## Béka

- Az SA gomb megnyomásával a béka kilövi a nyelvét.
- Amikor a nyelv eltalálja az ellenfelet, az ellenfél a békák irányába húzódik, és egy kicsit tovább repül.
- Amikor a nyelv eltalál egy térképdarabot, a békák az adott tárgyhoz húzódnak (pl. falak, mennyezetek stb.)
- A nyelv a megcélzott irányba lőhető (balra, jobbra, fel, le, átlósan).

### Emberi

- Az SA gomb megnyomásával bombát dob a célirányba (balra, jobbra, fel, le, átlók).
- A bombának van egy repülő íve, és nem repül egyenesen, mint a banán (ha nem robbantják fel, akkor a földön marad).
- A bomba egy idő után vagy az SA gomb másodszori megnyomása után felrobban.
- Jelenleg a bomba eltalálhatja az ellenfelet ütéssel vagy robbanással.
- A bombák az egyetlen SA, amely magát a dobó DEGEN-t tudja eltalálni a robbanásával.
- A bombákat ütővel lehet eltalálni, és a megcélzott irányba repülni.
- Azt tervezzük, hogy frissítjük a játékot, hogy a bomba azonnal felrobbanjon az ellenféllel való érintkezés után. Ha egyetlen ellenfelet sem talál el, akkor a földön marad, amíg automatikusan fel nem robban, vagy az SA gomb másodszori megnyomása után.

Kérjük, csatlakozzon a **[Discord](https://discord.gg/niftyleague)** hoz, hogy visszajelzést és ötleteket adjon a játék fejlesztéséhez és a következő szintre emeléséhez.
