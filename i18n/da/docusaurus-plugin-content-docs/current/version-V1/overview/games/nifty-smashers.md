---
id: smarte smashere
title: Smarte smashere
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Din browser understøtter ikke video-tagget.
  </video>
  </div>

---

# **Generel info**

Gør dig klar til at slås! Den lokale multiplayer-version af **[Nifty Smashers](https://nifty-league.com/games)** blev gjort tilgængelig umiddelbart ved lanceringen efterfulgt af online multiplayer.

Kæmp det ud blandt fællesskabet, og få så mange flagermus på dine venner, som du kan! Nifty Smashers tager inspiration fra det klassiske Super Smash Bros-spil, hvor målet er at slå dine modstandere væk fra kortet for at score point.

Du kan spille med dit tastatur eller en hvilken som helst anden kompatibel controller (Playstation, Xbox osv.). Gå ind i spillets lobby og vælg din DEGEN til kamp.

## Scoring

- Hvis en DEGEN bliver ramt én gang og dør (falder af kortet) får du 1 point.
- Hvis en DEGEN bliver ramt flere gange uden at være i stand til at komme sig, får du point lige så ofte, som DEGEN bliver ramt (uanset om tidligere hits blev udført af en anden DEGEN - så land den sidste mega-bonk for at ramme dem fra kortet og kræve alle point for runden).
- Jo mere din modstander successivt bliver bonket, jo hurtigere hopper de rundt, og jo flere point får du for bonking.
- Det sidste hit, der dræber DEGEN, får alle kombinationspoint.
- I øjeblikket er der ingen grænse for, hvor ofte en DEGEN kan rammes (kombineret), men der er et loft for antallet af point, du kan få (max 3 point: 2-spiller kamp / max 5 point: 3&4-spiller kamp ).
- En kamp med 2 spillere kræver 5 point for at vinde en runde.
- 3 & 4-spiller kampe kræver 10 point for at vinde en runde.
- Kampe er bedst af 5 runder.
- Hvis der er uafgjort efter 5. runde, går de lige spillere ind i en sudden death-runde, som de andre spillere kan se fra sidelinjen.

## Lag

- Forsinkelsesindikatoren viser forsinkelsen (pinghastighed) for din forbindelse.
- Lag angiver typisk din ping-hastighed er over 100ms.
- Generelt er lag altid til stede, når der er fysisk afstand mellem spillerne på internettet. Jo større afstand, jo større forsinkelse.
- Der er forskellige teknikker, som udviklere bruger til at kompensere og skjule forsinkelsen.
- Vi har implementeret en række af disse forsinkelseskompensationsteknikker, der skjuler forsinkelsen for den bedst mulige oplevelse.
- Vi har også indarbejdet løsninger med servere over hele verden, så vi kan matche spillere tættest på hinanden for at minimere forsinkelsen så meget som muligt. Hvis du er interesseret i at lære mere om disse teknikker, så tjek [dette indlæg](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) vi elsker på Lagkompensation af Gabriel Gambetta.

## Brugerdefineret lobby

- En tilpasset lobby kan bruges til at åbne en kamp i en valgt region. Skaberen af lobbyen kan se en kode i lobbykortet, som kan deles med andre.
- Hvis en anden degen ønsker at deltage i lobbyen, skal han først vælge den korrekte region og derefter indtaste lobbykoden i inputfeltet.
- Når du bruger en brugerdefineret lobbykode, skal regionen skiftes automatisk.

## Ændring af regioner

- Smasher er et hurtigt spil, hvor latency/ping er afgørende. Jo tættere den valgte region er på spillerens placering, jo lavere ping.
- Efter at have ændret region i Web-GL eller Desktop App, vises den aktuelle ping.

# **Battle Basics**

## Generelle råd

- Det anbefales stærkt at spille med en controller (Playstation, Xbox eller enhver anden controller, der genkendes af din pc/Mac).

## Flagermus gynger

- Flagermusen kan svinges i alle mulige retninger: venstre, højre, op, ned, diagonaler.
- Flagermusen kan svinges ved at klikke på angrebsknappen.
- Længere tryk på knappen gør, at flagermusen slår hårdere.
- Flagermusen kan svinges, mens den står, løber eller hopper.
- Spillere kan trykke længe på angrebsknappen under hop - dette er normalt en god måde at overraske din(e) modstander(e).

## Bevæger sig

- Som et 2D-spil er bevægelsesretninger venstre/højre.
- Retninger kan ændres under hop/tumbling (dette er meget nemmere at opnå med en controller).

## Hoppe

- Springhøjden kan ændres ved at trykke på varigheden af springknappen.
- Retninger kan ændres under hop/tumbling.

## Flyvende Hamburger

- At fange den flyvende hamburger vil få din DEGENs flagermus til at slå meget stærkere - dette resulterer typisk i et direkte drab.
- Vi overvejer at begrænse burgerbuffets varighed efter tid og/eller dræb.

# **Stammespecifikationer**

_Alle DEGEN-stammer har en speciel evne ("SA"), som vil være konsistent på tværs af alle Nifty League-spil (live og fremtidig)._

## Liste over særlige evner

- **Ape** - Kast boomerangbananer
- **Alien** - Teleport
- **Kat** - Kast og få flagermusstyrke og hastighedsboost midlertidigt
- **Frø** - Tungegribekrogen
- **Doge** - Doge møntrulle
- **Menneske** - Kast dynamitter, der eksploderer på kommando

## Alien

- Ved at trykke på SA-knappen kan Alien teleportere en kort afstand i den tilsigtede retning (venstre, højre, op, ned, diagonaler).
- Der er en energieksplosion på det teleporterede sted, der rammer modstandere, der står i nærheden.

## Abe

- Et tryk på SA-knappen kaster en banan i den sigtede retning (venstre, højre, op, ned, diagonaler), indtil den rammer en modstander, rammer en kortdel eller flyver væk fra kortet.
- Et tryk på SA-knappen igen får bananen til at flyve tilbage til DEGEN, hvilket gør det muligt at ramme en modstander igen.
- Bananer kan slås med et flagermus og flyve i den tilsigtede retning.

## Kat

- Et tryk på SA får katten til at kaste sig. Efter at have ramt i en kort periode fik katten magt.
- Styrket flagermussving betyder, at flagermusen slår hårdere.
- Styrket bevægelse betyder, at katten løber hurtigere.
- Katte kan dobbeltspringe og hoppe i luften.

## Doge

- Ved at trykke på SA-knappen og holde den nede får dogen til at rulle.
- At ramme en modstander med doge roll får dem til at flyve opad i roll retning.
- Doge vil fly-rulle i den tilsigtede retning.
- Under doge roll kan retningen ændres tre gange, indtil doge roll slutter.
- Doge roll slutter også efter en vis tid.

## Frø

- Et tryk på SA-knappen får frøen til at skyde med tungen.
- Når tungen rammer en modstander, trækkes denne modstander til frøernes retning og flyver lidt længere.
- Når tungen rammer et kortstykke, trækker frøerne sig til den genstand (f.eks. vægge, lofter osv.)
- Tungen kan skydes i den sigtede retning (venstre, højre, op, ned, diagonaler).

### Human

- Et tryk på SA-knappen kaster en bombe i den sigtede retning (venstre, højre, op, ned, diagonaler).
- Bomben har en flyvende kurve og flyver ikke lige som bananer (hvis den ikke detoneres, bliver den på jorden).
- Bomben eksploderer efter et stykke tid eller efter at SA-knappen trykkes igen.
- I øjeblikket kan bomben ramme en modstander ved at ramme den eller via eksplosion.
- Bomber er den eneste SA, der kan ramme selve den kastende DEGEN med sin eksplosion.
- Bomber kan slås med et bat og flyve i den tilsigtede retning.
- Vi planlægger at opdatere spillet, så bomben detonerer umiddelbart efter kontakt med en modstander. Hvis ingen modstander bliver ramt, bliver den på jorden, indtil den eksploderer automatisk eller efter at have trykket på SA-knappen anden gang.

Tilmeld dig vores **[Discord](https://discord.gg/niftyleague)** at give feedback og ideer til, hvordan vi kan forbedre spillet og tage det til næste niveau.
