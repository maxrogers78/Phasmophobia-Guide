# Phasmophobia Guide

### Index

- [Phasmophobia Guide](#phasmophobia-guide)
  - [Index](#index)
- [Posesiones Malditas](#posesiones-malditas)
  - [Monkey Paw](#monkey-paw)
  - [Music Box](#music-box)
  - [Summoning Circle](#summoning-circle)
  - [Ouija Board](#ouija-board)
  - [Voodoo Doll](#voodoo-doll)
  - [Haunted Mirror](#haunted-mirror)
  - [Tarot Cards](#tarot-cards)
- [Comportamientos de Ghosts](#comportamientos-de-ghosts)
- [Ghosts](#ghosts)
  - [Spirit](#spirit)
  - [Wraith](#wraith)
  - [Phantom](#phantom)
  - [Poltergeist](#poltergeist)
  - [Banshee](#banshee)
  - [Jinn](#jinn)
  - [Mare](#mare)
  - [Revenant](#revenant)
  - [Shade](#shade)
  - [Demon](#demon)
  - [Yurei](#yurei)
  - [Oni](#oni)
  - [Yokai](#yokai)
  - [Hantu](#hantu)
  - [Goryo](#goryo)
  - [Myling](#myling)
  - [Onryo](#onryo)
  - [The Twins](#the-twins)
  - [Raiju](#raiju)
  - [Obake](#obake)
  - [The Mimic](#the-mimic)
  - [Moroi](#moroi)
  - [Deogen](#deogen)
  - [Thaye](#thaye)

# Posesiones Malditas

Todas las posesiones malditas, de una u otra manera, pueden iniciar una `cursed hunt`, la cual tiene las siguientes caracteristicas:

- Ignora cordura
- Ignora cooldown entre hunts
- Ignora crucifijos
- Ignora velas (Onryo)

### Monkey Paw

Otorga deseos al player, tantos positivos como negativos

La cantidad de deseos depende de la dificultad

POR RELLENAR

### Music Box

Obliga al ghost a cantar, revelando su ubicación

POR RELLENAR

### Summoning Circle

Invoca y atrapa al ghost en la ubicación (por muy poco tiempo), luego inicia una cursed hunt

### Ouija Board

Otorga la habilidad de comunicarse con el ghost a costo de cordura

POR RELLENAR

### Voodoo Doll

Contiene 10 pins alrededor del cuerpo, los cuales 9 de ellos forzan una interacción

El pin restante se ubica en el corazón, al activarse inicia una cursed hunt

Activar un pin normal drena por `5%` la cordura, mientras que utilizar el del corazón la drena por `10%`

### Haunted Mirror

Revela la ubicación de la ghost room a costo de cordura

Si la cordura del player llega a 0, el espejo se rompe e inicia una cursed hunt

### Tarot Cards

Contiene 10 cartas generadas de forma aleatoria, las cuales son:

- The Tower (20%):
  - Forza una interacción
  - Duplica actividad fantasma por `20 segundos`
- The Wheel of Fortune (20%):
  - Fuego verde: `+25%` de cordura
  - Fuego rojo: `-25%` de cordura
- The Fool (17%, 100% durante una hunt):
  - Selecciona una carta al azar, la muestra y luego se transforma en The Fool, causando que nada suceda
- The Devil (10%):
  - Forza un ghost event hacia el player más cerca del ghost
- Death (10%):
  - Forza una cursed hunt
- The Hermit (10%):
  - Teleporta al ghost a la ghost room
  - Lo atrapa allí durante 1 minuto
- The Sun (5%):
  - Restaura por completo la cordura del player
- The Moon (5%):
  - Drena por completo la cordura del player
- The High Priestess (2%):
  - Revive a un player muerto
  - Si ningún player ha muerto, revive al siguiente en morir
- The Hanged Man (1%):
  - Mata al player

# Comportamientos de Ghosts

Estos datos son por defecto, hay varios ghosts que cambian valores de este comportamiento

- Su velocidad de movimiento base es de `1.7 m/s`
- Pueden iniciar una hunt cuando el promedio de cordura es menor a `50%`
- Tienen un delay de `25 segundos` para iniciar una hunt cuando:
  - Termina una hunt
  - Se consume una carga del Crucifijo
- Durante un evento y/o hunt, interfieren con aparatos electrónicos en un radio de `10 metros`
- Durante una hunt aumenatarán su velocidad de movimiento de forma gradual mientras tengan a su presa a la vista, excepciones a esto son:
  - Deogen (depende de la distancia del player)
  - Hantu (depende de la temperatura)
  - Raiju (depende de los aparatos electrónicos)
  - Revenant (depende de si está viendo al player)
  - Thaye (depende de su edad)

# Ghosts

### Spirit

- Utilizar un incienso lo dejará sin poder iniciar una hunt durante `3 minutos`

### Wraith

- No deja pisadas en la sal
- Se puede teletransportar a un player, e iniciar una hunt en ese lugar
- Cuando se teletransporta a un player deja una lectura `EMF 2`

### Phantom

- Desaparece cuando se le toma una foto
- Puede escoger a un player y hacer roaming alrededor de el, permitiendole cambiar de ghost room
- Durante una hunt es poco visible (a diferencia del Oni)

### Poltergeist

- Puede hacer una "explosión" de items (baja mucho la cordura)
- Durante una hunt, lanzará items cerca suyo cada `0.5 segundos`

### Banshee

- Elige a un player "favorito", solo cazará a ese player (mientras esté en el mismo piso y dentro del edificio, de lo contrario atacará a cualquiera)
- Iniciará hunts según la cordura del favorito
- Si el favorito muere, escogerá a otro
- Tiene un `30%` de probabilidad de dar su grito particular mediante el Micrófono Parabólico
- Su ghost event favorito es cantar

### Jinn

- Jamás apagará los fusibles
- Durante una hunt, avanzará muy rápidamente apenas te vea desde lejos (solo con los fusibles encendidos), una vez se acerque a ti continuará con su velocidad normal
- Puede bajar tu cordura en un `25%` de forma random, al hacerlo, dejará SIEMPRE un valor `EMF 2` en los fusibles

### Mare

- Puede apagar un interruptor de luz INMEDIATAMENTE después de que el jugador lo encienda (aún cuando los fusibles están apagados)
- Jamás podrá encender un interruptor de luz
- Puede iniciar una hunt cuando el promedio de cordura en menor a `60%` si están a oscuras y `40%` si están en luz
- Su ghost event favorito es romper ampolletas

### Revenant

- En una hunt es muy lento cuando no detecta a alguien, apenas detecta a alguien avanzará SUPER rápido
- Durante una hunt, no aumentará su velocidad de movimiento mientras observa al player

### Shade

- Es muy tímido, haciendo que reduzca la probabilidad de realizar un ghost event y/o interacción
- No puede iniciar una hunt si al menos 1 player está en la ghost room
- Solo puede iniciar una hunt cuando el promedio de cordura es bajo a `35%`
- Su ghost event favorito es la bola de aire
- Al ser invocado a través del Summoning Circle se verá como una sombra negra

### Demon

- Puede iniciar una hunt con promedio de cordura bajo el `75%`, pero tiene una probabilidad baja de atacar a valor
- Puede iniciar una hunt cada `20 segundos`
- El radio de uso del crucifijo aumenta en un `50%`
- Utilizar un incienso en la ghost room lo dejará sin poder iniciar una hunt por solo `60 segundos`

### Yurei

- Puede drenar la cordura de un player cercano en un `15%`
- Puede cerrar una puerta completamente abierta (fuera de un evento y/o hunt)
- Si falla en cerrar la puerta, tocará la manilla 2 veces
- Es el único ghost que puede dejar lectura EMF en la puerta principal al cerrar una puerta
- Utilizar un incencio en la ghost room lo dejará encerrado ahí por `60 segundos`

### Oni

- No puede manifestarse como una bola de aire
- Se manifiesta más a menudo cuando hay varios player en la ghost room
- Durante una hunt es muy visible (a diferencia del Phantom/Ente)

### Yokai

- Puede iniciar una hunt con promedio de cordura bajo el `80%` si un player habla cerca de él
- Durante una hunt, le cuesta mucho detectar el equipamiento y voz del player

### Hantu

- Lento en temperaturas altas, rápido en temperaturas bajas
- Si los fusibles están apagados, se le puede ver su respiración durante una hunt (procurar no confundir con respiración de players)
- Durante una hunt, no aumentará su velocidad de movimiento mientras observa al player

### Goryo

- DOTS solo pueden ser reveladas mediante una cámara de video mientras la ghost room esté vacía
- No puede cambiar de ghost room

### Myling

- Durante una hunt es muy callado, pudiendo escucharlo hasta un rango de `12 metros`
- Habla más seguido mediante un micrófono parabólico
- Durante una hunt, sus pisadas y voz se detendrán apenas la linterna del player deje de parpadear

### Onryo

- No puede iniciar una hunt en un radio de `4 metros` de una vela encendida
- Si se deja una vela encencida sobre un crucifijo, priorizará apagar la vela antes que ocupar el crucifijo
- Al apagar por `3ra vez` una vela, comenzará una hunt ignorando el promedio de cordura

### The Twins

- Solo 1 ghost caza durante una hunt
- Durante una hunt, será más lento de lo normal o más rápido de lo normal
- Al momento de iniciar una hunt, no necesariamente cambiarán entre el rápido y el lento
- Pueden hacer 2 interacciones a la vez en diferentes rooms (ej: tocar una puerta y lanzar un objeto)
- Pueden iniciar una hunt en una room diferente a la ghost room

### Raiju

- Durante una hunt, aumentará su velocidad de movimiento cerca de aparatos electrónicos encendidos (aún cuando estén en el suelo)
- Interfiere los aparatos electrónicos en un radio de 15 metros durante un evento y/o hunt
- Durante una hunt, no aumentará su velocidad de movimiento mientras observa al player

### Obake

- Tiene un `75%` de probabilidad de dejar Ultravioleta
- Al dejar evidencia Ultravioleta, tiene `16.7%` de probabilidad de:
  - Dejar evidencia de mano con `6 dedos`
  - Dejar evidencia de interruptor con `2 dedos`
- Durante una hunt, tiene `6.66%` de probabilidad de cambiar de forma cada vez que parpadea

### The Mimic

- Escogerá a un ghost random e imitará su comportamiento
- Siempre mostrará orbes fantasma, pero no es una de sus 3 pruebas obligatorias
- No puede imitar DOTS de Goryo
- Puede cambiar de ghost cada `30 segundos - 2 minutos`, pero nunca durante una hunt

### Moroi

- Su velocidad de movimiento depende del promedio de cordura, entre menor sea, más rápido será
- Si responde a un player mediante la Spirit Box y/o Micrófono Parabólico lo maldecirá
- Un player maldito tendrá las siguientes caracteristicas:
  - Su cordura bajará el doble de rápido
  - Su cordura seguirá bajando aún estando en areas iluminadas
  - Su cordura no bajará estando fuera del edificio
  - Puede curarse utilizando Píldoras de Cordura
- Puede comportarse como un Gemelo (lento) si el promedio de cordura está entre `35%` y `50%`
- Utilizar un incienso durante una hunt lo aturdirá por más tiempo del normal:
  - Tier 1: `7.5 segundos`
  - Tier 2: `9 segundos`
  - Tier 3: `10.5 segundos`

### Deogen

- Durante una hunt, SIEMPRE sabrá en donde estás, no puedes esconderte
- Al estar lejos del player, se moverá muy rápido
- Al estar cerca del player, se moverá extremadamente lento
- Solo puede iniciar una hunt cuando el promedio de cordura es bajo a `40%`
- Al estar en menos de 1 metro de él utilizando la Spirit Box, dará un gruñido
- Durante una hunt, no aumentará su velocidad de movimiento mientras observa al player

### Thaye

- Es el único ghost que avanza de edad según avanza la partida
- Envejecerá cada `1-2 minutos` si un player está cerca de él
- Inicia joven, pudiendo iniciar una hunt con un promedio de cordura de `75%` y con velocidad de movimiento rápida
- Estando joven, será más activo, iniciando eventos e interacciones
- Cada vez que envejece, iniciará una hunt con menor frecuencia y será más lento (eliminando `0.175m/s` a su velocidad de movimiento)
- Se puede consultar su edad actual mediante un tablejo Ouija
- Durante una hunt, no aumentará su velocidad de movimiento mientras observa al player
