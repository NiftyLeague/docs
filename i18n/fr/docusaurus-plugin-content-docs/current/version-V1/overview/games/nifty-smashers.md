---
id: astucieux
title: Casseurs astucieux
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Votre navigateur ne prend pas en charge la balise vidéo.
  </video>
  </div>

---

# **Informations générales**

Préparez-vous à vous battre ! La version multijoueur locale de **[Nifty Smashers](https://nifty-league.com/games)** été mise à disposition immédiatement au lancement, suivie du multijoueur en ligne.

Battez-vous au sein de la communauté et obtenez autant de bat bonks sur vos amis que vous le pouvez ! Nifty Smashers s'inspire du jeu classique Super Smash Bros où l'objectif est de faire tomber vos adversaires de la carte pour marquer des points.

Vous pouvez jouer à l'aide de votre clavier ou de toute autre manette compatible (Playstation, Xbox, etc.). Entrez dans le lobby du jeu et sélectionnez votre DEGEN pour le combat.

## Notation

- Si un DEGEN est touché une fois et meurt (tombe de la carte), vous obtenez 1 point.
- Si un DEGEN est touché plusieurs fois sans pouvoir récupérer, vous obtenez des points aussi souvent que le DEGEN est touché (peu importe si les coups précédents ont été effectués par un autre DEGEN - alors atterrissez le méga-bonk final pour les frapper hors de la carte et réclamer tous les points du tour).
- Plus votre adversaire est successivement bonké, plus il rebondit vite et plus vous marquerez de points pour ce bonk.
- Le dernier coup qui tue le DEGEN obtient tous les points de combo.
- Actuellement, il n'y a pas de limite à la fréquence à laquelle un DEGEN peut être touché (combiné), mais il y a une limite au nombre de points que vous pouvez obtenir (max 3pts : match à 2 joueurs / max 5pts : 3&match à 4 joueurs ).
- Un match à 2 joueurs nécessite 5 points pour gagner une manche.
- 3 & matchs à 4 joueurs nécessitent 10 points pour gagner une manche.
- Les matchs sont au meilleur des 5 rounds.
- S'il y a égalité après le 5e tour, les joueurs à égalité entrent dans un tour de mort subite que les autres joueurs peuvent regarder depuis la ligne de touche.

## Décalage

- L'indicateur de décalage indique le décalage (vitesse de ping) de votre connexion.
- Le décalage indique généralement que votre vitesse de ping est supérieure à 100 ms.
- D'une manière générale, le décalage est toujours présent dès qu'il y a une distance physique entre les joueurs sur Internet. Plus la distance est grande, plus le décalage est important.
- Il existe différentes techniques que les développeurs utilisent pour compenser et masquer le décalage.
- Nous avons mis en place un certain nombre de ces techniques de compensation de décalage qui masquent le décalage pour la meilleure expérience possible.
- Nous avons également intégré des solutions avec des serveurs partout dans le monde afin que nous puissions faire correspondre les joueurs les plus proches les uns des autres afin de minimiser autant que possible le décalage. Si vous souhaitez en savoir plus sur ces techniques, consultez [ce post](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) nous aimons sur Lag Compensation par Gabriel Gambetta.

## Lobby personnalisé

- Un lobby personnalisé peut être utilisé pour ouvrir un match dans une région choisie. Le créateur du lobby peut voir un code dans la carte du lobby qui peut être partagé avec d'autres.
- Si un autre degen souhaite rejoindre le lobby, il doit d'abord sélectionner la bonne région, puis saisir le code du lobby dans la zone de saisie.
- Lors de l'utilisation d'un code de lobby personnalisé, la région doit être changée automatiquement.

## Changer de région

- Smasher est un jeu rapide où la latence/le ping sont cruciaux. Plus la région choisie est proche de l'emplacement du joueur, plus le ping est faible.
- Après avoir changé la région dans le Web-GL ou l'application de bureau, le ping actuel s'affiche.

# **Bases de la bataille**

## Conseils généraux

- Jouer avec une manette fortement recommandée (Playstation, Xbox ou toute autre manette reconnue par votre PC/Mac).

## Balançoires de chauve-souris

- La batte peut être balancée dans toutes les directions possibles : gauche, droite, haut, bas, diagonales.
- La chauve-souris peut être balancée en cliquant sur le bouton d'attaque.
- Des pressions plus longues sur les boutons rendent la chauve-souris plus forte.
- La chauve-souris peut être balancée debout, en courant ou en sautant.
- Les joueurs peuvent appuyer longuement sur le bouton d'attaque pendant les sauts - c'est généralement un bon moyen de surprendre votre ou vos adversaires.

## En mouvement

- En tant que jeu 2D, les directions de déplacement sont gauche/droite.
- Les directions peuvent être modifiées pendant les sauts/culbutes (c'est beaucoup plus facile à accomplir à l'aide d'un contrôleur).

## Sauter

- La hauteur de saut peut être modifiée en appuyant sur la durée du bouton de saut.
- Les directions peuvent être modifiées pendant les sauts/culbutes.

## Hamburger volant

- Attraper le hamburger volant rendra la batte de votre DEGEN beaucoup plus forte - cela se traduit généralement par une mise à mort directe.
- Nous envisageons de limiter la durée du buff des hamburgers en fonction du temps et/ou de la mort.

# **Spécificités de la tribu**

_Toutes les tribus DEGEN ont une capacité spéciale ("SA"), qui sera cohérente dans tous les jeux Nifty League (en direct et futurs)._

## Liste des capacités spéciales

- **Ape** - Lancer des bananes boomerang
- **Extraterrestre** - Téléportation
- **Cat** - Bondissez et obtenez temporairement la puissance et la vitesse de la chauve-souris
- **Frog** - Le crochet de la languette
- **Doge** - Rouleau de pièces Doge
- **Humain** - Lancer des dynamites qui explosent sur commande

## Extraterrestre

- En appuyant sur le bouton SA, Alien peut se téléporter sur une courte distance dans la direction visée (gauche, droite, haut, bas, diagonales).
- Il y a une explosion d'énergie à l'emplacement téléporté, frappant les adversaires qui se tiennent à proximité.

## Singe

- Appuyer sur le bouton SA lance une banane dans la direction visée (gauche, droite, haut, bas, diagonales) jusqu'à ce qu'elle touche un adversaire, touche une partie de la carte ou vole hors de la carte.
- Une nouvelle pression sur le bouton SA fait voler la banane vers le DEGEN, ce qui permet de frapper à nouveau un adversaire.
- Les bananes peuvent être frappées avec une batte et voler dans la direction visée.

## Chat

- Appuyer sur SA fait bondir le chat. Après avoir bondi pendant une courte durée, le chat se renforce.
- Le swing de chauve-souris renforcé signifie que la chauve-souris frappe plus fort.
- Un mouvement puissant signifie que le chat court plus vite.
- Les chats peuvent faire un double saut et sauter dans les airs.

## Doge

- Appuyer et maintenir le bouton SA fait rouler le doge.
- Frapper un adversaire avec un roulement de doge le fait voler vers le haut dans la direction du roulement.
- Doge volera-roulera dans la direction visée.
- Pendant le jet de doge, les directions peuvent être changées trois fois jusqu'à ce que le jet de doge se termine.
- Doge roll se termine également après un certain temps.

## Grenouille

- En appuyant sur le bouton SA, la grenouille tire sur sa langue.
- Lorsque la langue frappe un adversaire, cet adversaire est tiré dans la direction des grenouilles et vole un peu plus loin.
- Lorsque la langue touche un morceau de carte, les grenouilles se tirent vers cet objet (par exemple, murs, plafonds, etc.)
- La langue peut être tirée dans la direction visée (gauche, droite, haut, bas, diagonales).

### Humain

- Appuyer sur le bouton SA lance une bombe dans la direction visée (gauche, droite, haut, bas, diagonales).
- La bombe a une courbe de vol et ne vole pas droit comme des bananes (si elle n'explose pas, elle reste au sol).
- La bombe explose après un certain temps ou après avoir appuyé une deuxième fois sur le bouton SA.
- Actuellement, la bombe peut toucher un adversaire en le frappant ou via une explosion.
- Les bombes sont les seuls SA qui peuvent frapper le DEGEN lanceur lui-même avec son explosion.
- Les bombes peuvent être frappées avec une batte et voler dans la direction visée.
- Nous prévoyons de mettre à jour le jeu afin que la bombe explose immédiatement après un contact avec un adversaire. Si aucun adversaire n'est touché, il reste au sol jusqu'à ce qu'il explose automatiquement ou après avoir appuyé une deuxième fois sur le bouton SA.

Veuillez rejoindre notre **[Discord](https://discord.gg/niftyleague)** pour fournir des commentaires et des idées sur la façon dont nous pouvons améliorer le jeu et le faire passer au niveau supérieur.
