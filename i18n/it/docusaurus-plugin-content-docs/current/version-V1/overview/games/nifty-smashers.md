---
id: nifty-distruttori
title: Smash ingegnosi
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Il tuo browser non supporta il tag video.
  </video>
  </div>

---

# **Informazioni generali**

Preparati alla rissa! La versione multiplayer locale di **[Nifty Smashers](https://nifty-league.com/games)** stata resa disponibile immediatamente al lancio, seguita dal multiplayer online.

Combatti all'interno della community e lancia più bat bonk sui tuoi amici che puoi! Nifty Smashers si ispira al classico gioco di Super Smash Bros in cui l'obiettivo è buttare i tuoi avversari fuori mappa per guadagnare punti.

Puoi giocare utilizzando la tastiera o qualsiasi altro controller compatibile (Playstation, Xbox, ecc.). Entra nella lobby di gioco e seleziona il tuo DEGEN per la battaglia.

## Punteggio

- Se un DEGEN viene colpito una volta e muore (cade fuori mappa) ottieni 1 punto.
- Se un DEGEN viene colpito più volte senza essere in grado di recuperare, ottieni punti ogni volta che viene colpito il DEGEN (indipendentemente dal fatto che i colpi precedenti siano stati effettuati da un altro DEGEN, quindi fai atterrare il mega-bonk finale per eliminarlo dalla mappa e rivendicare tutti i punti per il round).
- Più il tuo avversario viene colpito successivamente, più velocemente rimbalza e più punti guadagnerai per il bonking.
- L'ultimo colpo che uccide il DEGEN, ottiene tutti i punti combo.
- Attualmente non esiste un limite alla frequenza con cui un DEGEN può essere colpito (combo'), ma esiste un limite al numero di punti che puoi ottenere (max 3 punti: partita a 2 giocatori / max 5 punti: 3&partita a 4 giocatori ).
- Una partita a 2 giocatori richiede 5 punti per vincere un round.
- 3 & Le partite a 4 giocatori richiedono 10 punti per vincere un round.
- Le partite sono al meglio di 5 round.
- Se c'è un pareggio dopo il 5° round, i giocatori in parità passano a un round di morte improvvisa che gli altri giocatori possono guardare dalla linea laterale.

## Ritardo

- L'indicatore di ritardo mostra il ritardo (velocità del ping) della tua connessione.
- Il ritardo indica in genere che la velocità del ping è superiore a 100 ms.
- In generale, il ritardo è sempre presente ogni volta che c'è distanza fisica tra i giocatori su Internet. Maggiore è la distanza, maggiore è il ritardo.
- Esistono diverse tecniche che gli sviluppatori utilizzano per compensare e nascondere il ritardo.
- Abbiamo implementato una serie di queste tecniche di compensazione del ritardo che velano il ritardo per la migliore esperienza possibile.
- Abbiamo anche incorporato soluzioni con server in tutto il mondo in modo da poter abbinare i giocatori più vicini tra loro per ridurre al minimo il ritardo il più possibile. Se sei interessato a saperne di più su queste tecniche, dai un'occhiata a [questo post](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) che amiamo sulla compensazione del ritardo di Gabriel Gambetta.

## Lobby personalizzata

- Una lobby personalizzata può essere utilizzata per aprire una partita in una regione scelta. Il creatore della lobby può vedere un codice nella mappa della lobby che può essere condiviso con altri.
- Se un altro degen vuole entrare nella lobby, deve prima selezionare la regione corretta e quindi digitare il codice della lobby nella casella di input.
- Quando si utilizza un codice lobby personalizzato, la regione dovrebbe essere cambiata automaticamente.

## Cambiare le regioni

- Smasher è un gioco frenetico in cui latenza/ping è cruciale. Più la regione scelta è vicina alla posizione del giocatore, più basso sarà il ping.
- Dopo aver modificato la regione nel Web-GL o nell'app desktop, viene visualizzato il ping corrente.

# **Nozioni di base sulla battaglia**

## Consiglio generale

- Giocare con un controller altamente raccomandato (Playstation, Xbox o qualsiasi altro controller riconosciuto dal tuo PC/Mac).

## Altalene di pipistrello

- La mazza può essere oscillata in tutte le direzioni possibili: sinistra, destra, su, giù, diagonali.
- La mazza può essere oscillata facendo clic sul pulsante di attacco.
- Premendo più a lungo i pulsanti, la mazza colpisce più duramente.
- La mazza può essere oscillata stando in piedi, correndo o saltando.
- I giocatori possono premere a lungo il pulsante di attacco durante i salti: questo di solito è un buon modo per sorprendere i tuoi avversari.

## In movimento

- Come gioco 2D, le direzioni di movimento sono sinistra/destra.
- Le direzioni possono essere cambiate durante i salti/ruote (questo è molto più facile da realizzare usando un controller).

## Saltando

- L'altezza del salto può essere modificata premendo la durata del pulsante di salto.
- Le direzioni possono essere cambiate durante i salti o le cadute.

## Hamburger volante

- Prendere l'hamburger volante renderà la mazza del tuo DEGEN molto più forte - questo in genere si traduce in un'uccisione diretta.
- Stiamo considerando di limitare la durata del buff degli hamburger in base al tempo e/o alle uccisioni.

# **Specifiche della tribù**

_Tutte le tribù DEGEN hanno un'abilità speciale ("SA"), che sarà coerente in tutte le partite della Nifty League (live e future)._

## Elenco delle abilità speciali

- **Scimmia** - Lancia banane boomerang
- **Alieno** - Teletrasporto
- **Cat** - Balza e ottieni temporaneamente potenza del pipistrello e aumento della velocità
- **Rana** - Il rampino a lingua
- **Doge** - Rotolo di monete del Doge
- **Umano** - Lancia dinamite che esplodono a comando

## Alieno

- Premendo il pulsante SA, Alien può teletrasportarsi per una breve distanza nella direzione mirata (sinistra, destra, su, giù, diagonali).
- C'è un'esplosione di energia nella posizione del teletrasporto, colpendo gli avversari vicini.

## Scimmia

- Premendo il pulsante SA si lancia una banana nella direzione mirata (sinistra, destra, su, giù, diagonali) finché non colpisce un avversario, colpisce una parte della mappa o vola fuori dalla mappa.
- Premendo nuovamente il pulsante SA, la banana torna al DEGEN, rendendo possibile colpire di nuovo un avversario.
- Le banane possono essere colpite con una mazza e volare nella direzione mirata.

## Gatto

- Premendo il SA fa balzare il gatto. Dopo aver balzato per un breve periodo, il gatto si è potenziato.
- L'oscillazione della mazza potenziata significa che la mazza colpisce più forte.
- Il movimento potenziato significa che il gatto corre più veloce.
- I gatti possono fare un doppio salto e saltare a mezz'aria.

## Doge

- Premendo e tenendo premuto il pulsante SA, il doge roll.
- Colpire un avversario con un doge roll lo fa volare verso l'alto in direzione di rollio.
- Doge volerà-rotolare nella direzione mirata.
- Durante il doge roll, le direzioni possono essere cambiate tre volte fino al termine del doge roll.
- Anche il Doge roll termina dopo un certo tempo.

## Rana

- Premendo il pulsante SA, la Rana spara con la lingua.
- Quando la lingua colpisce un avversario, quell'avversario viene tirato nella direzione delle rane e vola un po' più lontano.
- Quando la lingua colpisce un pezzo di mappa, le rane si avvicinano a quell'oggetto (es. pareti, soffitti, ecc.)
- La lingua può essere sparata nella direzione mirata (sinistra, destra, su, giù, diagonali).

### Umano

- Premendo il pulsante SA si lancia una bomba nella direzione mirata (sinistra, destra, su, giù, diagonali).
- La bomba ha una curva volante e non vola dritta come le banane (se non fatta esplodere, resta a terra).
- La bomba esplode dopo un po' di tempo o dopo che il pulsante SA è stato premuto una seconda volta.
- Attualmente la bomba può colpire un avversario colpendolo o tramite esplosione.
- Le bombe sono le uniche SA in grado di colpire lo stesso DEGEN lanciatore con la sua esplosione.
- Le bombe possono essere colpite con una mazza e volare nella direzione mirata.
- Abbiamo in programma di aggiornare il gioco in modo che la bomba esploda immediatamente dopo il contatto con un avversario. Se nessun avversario viene colpito, rimane a terra finché non esplode automaticamente o dopo aver premuto il pulsante SA una seconda volta.

Unisciti al nostro **[Discord](https://discord.gg/niftyleague)** per fornire feedback e idee su come possiamo migliorare il gioco e portarlo al livello successivo.
