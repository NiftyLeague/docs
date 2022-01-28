---
id: raffinierte Zerschmetterer
title: Schicke Smasher
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Ihr Browser unterstützt das Video-Tag nicht.
  </video>
  </div>

---

# **Allgemeine Information**

Mach dich bereit für eine Schlägerei! Die lokale Multiplayer-Version von **[Nifty Smashers](https://nifty-league.com/games)** wurde sofort nach dem Start verfügbar gemacht, gefolgt vom Online-Multiplayer.

Kämpfe in der Community und bringe so viele Fledermäuse wie möglich auf deine Freunde! Nifty Smashers ist vom klassischen Super Smash Bros-Spiel inspiriert, bei dem es darum geht, deine Gegner von der Karte zu stoßen, um Punkte zu sammeln.

Sie können mit Ihrer Tastatur oder jedem anderen kompatiblen Controller (Playstation, Xbox usw.) spielen. Betreten Sie die Spiellobby und wählen Sie Ihren DEGEN für den Kampf aus.

## Punkte

- Wenn ein DEGEN einmal getroffen wird und stirbt (von der Karte fallen), erhalten Sie 1 Punkt.
- Wenn ein DEGEN mehrmals getroffen wird, ohne sich erholen zu können, erhalten Sie so oft Punkte, wie der DEGEN getroffen wurde (unabhängig davon, ob vorherige Treffer von einem anderen DEGEN ausgeführt wurden - landen Sie also den letzten Mega-Bonk, um ihn von der Karte zu schlagen und zu beanspruchen alle Punkte für die Runde).
- Je mehr Ihr Gegner hintereinander gebumst wird, desto schneller hüpfen sie herum und desto mehr Punkte erhalten Sie für das Bumsen.
- Der letzte Treffer, der den DEGEN tötet, erhält alle Combopunkte.
- Derzeit gibt es keine Obergrenze dafür, wie oft ein DEGEN getroffen (kombiniert) werden kann, aber es gibt eine Obergrenze für die Anzahl der Punkte, die Sie erhalten können (max. 3 Punkte: 2-Spieler-Match / max. 5 Punkte: 3&4-Spieler-Match ).
- Ein 2-Spieler-Match erfordert 5 Punkte, um eine Runde zu gewinnen.
- 3 & 4-Spieler-Matches erfordern 10 Punkte, um eine Runde zu gewinnen.
- Die Matches sind Best-of-5-Runden.
- Bei einem Unentschieden nach der 5. Runde gehen die am Gleichstand beteiligten Spieler in eine Sudden-Death-Runde, die die anderen Spieler von der Seitenlinie aus beobachten können.

## Verzögerung

- Die Verzögerungsanzeige zeigt die Verzögerung (Ping-Geschwindigkeit) Ihrer Verbindung an.
- Verzögerung zeigt normalerweise an, dass Ihre Ping-Geschwindigkeit über 100 ms liegt.
- Im Allgemeinen ist eine Verzögerung immer dann vorhanden, wenn zwischen den Spielern im Internet eine physische Distanz besteht. Je größer der Abstand, desto größer die Verzögerung.
- Es gibt verschiedene Techniken, die Entwickler verwenden, um die Verzögerung zu kompensieren und zu verbergen.
- Wir haben eine Reihe dieser Verzögerungskompensationstechniken implementiert, die die Verzögerung verschleiern, um das bestmögliche Erlebnis zu erzielen.
- Wir haben auch Lösungen mit Servern auf der ganzen Welt integriert, damit wir Spieler am nächsten zusammenbringen können, um die Verzögerung so weit wie möglich zu minimieren. Wenn Sie daran interessiert sind, mehr über diese Techniken zu erfahren, lesen Sie [diesen Beitrag](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) we love on Lag Compensation von Gabriel Gambetta.

## Benutzerdefinierte Lobby

- Eine benutzerdefinierte Lobby kann verwendet werden, um ein Spiel in einer ausgewählten Region zu eröffnen. Der Ersteller der Lobby kann einen Code in der Lobby-Karte sehen, der mit anderen geteilt werden kann.
- Wenn ein anderer Degen der Lobby beitreten möchte, muss er zuerst die richtige Region auswählen und dann den Lobby-Code in das Eingabefeld eingeben.
- Bei Verwendung eines benutzerdefinierten Lobby-Codes sollte die Region automatisch umgeschaltet werden.

## Wechselnde Regionen

- Smasher ist ein schnelles Spiel, bei dem Latenz/Ping entscheidend sind. Je näher die ausgewählte Region am Standort des Spielers liegt, desto niedriger ist der Ping.
- Nach dem Wechsel der Region in der Web-GL oder Desktop App wird der aktuelle Ping angezeigt.

# **Kampfgrundlagen**

## Allgemeine Beratung

- Das Spielen mit einem Controller wird dringend empfohlen (Playstation, Xbox oder ein anderer Controller, der von Ihrem PC/Mac erkannt wird).

## Fledermaus schwingt

- Der Schläger kann in alle möglichen Richtungen geschwungen werden: links, rechts, oben, unten, diagonal.
- Der Schläger kann durch Klicken auf die Angriffstaste geschwungen werden.
- Längere Tastendrücke machen den Schlag härter.
- Der Schläger kann im Stehen, Laufen oder Springen geschwungen werden.
- Spieler können während Sprüngen lange auf die Angriffstaste drücken – dies ist normalerweise eine gute Möglichkeit, Ihre(n) Gegner zu überraschen.

## Ziehen um

- Als 2D-Spiel sind die Bewegungsrichtungen links/rechts.
- Die Richtung kann während Sprüngen/Stürzen geändert werden (dies ist viel einfacher mit einem Controller zu bewerkstelligen).

## Springen

- Die Sprunghöhe kann durch die Druckdauer der Sprungtaste verändert werden.
- Die Richtung kann während Sprüngen/Stürzen geändert werden.

## Fliegender Hamburger

- Wenn Sie den fliegenden Hamburger fangen, wird der Schläger Ihres DEGEN viel stärker getroffen – dies führt normalerweise zu einem direkten Kill.
- Wir erwägen, die Burger-Buff-Dauer nach Zeit und/oder Kill zu begrenzen.

# **Stammesspezifische Besonderheiten**

_Alle DEGEN-Stämme haben eine Spezialfähigkeit („SA“), die in allen Nifty League-Spielen (live und in Zukunft) einheitlich sein wird._

## Liste der besonderen Fähigkeiten

- **Ape** - Bumerang-Bananen werfen
- **Außerirdischer** - Teleportieren
- **Cat** - Stürzen Sie sich und erhalten Sie vorübergehend Schlagkraft und Geschwindigkeitsschub
- **Frosch** - Der Zungenhaken
- **Doge** - Doge-Münzwurf
- **Mensch** - Wirf Dynamite, die auf Befehl explodieren

## Außerirdischer

- Durch Drücken der SA-Taste kann Alien eine kurze Distanz in die Zielrichtung teleportieren (links, rechts, oben, unten, diagonal).
- Am teleportierten Ort gibt es eine Energieexplosion, die Gegner trifft, die in der Nähe stehen.

## Affe

- Durch Drücken der SA-Taste wird eine Banane in die gewünschte Richtung (links, rechts, oben, unten, diagonal) geworfen, bis sie einen Gegner trifft, einen Kartenteil trifft oder von der Karte fliegt.
- Durch erneutes Drücken der SA-Taste fliegt die Banane zurück zum DEGEN, wodurch es möglich ist, einen Gegner erneut zu treffen.
- Bananen können mit einem Schläger getroffen werden und in die gewünschte Richtung fliegen.

## Katze

- Durch Drücken der SA springt die Katze. Nach kurzem Anspringen ist die Katze ermächtigt.
- Stärkerer Schlägerschwung bedeutet, dass der Schläger härter trifft.
- Kraftvolle Bewegung bedeutet, dass die Katze schneller läuft.
- Katzen können doppelt springen und in der Luft springen.

## Doge

- Durch Drücken und Halten der SA-Taste rollt der Doge.
- Trifft man einen Gegner mit der Dogenrolle, fliegt dieser in Rollrichtung nach oben.
- Doge rollt in die gewünschte Richtung.
- Während der Doge-Rolle können die Richtungen dreimal geändert werden, bis die Doge-Rolle endet.
- Doge Roll endet auch nach einer bestimmten Zeit.

## Frosch

- Durch Drücken der SA-Taste schießt der Frosch mit der Zunge.
- Wenn die Zunge einen Gegner trifft, wird dieser in die Froschrichtung gezogen und fliegt etwas weiter.
- Wenn die Zunge auf ein Kartenstück trifft, zieht sich der Frosch zu diesem Objekt (z. B. Wände, Decken usw.)
- Die Zunge kann in die Zielrichtung (links, rechts, oben, unten, diagonal) geschossen werden.

### Menschlich

- Durch Drücken der SA-Taste wird eine Bombe in die gewünschte Richtung geworfen (links, rechts, oben, unten, diagonal).
- Die Bombe hat eine Flugkurve und fliegt nicht geradeaus wie Bananen (wenn sie nicht gezündet wird, bleibt sie am Boden).
- Die Bombe explodiert nach einiger Zeit oder nachdem die SA-Taste ein zweites Mal gedrückt wurde.
- Derzeit kann die Bombe einen Gegner treffen, indem sie sie trifft oder durch Explosion.
- Bomben sind die einzige SA, die mit ihrer Explosion den werfenden DEGEN selbst treffen kann.
- Bomben können mit einem Schläger getroffen werden und in die gewünschte Richtung fliegen.
- Wir planen, das Spiel so zu aktualisieren, dass die Bombe sofort nach dem Kontakt mit einem Gegner explodiert. Wenn kein Gegner getroffen wird, bleibt es am Boden, bis es automatisch explodiert oder nach dem zweiten Drücken der SA-Taste.

Bitte treten Sie unserem **[Discord](https://discord.gg/niftyleague)** , um Feedback und Ideen zu geben, wie wir das Spiel verbessern und auf die nächste Stufe bringen können.
