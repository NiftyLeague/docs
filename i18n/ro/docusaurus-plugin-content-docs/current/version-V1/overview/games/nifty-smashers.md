---
id: nifty-smashers
title: Nifty Smashers
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Browserul dvs. nu acceptă eticheta video.
  </video>
  </div>

---

# **Informatii generale**

Pregătește-te de ceartă! Versiunea multiplayer local a **[Nifty Smashers](https://nifty-league.com/games)** fost disponibilă imediat la lansare, urmată de multiplayer online.

Luptă-te în rândul comunității și fă cât mai multe bătăi de cap cu prietenii tăi! Nifty Smashers se inspiră din jocul clasic Super Smash Bros, în care obiectivul este să-ți arunci adversarii de pe hartă pentru a câștiga puncte.

Puteți juca folosind tastatura sau orice alt controler compatibil (Playstation, Xbox etc.). Intră în lobby-ul jocului și selectează-ți DEGEN pentru luptă.

## Punctajul

- Dacă un DEGEN este lovit o dată și moare (cad de pe hartă), primești 1 punct.
- Dacă un DEGEN este lovit de mai multe ori fără a putea să-și revină, obțineți puncte de câte ori este lovit DEGEN (indiferent dacă loviturile anterioare au fost făcute de un alt DEGEN - așa că aterizați mega-bonkul final pentru a le lovi de pe hartă și revendica toate punctele pentru rundă).
- Cu cât adversarul tău este mai mult succesiv, cu atât sară mai repede și cu atât vei câștiga mai multe puncte pentru bonking.
- Ultima lovitură care ucide DEGEN primește toate punctele combo.
- În prezent, nu există o limită pentru cât de des poate fi lovit un DEGEN (combinat), dar există o limită pentru numărul de puncte pe care le puteți obține (maxim 3 puncte: meci cu 2 jucători / max 5 puncte: 3&meci cu 4 jucători ).
- Un meci de 2 jucători necesită 5 puncte pentru a câștiga o rundă.
- 3 & meciuri cu 4 jucători necesită 10 puncte pentru a câștiga o rundă.
- Meciurile sunt cele mai bune din 5 runde.
- Dacă există o egalitate după runda a 5-a, jucătorii la egalitate trec într-o rundă de moarte subită pe care ceilalți jucători pot să o urmărească de pe margine.

## Lag

- Indicatorul de întârziere arată întârzierea (viteza de ping) a conexiunii dvs.
- Întârzierea indică, de obicei, viteza dvs. de ping este peste 100 ms.
- În general, lag-ul este întotdeauna prezent ori de câte ori există distanță fizică între jucători de pe internet. Cu cât distanța este mai mare, cu atât este mai mare decalajul.
- Există diferite tehnici pe care dezvoltatorii le folosesc pentru a compensa și a ascunde decalajul.
- Am implementat o serie de aceste tehnici de compensare a întârzierilor care ascund întârzierea pentru cea mai bună experiență posibilă.
- De asemenea, am încorporat soluții cu servere din întreaga lume, astfel încât să putem potrivi jucătorii cei mai apropiați unul de celălalt pentru a minimiza decalajul cât mai mult posibil. Dacă sunteți interesat să aflați mai multe despre aceste tehnici, consultați [această postare](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) ne place pe Lag Compensation de Gabriel Gambetta.

## Lobby personalizat

- Un lobby personalizat poate fi folosit pentru a deschide un meci într-o regiune aleasă. Creatorul lobby-ului poate vedea un cod pe harta lobby-ului care poate fi partajat altora.
- Dacă un alt degen dorește să se alăture lobby-ului, trebuie mai întâi să selecteze regiunea corectă și apoi să tastați codul lobby-ului în caseta de introducere.
- Când utilizați un cod de lobby personalizat, regiunea ar trebui să fie schimbată automat.

## Schimbarea regiunilor

- Smasher este un joc cu ritm rapid în care latența/ping-ul este crucial. Cu cât regiunea aleasă este mai aproape de locația jucătorului, cu atât ping-ul este mai scăzut.
- După schimbarea regiunii în aplicația Web-GL sau Desktop, este afișat ping-ul curent.

# **Bazele bătăliei**

## Sfat general

- Jocul cu un controler foarte recomandat (Playstation, Xbox sau orice alt controler recunoscut de PC/Mac).

## Leagăne de lilieci

- Liliacul poate fi balansat în toate direcțiile posibile: stânga, dreapta, sus, jos, diagonale.
- Liliacul poate fi aruncat făcând clic pe butonul de atac.
- Apăsări mai lungi de buton fac bâtul să lovească mai puternic.
- Liliacul poate fi legănat în timp ce stați în picioare, aleargă sau săriți.
- Jucătorii pot apăsa lung butonul de atac în timpul sărituri - aceasta este de obicei o modalitate bună de a-ți surprinde adversarul(i).

## In miscare

- Ca un joc 2D, direcțiile de mișcare sunt stânga/dreapta.
- Direcțiile pot fi schimbate în timpul sărituri/tumble (acest lucru este mult mai ușor de realizat folosind un controler).

## Jumping

- Înălțimea săriturii poate fi modificată prin apăsarea butonului de săritură.
- Direcțiile pot fi schimbate în timpul sărituri/tumble.

## Hamburger zburător

- Prinderea hamburgerului zburător va face ca bâta DEGEN să lovindă mult mai puternică - acest lucru duce de obicei la o ucidere directă.
- Luăm în considerare limitarea duratei de burger în funcție de timp și/sau ucidere.

# **Specificul tribului**

_Toate triburile DEGEN au o abilitate specială („SA”), care va fi consecventă în toate jocurile Nifty League (în direct și în viitor)._

## Lista abilităților speciale

- **Ape** - Aruncă banane bumerang
- **Alien** - Teleportare
- **Cat** - Bucurați-vă și obțineți puterea liliecilor și creșterea vitezei temporare
- **Broasca** - Cârligul de prindere a limbii
- **Doge** - Rol de monede Doge
- **Uman** - Aruncă dinamite care explodează la comandă

## Străin

- Apăsând butonul SA, Alien se poate teleporta pe o distanță scurtă în direcția vizată (stânga, dreapta, sus, jos, diagonale).
- Există o explozie de energie în locația teleportată, lovind adversarii care stau în apropiere.

## Maimuţă

- Apăsarea butonului SA aruncă o banană în direcția vizată (stânga, dreapta, sus, jos, diagonale) până când lovește un adversar, lovește o parte a hărții sau zboară de pe hartă.
- Apăsarea butonului SA din nou face ca banana să zboare înapoi la DEGEN, făcând posibilă lovirea din nou a unui adversar.
- Bananele pot fi lovite cu o liliac și zboară în direcția vizată.

## Pisică

- Apăsând SA face pisica să se năpustească. După ce s-a năpustit pentru o scurtă durată, pisica s-a împuternicit.
- Leagănul de liliac împuternicit înseamnă că liliacul lovește mai puternic.
- Mișcarea împuternicită înseamnă că pisica aleargă mai repede.
- Pisicile pot sări dublu și să sară în aer.

## Doge

- Apăsarea și menținerea butonului SA face ca doge să se rostogolească.
- Lovirea unui adversar cu rola de doge îl face să zboare în sus în direcția de rostogolire.
- Doge va zbura și rostogoli în direcția vizată.
- În timpul rostogolirei de doge, direcțiile pot fi schimbate de trei ori până la sfârșitul rolului de doge.
- Rolul Doge se termină și după un anumit timp.

## Broască

- Apăsarea butonului SA îl face pe Broasca să-și tragă limba.
- Când limba lovește un adversar, acel adversar este tras în direcția broaștelor și zboară puțin mai departe.
- Când limba lovește o bucată de hartă, broaștele se trage spre acel obiect (de exemplu, pereți, tavane etc.)
- Limba poate fi trasă în direcția vizată (stânga, dreapta, sus, jos, diagonale).

### Uman

- Apăsarea butonului SA aruncă o bombă în direcția vizată (stânga, dreapta, sus, jos, diagonale).
- Bomba are o curbă zburătoare și nu zboară drept ca bananele (dacă nu detonează, rămâne pe pământ).
- Bomba explodează după ceva timp sau după ce butonul SA este apăsat a doua oară.
- În prezent, bomba poate lovi un adversar lovind-o sau prin explozie.
- Bombele sunt singurele SA care pot lovi DEGEN cu explozia lui.
- Bombele pot fi lovite cu o bâtă și zboară în direcția vizată.
- Intenționăm să actualizăm jocul, astfel încât bomba să detoneze imediat după contactul cu un adversar. Dacă niciun adversar nu este lovit, acesta rămâne pe pământ până când explodează automat sau după ce apăsați butonul SA a doua oară.

Vă rugăm să vă alăturați **[Discord](https://discord.gg/niftyleague)** pentru a oferi feedback și idei despre cum putem îmbunătăți jocul și să-l ducem la nivelul următor.
