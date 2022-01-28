---
id: fiffige knusere
title: Flotte smashere
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Nettleseren din støtter ikke videokoden.
  </video>
  </div>

---

# **Generell info**

Gjør deg klar til å slåss! Den lokale flerspillerversjonen av **[Nifty Smashers](https://nifty-league.com/games)** ble gjort tilgjengelig umiddelbart ved lansering etterfulgt av online flerspiller.

Kjemp ut i fellesskapet og få så mange flaggermusbonker på vennene dine som du kan! Nifty Smashers henter inspirasjon fra det klassiske Super Smash Bros-spillet der målet er å slå motstanderne av kartet for å score poeng.

Du kan spille med tastaturet eller en annen kompatibel kontroller (Playstation, Xbox, etc.). Gå inn i spilllobbyen og velg din DEGEN for kamp.

## Scoring

- Hvis en DEGEN blir truffet én gang og dør (faller av kartet) får du 1 poeng.
- Hvis en DEGEN blir truffet flere ganger uten å være i stand til å komme seg, får du poeng like ofte som DEGEN blir truffet (uansett om tidligere treff ble gjort av en annen DEGEN - så land den siste mega-bonken for å treffe dem av kartet og kreve alle poengene for runden).
- Jo mer motstanderen din blir tullet, jo raskere spretter de rundt og jo flere poeng får du for tullingen.
- Det siste treffet som dreper DEGEN, får alle kombinasjonspoeng.
- Foreløpig er det ingen grense for hvor ofte en DEGEN kan treffes (kombinert), men det er et tak på antall poeng du kan få (maks 3 poeng: 2-spiller kamp / maks 5 poeng: 3&4-spiller kamp ).
- En 2-spiller kamp krever 5 poeng for å vinne en runde.
- 3 & 4-spillerkamper krever 10 poeng for å vinne en runde.
- Kamper er best av 5 runder.
- Hvis det er uavgjort etter 5. runde, går de likestilte spillerne inn i en sudden death-runde som de andre spillerne får se fra sidelinjen.

## Lag

- Lagindikatoren viser etterslepet (pinghastighet) til tilkoblingen din.
- Lag indikerer typisk pinghastigheten din er over 100 ms.
- Generelt sett er lag alltid tilstede når det er fysisk avstand mellom spillerne på internett. Jo større avstand, jo større etterslep.
- Det er forskjellige teknikker som utviklere bruker for å kompensere og skjule etterslepet.
- Vi har implementert en rekke av disse forsinkelseskompensasjonsteknikkene som skjuler forsinkelsen for en best mulig opplevelse.
- Vi har også innlemmet løsninger med servere over hele verden slik at vi kan matche spillere nærmest hverandre for å minimere etterslepet så mye som mulig. Hvis du er interessert i å lære mer om disse teknikkene, sjekk ut [dette innlegget](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) vi elsker på Lagkompensasjon av Gabriel Gambetta.

## Tilpasset lobby

- En tilpasset lobby kan brukes til å åpne en kamp i en valgt region. Skaperen av lobbyen kan se en kode i lobbykartet som kan deles med andre.
- Hvis en annen degen ønsker å bli med i lobbyen, må han først velge riktig region og deretter skrive inn lobbykoden i inntastingsboksen.
- Når du bruker en tilpasset lobbykode, bør regionen byttes automatisk.

## Endre regioner

- Smasher er et fartsfylt spill hvor latency/ping er avgjørende. Jo nærmere den valgte regionen er spillerens plassering, jo lavere ping.
- Etter å ha endret regionen i Web-GL eller Desktop App, vises gjeldende ping.

# **Grunnleggende om kamp**

## Generelle råd

- Å spille med en kontroller anbefales på det sterkeste (Playstation, Xbox eller en annen kontroller som gjenkjennes av din PC/Mac).

## Flaggermus svinger

- Flaggermusen kan svinges i alle mulige retninger: venstre, høyre, opp, ned, diagonaler.
- Flaggermusen kan svinges ved å klikke på angrepsknappen.
- Lengre knappetrykk gjør at flaggermusen slår hardere.
- Flaggermusen kan svinges mens den står, løper eller hopper.
- Spillere kan trykke lenge på angrepsknappen under hopp - dette er vanligvis en god måte å overraske motstanderen(e).

## Flytte

- Som et 2D-spill er bevegelige retninger venstre/høyre.
- Retninger kan endres under hopp/tumbling (dette er mye lettere å få til med en kontroller).

## Hopping

- Hopphøyden kan endres ved å trykke på varigheten av hoppknappen.
- Retningen kan endres under hopp/tumbling.

## Flyvende hamburger

- Å fange den flygende hamburgeren vil få DEGENs flaggermus til å treffe mye sterkere - dette resulterer vanligvis i et direkte drap.
- Vi vurderer å begrense burgerbuffets varighet etter tid og/eller drep.

# **Stammespesifikasjoner**

_Alle DEGEN-stammer har en spesiell evne ("SA"), som vil være konsistent på tvers av alle Nifty League-spill (live og fremtidig)._

## Liste over spesielle evner

- **Ape** - Kast bumerangbananer
- **Alien** - Teleport
- **Katt** - Slå ned og få flaggermuskraft og fartsøkning midlertidig
- **Frosk** - Tungegripekroken
- **Doge** - Doge myntrull
- **Menneske** - Kast dynamitt som eksploderer på kommando

## Romvesen

- Ved å trykke på SA-knappen kan Alien teleportere en kort avstand i den siktede retningen (venstre, høyre, opp, ned, diagonaler).
- Det er en energieksplosjon på det teleporterte stedet, og treffer motstandere som står i nærheten.

## Ape

- Et trykk på SA-knappen kaster en banan i den siktede retningen (venstre, høyre, opp, ned, diagonaler) til den treffer en motstander, treffer en kartdel eller flyr av kartet.
- Ved å trykke på SA-knappen igjen får bananen til å fly tilbake til DEGEN, noe som gjør det mulig å treffe en motstander igjen.
- Bananer kan slås med balltre og fly i den siktede retningen.

## Katt

- Å trykke på SA får katten til å kaste seg. Etter å ha kastet en kort periode, fikk katten makt.
- Styrket flaggermussving betyr at flaggermusen slår hardere.
- Styrket bevegelse betyr at katten løper raskere.
- Katter kan dobbelthoppe og hoppe i luften.

## Doge

- Ved å trykke og holde inne SA-knappen får dogen til å rulle.
- Å treffe en motstander med doge roll får dem til å fly oppover i rulleretning.
- Doge vil fly-rulle i den siktede retningen.
- Under doge roll kan retningen endres tre ganger til doge roll slutter.
- Doge roll slutter også etter en viss tid.

## Frosk

- Ved å trykke på SA-knappen får frosken til å skyte med tungen.
- Når tungen treffer en motstander, blir den motstanderen trukket til froskens retning og flyr litt lenger.
- Når tungen treffer et kartstykke, trekker froskene seg til det objektet (f.eks. vegger, tak osv.)
- Tungen kan skytes i den siktede retningen (venstre, høyre, opp, ned, diagonaler).

### Menneskelig

- Et trykk på SA-knappen kaster en bombe i den siktede retningen (venstre, høyre, opp, ned, diagonaler).
- Bomben har en flygende kurve og flyr ikke rett som bananer (hvis den ikke detoneres, forblir den på bakken).
- Bomben eksploderer etter en stund eller etter at SA-knappen trykkes en gang til.
- For øyeblikket kan bomben treffe en motstander ved å treffe den eller via eksplosjon.
- Bomber er den eneste SA som kan treffe selve DEGEN som kaster seg med eksplosjonen.
- Bomber kan treffes med balltre og fly i den siktede retningen.
- Vi planlegger å oppdatere spillet slik at bomben detonerer umiddelbart etter kontakt med en motstander. Hvis ingen motstander blir truffet, forblir den på bakken til den eksploderer automatisk eller etter å ha trykket på SA-knappen andre gang.

Bli med på vår **[Discord](https://discord.gg/niftyleague)** å gi tilbakemeldinger og ideer om hvordan vi kan forbedre spillet og ta det til neste nivå.
