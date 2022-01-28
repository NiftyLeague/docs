---
id: ingeniosos aplastadores
title: Aplastadores ingeniosos
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Su navegador no soporta la etiqueta de vídeo.
  </video>
  </div>

---

# **Información general**

¡Prepárate para pelear! La versión multijugador local de **[Nifty Smashers](https://nifty-league.com/games)** estuvo disponible inmediatamente después del lanzamiento, seguida del multijugador en línea.

¡Combate entre la comunidad y consigue tantos bat bonks con tus amigos como puedas! Nifty Smashers se inspira en el clásico juego Super Smash Bros, donde el objetivo es eliminar a tus oponentes del mapa para sumar puntos.

Puedes jugar usando tu teclado o cualquier otro controlador compatible (Playstation, Xbox, etc.). Ingresa al lobby del juego y selecciona tu DEGEN para la batalla.

## Puntuación

- Si un DEGEN es golpeado una vez y muere (se cae del mapa), obtienes 1 punto.
- Si se golpea un DEGEN varias veces sin poder recuperarse, obtienes puntos con la misma frecuencia con la que se golpea el DEGEN (independientemente de si otro DEGEN realizó los golpes anteriores, así que consigue el mega-bonk final para sacarlos del mapa y reclamar todos los puntos de la ronda).
- Cuanto más golpee sucesivamente a su oponente, más rápido rebotará y más puntos obtendrá por golpear.
- El último golpe que mata al DEGEN obtiene todos los puntos de combo.
- Actualmente no hay un límite en la frecuencia con la que se puede golpear un DEGEN (combinado), pero hay un límite en la cantidad de puntos que puede obtener (máximo 3 puntos: partido de 2 jugadores / máximo 5 puntos: 3&partido de 4 jugadores ).
- Un partido de 2 jugadores requiere 5 puntos para ganar una ronda.
- 3 & Los partidos de 4 jugadores requieren 10 puntos para ganar una ronda.
- Los partidos son al mejor de 5 rondas.
- Si hay un empate después de la quinta ronda, los jugadores empatados pasan a una ronda de muerte súbita que los otros jugadores pueden ver desde la banca.

## Retraso

- El indicador de retraso muestra el retraso (velocidad de ping) de su conexión.
- El retraso normalmente indica que su velocidad de ping es superior a 100 ms.
- En términos generales, el retraso siempre está presente cuando hay distancia física entre los jugadores en Internet. Cuanto mayor es la distancia, mayor es el retraso.
- Existen diferentes técnicas que utilizan los desarrolladores para compensar y ocultar el retraso.
- Hemos implementado varias de estas técnicas de compensación de retraso que velan el retraso para obtener la mejor experiencia posible.
- También hemos incorporado soluciones con servidores en todo el mundo para que podamos emparejar a los jugadores más cercanos entre sí para minimizar el retraso tanto como sea posible. Si está interesado en obtener más información sobre estas técnicas, consulte [esta publicación](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) nos encanta sobre Lag Compensation de Gabriel Gambetta.

## Vestíbulo personalizado

- Se puede usar un lobby personalizado para abrir un partido en una región elegida. El creador del lobby puede ver un código en el mapa del lobby que se puede compartir con otros.
- Si otro degen quiere unirse al lobby, primero debe seleccionar la región correcta y luego escribir el código del lobby en el cuadro de entrada.
- Al usar un código de lobby personalizado, la región debe cambiarse automáticamente.

## Cambio de regiones

- Smasher es un juego de ritmo rápido donde la latencia/ping es crucial. Cuanto más cerca esté la región elegida de la ubicación del jugador, menor será el ping.
- Después de cambiar la región en Web-GL o la aplicación de escritorio, se muestra el ping actual.

# **Conceptos básicos de batalla**

## Consejos generales

- Se recomienda jugar con un controlador (Playstation, Xbox o cualquier otro controlador reconocido por su PC/Mac).

## Columpios de bate

- El bate se puede balancear en todas las direcciones posibles: izquierda, derecha, arriba, abajo, diagonales.
- El bate se puede balancear haciendo clic en el botón de ataque.
- Las pulsaciones más largas de los botones hacen que el bate golpee con más fuerza.
- El bate se puede balancear mientras está de pie, corriendo o saltando.
- Los jugadores pueden presionar prolongadamente el botón de ataque durante los saltos; esta suele ser una buena forma de sorprender a tu(s) oponente(s).

## Moviente

- Como juego 2D, las direcciones de movimiento son izquierda/derecha.
- Las direcciones se pueden cambiar durante los saltos/caídas (esto es mucho más fácil de lograr usando un controlador).

## saltando

- La altura del salto se puede modificar presionando la duración del botón de salto.
- Las direcciones se pueden cambiar durante los saltos/caídas.

## Hamburguesa voladora

- Atrapar la hamburguesa voladora hará que el bate de tu DEGEN golpee mucho más fuerte; esto generalmente resulta en una muerte directa.
- Estamos considerando limitar la duración del beneficio de hamburguesas por tiempo y/o muerte.

# **Especificaciones de la tribu**

_Todas las tribus DEGEN tienen una habilidad especial ("SA"), que será consistente en todos los juegos de Nifty League (en vivo y futuros)._

## Lista de habilidades especiales

- **Ape** - Lanza bananas boomerang
- **Alien** - Teletransporte
- **Cat** : salta y obtén potencia de bate y aumento de velocidad temporalmente
- **Rana** - El gancho de la lengua
- **Doge** - Rollo de moneda Doge
- **Humano** - Lanza dinamitas que explotan al mando

## Extraterrestre

- Al presionar el botón SA, Alien puede teletransportarse una distancia corta en la dirección deseada (izquierda, derecha, arriba, abajo, diagonales).
- Hay una explosión de energía en el lugar teletransportado, que golpea a los oponentes que se encuentran cerca.

## Mono

- Al presionar el botón SA, se lanza una banana en la dirección deseada (izquierda, derecha, arriba, abajo, diagonales) hasta que golpea a un oponente, golpea una parte del mapa o sale volando del mapa.
- Presionar el botón SA nuevamente hace que el plátano vuele de regreso al DEGEN, lo que permite golpear a un oponente nuevamente.
- Los plátanos se pueden golpear con un bate y volar en la dirección deseada.

## Gato

- Presionar el SA hace que el gato salte. Después de abalanzarse durante un breve período, el gato se fortaleció.
- El swing de bate potenciado significa que el bate golpea más fuerte.
- El movimiento potenciado significa que el gato corre más rápido.
- Los gatos pueden hacer doble salto y saltar en el aire.

## Dux

- Presionar y mantener presionado el botón SA hace que el dux ruede.
- Golpear a un oponente con Doge Roll lo hace volar hacia arriba en la dirección de Roll.
- Doge volará rodando en la dirección deseada.
- Durante la tirada de doge, las direcciones se pueden cambiar tres veces hasta que finalice la tirada de doge.
- Doge roll también termina después de cierto tiempo.

## Rana

- Al presionar el botón SA, la rana dispara su lengua.
- Cuando la lengua golpea a un oponente, ese oponente es atraído hacia la dirección de la rana y vuela un poco más lejos.
- Cuando la lengua golpea una pieza del mapa, la rana se empuja hacia ese objeto (por ejemplo, paredes, techos, etc.)
- La lengua se puede disparar en la dirección apuntada (izquierda, derecha, arriba, abajo, diagonales).

### Humano

- Presionar el botón SA lanza una bomba en la dirección apuntada (izquierda, derecha, arriba, abajo, diagonales).
- La bomba tiene una curva de vuelo y no vuela en línea recta como los plátanos (si no se detona, se queda en el suelo).
- La bomba explota después de un tiempo o después de presionar el botón SA por segunda vez.
- Actualmente, la bomba puede golpear a un oponente golpeándolo o mediante una explosión.
- Las bombas son las únicas SA que pueden golpear al propio DEGEN arrojadizo con su explosión.
- Las bombas se pueden golpear con un bate y volar en la dirección deseada.
- Planeamos actualizar el juego para que la bomba explote inmediatamente después del contacto con un oponente. Si no se golpea a ningún oponente, permanece en el suelo hasta que explota automáticamente o después de presionar el botón SA por segunda vez.

Únase a nuestro **[Discord](https://discord.gg/niftyleague)** para brindar comentarios e ideas sobre cómo podemos mejorar el juego y llevarlo al siguiente nivel.
