---
id: fiffiga smashers
title: Snygga smashers
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Din webbläsare stöder inte videotaggen.
  </video>
  </div>

---

# **Generell information**

Gör dig redo att bråka! Den lokala flerspelarversionen av **[Nifty Smashers](https://nifty-league.com/games)** gjordes tillgänglig direkt vid lanseringen följt av online-multiplayer.

Kämpa ut bland samhället och få så många batbonks på dina vänner som du kan! Nifty Smashers hämtar inspiration från det klassiska Super Smash Bros-spelet där målet är att slå dina motståndare från kartan för att få poäng.

Du kan spela med ditt tangentbord eller någon annan kompatibel handkontroll (Playstation, Xbox, etc.). Gå in i spellobbyn och välj din DEGEN för strid.

## Poängsättning

- Om en DEGEN träffas en gång och dör (faller av kartan) får du 1 poäng.
- Om en DEGEN träffas flera gånger utan att kunna återhämta sig, får du poäng lika ofta som DEGEN träffas (oavsett om tidigare träffar gjordes av en annan DEGEN - så landa den sista megabonken för att slå dem från kartan och göra anspråk på alla poäng för omgången).
- Ju mer din motståndare successivt tjats, desto snabbare studsar de runt och desto fler poäng får du för att tjata.
- Den sista träffen som dödar DEGEN, får alla kombinationspoäng.
- För närvarande finns det inget tak för hur ofta en DEGEN kan träffas (kombineras), men det finns ett tak för antalet poäng du kan få (max 3 poäng: 2-spelares match / max 5 poäng: 3&4-spelares match ).
- En match med 2 spelare kräver 5 poäng för att vinna en omgång.
- 3 & 4-spelares matcher kräver 10 poäng för att vinna en omgång.
- Matcher är bäst av 5 omgångar.
- Om det blir oavgjort efter den 5:e omgången går de oavgjorda spelarna in i en sudden death-runda som de andra spelarna får se från sidlinjen.

## Eftersläpning

- Fördröjningsindikatorn visar fördröjningen (pinghastighet) för din anslutning.
- Fördröjning indikerar typiskt att din pinghastighet är över 100 ms.
- Generellt sett är lagg alltid närvarande när det finns fysiskt avstånd mellan spelarna på internet. Ju större avstånd, desto större fördröjning.
- Det finns olika tekniker som utvecklare använder för att kompensera och dölja eftersläpningen.
- Vi har implementerat ett antal av dessa fördröjningskompensationstekniker som döljer fördröjningen för bästa möjliga upplevelse.
- Vi har även införlivat lösningar med servrar över hela världen så att vi kan matcha spelare närmast varandra för att minimera eftersläpningen så mycket som möjligt. Om du är intresserad av att lära dig mer om dessa tekniker, kolla in [detta inlägg](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) vi älskar på Lagkompensation av Gabriel Gambetta.

## Anpassad lobby

- En anpassad lobby kan användas för att öppna en match i en vald region. Skaparen av lobbyn kan se en kod i lobbykartan som kan delas med andra.
- Om en annan degen vill gå med i lobbyn måste han först välja rätt region och sedan skriva in lobbykoden i inmatningsrutan.
- När du använder en anpassad lobbykod bör regionen bytas automatiskt.

## Ändra regioner

- Smasher är ett snabbt spel där latens/ping är avgörande. Ju närmare den valda regionen är spelarens plats, desto lägre ping.
- Efter att ha ändrat region i Web-GL eller Desktop App, visas den aktuella pingen.

# **Battle Basics**

## Allmänna råd

- Att spela med en handkontroll rekommenderas starkt (Playstation, Xbox eller någon annan kontroll som känns igen av din PC/Mac).

## Fladdermus gungor

- Fladdermusen kan svängas i alla möjliga riktningar: vänster, höger, upp, ner, diagonaler.
- Fladdermusen kan svängas genom att klicka på attackknappen.
- Längre knapptryckningar gör att fladdermusen slår hårdare.
- Fladdermusen kan svängas när du står, springer eller hoppar.
- Spelare kan trycka länge på attackknappen under hopp - detta är vanligtvis ett bra sätt att överraska din(a) motståndare(r).

## Rör på sig

- Som ett 2D-spel är rörliga riktningar vänster/höger.
- Riktningen kan ändras under hopp/tumbling (detta är mycket lättare att åstadkomma med en kontroller).

## Hoppar

- Hopphöjden kan ändras genom att trycka på hoppknappens varaktighet.
- Riktningen kan ändras under hopp/tumbling.

## Flygande hamburgare

- Att fånga den flygande hamburgaren kommer att göra din DEGENs slagträ mycket starkare - detta resulterar vanligtvis i en direkt död.
- Vi överväger att begränsa hamburgerbufféns varaktighet genom tid och/eller död.

# **Stamspecifikationer**

_Alla DEGEN-stammar har en speciell förmåga (”SA”), som kommer att vara konsekvent i alla Nifty League-spel (live och framtid)._

## Lista över speciella förmågor

- **Ape** - Kasta bumerangbananer
- **Alien** - Teleportera
- **Katt** - Släng och få fladdermuskraft och fartökning tillfälligt
- **Groda** - Tunggripkroken
- **Doge** - Doge myntrulle
- **Människan** - Kasta dynamit som exploderar på kommando

## Utomjording

- Genom att trycka på SA-knappen kan Alien teleportera en kort sträcka i den riktade riktningen (vänster, höger, upp, ner, diagonaler).
- Det är en energiexplosion på den teleporterade platsen och träffar motståndare som står nära.

## Apa

- Ett tryck på SA-knappen kastar en banan i den riktade riktningen (vänster, höger, upp, ner, diagonaler) tills den träffar en motståndare, träffar en kartdel eller flyger från kartan.
- Om du trycker på SA-knappen igen får bananen att flyga tillbaka till DEGEN, vilket gör det möjligt att träffa en motståndare igen.
- Bananer kan slås med ett slagträ och flyga i den riktade riktningen.

## Katt

- Att trycka på SA får katten att kasta sig. Efter att ha slagit en kort stund fick katten kraft.
- Befogat fladdermussving betyder att fladdermusen slår hårdare.
- Befogad rörelse betyder att katten springer snabbare.
- Katter kan dubbelhoppa och hoppa i luften.

## Doge

- Genom att trycka och hålla ner SA-knappen får dogen att rulla.
- Att slå en motståndare med doge roll gör att de flyger uppåt i rollriktningen.
- Doge kommer att fly-rulla i den riktade riktningen.
- Under doge roll kan riktningen ändras tre gånger tills doge roll slutar.
- Doge roll slutar också efter en viss tid.

## Groda

- Genom att trycka på SA-knappen får grodan att skjuta tungan.
- När tungan träffar en motståndare, dras den mot grodornas riktning och flyger lite längre.
- När tungan träffar en kartbit drar grodorna sig till det föremålet (t.ex. väggar, tak, etc.)
- Tungan kan skjutas i den riktade riktningen (vänster, höger, upp, ner, diagonaler).

### Mänsklig

- Ett tryck på SA-knappen kastar en bomb i den riktade riktningen (vänster, höger, upp, ner, diagonaler).
- Bomben har en flygande kurva och flyger inte rakt som bananer (om den inte detoneras stannar den på marken).
- Bomben exploderar efter en tid eller efter att SA-knappen trycks in en andra gång.
- För närvarande kan bomben träffa en motståndare genom att träffa den eller via explosion.
- Bomber är den enda SA som kan träffa den kastande DEGEN själv med sin explosion.
- Bomber kan träffas med ett slagträ och flyga i den riktade riktningen.
- Vi planerar att uppdatera spelet så att bomben detonerar direkt efter kontakt med en motståndare. Om ingen motståndare träffas, stannar den på marken tills den exploderar automatiskt eller efter att ha tryckt på SA-knappen andra gången.

Gå med i vår **[Discord](https://discord.gg/niftyleague)** att ge feedback och idéer om hur vi kan förbättra spelet och ta det till nästa nivå.
