---
id: näppärät murskaajat
title: Näppärät Smasherit
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Selaimesi ei tue videotunnistetta.
  </video>
  </div>

---

# **Yleistä tietoa**

Valmistaudu tappeluun! **[Nifty Smashers](https://nifty-league.com/games)** paikallinen moninpeliversio julkaistiin heti julkaisun yhteydessä ja sen jälkeen verkkomoninpeli.

Taistele yhteisön keskuudessa ja lyö ystävillesi niin monta lyöntiä kuin pystyt! Nifty Smashers saa inspiraationsa klassisesta Super Smash Bros -pelistä, jossa tavoitteena on kaataa vastustajasi pois kartalta pisteiden keräämiseksi.

Voit pelata näppäimistölläsi tai millä tahansa muulla yhteensopivalla ohjaimella (Playstation, Xbox jne.). Mene pelin aulaan ja valitse DEGEN taisteluun.

## Pisteytys

- Jos DEGEN osuu kerran ja kuolee (putoaa kartalta), saat 1 pisteen.
- Jos DEGENiin osuu useita kertoja ilman, että pystyt toipumaan, saat pisteitä niin usein kuin DEGENiin osuu (riippumatta siitä, onko aiemmat osumat tehty toisella DEGENillä - joten laske viimeinen megabonkki, jotta voit osua ne pois kartalta ja lunastaa kierroksen kaikki pisteet).
- Mitä enemmän vastustajasi lyö peräkkäin, sitä nopeammin hän pomppii ympäriinsä ja sitä enemmän pisteitä saat.
- Viimeinen osuma, joka tappaa DEGENin, saa kaikki yhdistelmäpisteet.
- Tällä hetkellä ei ole rajaa sille, kuinka usein DEGENiin voidaan lyödä (yhdistelmä), mutta pistemäärälle, jonka voit saada, on raja (max 3 pistettä: 2 pelaajan ottelu / max 5 pt: 3&4 pelaajan ottelu ).
- Kahden pelaajan ottelu vaatii 5 pistettä kierroksen voittamiseksi.
- 3 & 4 pelaajan ottelut vaativat 10 pistettä kierroksen voittamiseksi.
- Ottelut ovat paras viidestä kierroksesta.
- Jos 5. kierroksen jälkeen on tasapeli, tasatuloksissa olevat pelaajat siirtyvät äkilliseen kuolemaan, jota muut pelaajat pääsevät katsomaan sivurajasta.

## Viive

- Viiveilmaisin näyttää yhteytesi viiveen (ping-nopeuden).
- Viive osoittaa tyypillisesti, että ping-nopeus on yli 100 ms.
- Yleisesti ottaen viive on aina läsnä aina, kun pelaajien välillä on fyysinen etäisyys Internetissä. Mitä suurempi etäisyys, sitä suurempi viive.
- On olemassa erilaisia tekniikoita, joita kehittäjät käyttävät viiveen kompensoimiseen ja piilottamiseen.
- Olemme ottaneet käyttöön useita näitä viiveen kompensointitekniikoita, jotka peittävät viiveen parhaan mahdollisen kokemuksen saavuttamiseksi.
- Olemme myös yhdistäneet ratkaisuja palvelimiin ympäri maailmaa, jotta voimme sovittaa toisiaan lähinnä olevia pelaajia minimoidaksemme viiveen mahdollisimman paljon. Jos olet kiinnostunut oppimaan lisää näistä tekniikoista, katso [tämä viesti](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) jota rakastamme Gabriel Gambettan viiveen kompensoinnista.

## Mukautettu aula

- Räätälöityä aulaa voidaan käyttää ottelun avaamiseen valitulla alueella. Aulan luoja näkee aulakartassa koodin, jonka voi jakaa muiden kanssa.
- Jos toinen degen haluaa liittyä aulaan, hänen on ensin valittava oikea alue ja kirjoitettava sitten aulan koodi syöttöruutuun.
- Kun käytät mukautettua aulakoodia, alueen tulee vaihtaa automaattisesti.

## Vaihtuvat alueet

- Smasher on nopeatempoinen peli, jossa latenssi/ping on ratkaisevan tärkeää. Mitä lähempänä pelaajan sijaintia valittu alue on, sitä pienempi on ping.
- Kun alue on vaihdettu Web-GL:ssä tai työpöytäsovelluksessa, nykyinen ping näytetään.

# **Taistelun perusteet**

## Yleiset neuvot

- Pelaaminen ohjaimella on erittäin suositeltavaa (Playstation, Xbox tai mikä tahansa muu PC/Mac-tietokoneesi tunnistama ohjain).

## Lepakon keinut

- Mailaa voidaan heilauttaa kaikkiin mahdollisiin suuntiin: vasemmalle, oikealle, ylös, alas, diagonaaleihin.
- Mailaa voi heilauttaa napsauttamalla hyökkäyspainiketta.
- Pidemmät painikkeen painallukset tekevät mailasta kovempaa iskemistä.
- Mailaa voi heilua seistessä, juoksussa tai hyppääessä.
- Pelaajat voivat painaa hyökkäyspainiketta pitkään hyppyjen aikana - tämä on yleensä hyvä tapa yllättää vastustajasi.

## Liikkuva

- 2D-pelinä liikesuunnat ovat vasemmalle/oikealle.
- Suunta voidaan muuttaa hyppyjen/pysähdysten aikana (tämä on paljon helpompi suorittaa ohjaimella).

## Hyppääminen

- Hyppykorkeutta voidaan muuttaa painamalla hyppypainiketta.
- Suunta voidaan muuttaa hyppyjen/pysähdysten aikana.

## Lentävä hampurilainen

- Lentävän hampurilaisen kiinni saaminen tekee DEGENin mailasta paljon vahvemman - tämä johtaa yleensä suoraan tappamiseen.
- Harkitsemme hampurilaisen buffin keston rajoittamista ajan ja/tai tappamisen mukaan.

# **Heimotiedot**

_Kaikilla DEGEN-heimoilla on Special Ability ("SA"), joka on johdonmukainen kaikissa Nifty League -peleissä (liveissä ja tulevissa)._

## Luettelo erityiskyvyistä

- **Ape** - Heitä bumerangibanaanit
- **Alien** - Teleport
- **Cat** - Hyppää ja saat mailan tehoa ja nopeutta väliaikaisesti
- **Sammakko** - kielikoukku
- **Doge** - Doge-kolikkorulla
- **Ihminen** - Heitä dynamiittia, joka räjähtää käskystä

## Ulkomaalainen

- Painamalla SA-painiketta Alien voi teleportoida lyhyen matkan kohdistettuun suuntaan (vasemmalle, oikealle, ylös, alas, diagonaalit).
- Teleportoidussa paikassa tapahtuu energiaräjähdys, joka osuu lähellä seisoviin vastustajiin.

## Apina

- SA-painikkeen painaminen heittää banaania kohdistettuun suuntaan (vasemmalle, oikealle, ylös, alas, diagonaalit), kunnes se osuu vastustajaan, osuu karttaosaan tai lentää pois kartalta.
- Kun painat SA-painiketta uudelleen, banaani lentää takaisin DEGENiin, jolloin vastustajaan on mahdollista lyödä uudelleen.
- Banaaneja voi lyödä mailalla ja lentää haluttuun suuntaan.

## Kissa

- SA:n painaminen saa kissan pomppimaan. Lyhyen pommituksen jälkeen kissa vahvistui.
- Voimakas lepakkokeinu tarkoittaa, että maila osuu kovemmin.
- Voimakas liike tarkoittaa, että kissa juoksee nopeammin.
- Kissat voivat hypätä kaksinkertaisesti ja hypätä ilmassa.

## Doge

- Painamalla ja pitämällä SA-painiketta painettuna, doge rullaa.
- Vastustajaan lyöminen doge-rullalla saa heidät lentämään ylöspäin heiton suuntaan.
- Doge lennättää suunnattuun suuntaan.
- Doge-rullan aikana suuntaa voidaan vaihtaa kolme kertaa, kunnes doge-tela päättyy.
- Doge roll myös loppuu tietyn ajan kuluttua.

## Sammakko

- SA-painikkeen painaminen saa sammakon ampumaan kielensä.
- Kun kieli osuu vastustajaan, vastustaja vedetään sammakon suuntaan ja lentää hieman pidemmälle.
- Kun kieli osuu karttapalaan, sammakot vetäytyvät kyseiseen kohteeseen (esim. seinät, katto jne.)
- Kielellä voidaan ampua suunnattuun suuntaan (vasen, oikea, ylös, alas, diagonaalit).

### Ihmisen

- SA-painikkeen painaminen heittää pommin kohdistettuun suuntaan (vasemmalle, oikealle, ylös, alas, diagonaalit).
- Pommilla on lentävä kaarre, eikä se lennä suoraan kuin banaanit (jos sitä ei räjäytä, se pysyy maassa).
- Pommi räjähtää jonkin ajan kuluttua tai sen jälkeen, kun SA-painiketta painetaan toisen kerran.
- Tällä hetkellä pommi voi osua vastustajaan osumalla siihen tai räjähdyksen kautta.
- Pommit ovat ainoa SA, joka voi osua itse heittävään DEGENiin räjähdyksellä.
- Pommeihin voidaan lyödä mailalla ja lentää kohdistettuun suuntaan.
- Aiomme päivittää pelin niin, että pommi räjähtää heti kontaktin jälkeen vastustajaan. Jos vastustajaa ei lyödä, se pysyy maassa, kunnes se räjähtää automaattisesti tai kun SA-painiketta on painettu toisen kerran.

Liity **[Discord](https://discord.gg/niftyleague)** -ryhmään saadaksesi palautetta ja ideoita siitä, kuinka voimme parantaa peliä ja viedä sen seuraavalle tasolle.
