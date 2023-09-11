# Juego de Ajedrez en Python con Pygame

El juego de ajedrez es un juego de estrategia de dos jugadores que se juega en un tablero cuadriculado. Cada jugador controla un conjunto de piezas con diferentes movimientos y el objetivo es poner al rey del oponente en jaque mate, lo que significa que el rey no tiene movimientos legales para escapar del ataque. Aquí se presenta una implementación simple del juego de ajedrez en Python utilizando la biblioteca Pygame.

## Características del Juego

- **Tablero de Ajedrez:** El juego se juega en un tablero de 8x8 cuadrados, alternando entre casillas negras y blancas.

- **Piezas:** Cada jugador tiene 16 piezas, incluyendo peones, torres, caballos, alfiles, la reina y el rey. Cada tipo de pieza tiene movimientos específicos.

- **Movimientos Legales:** Los jugadores seleccionan una pieza y eligen una casilla de destino válida. El juego verifica si el movimiento es legal según las reglas del ajedrez.

- **Turnos:** El juego tiene un sistema de turnos que permite a los jugadores realizar movimientos alternativos.

- **Detección de Jaque:** El juego verifica si un jugador está en jaque (amenazado por una pieza enemiga). Si el rey está en jaque, el jugador debe encontrar una forma de proteger al rey o moverlo fuera del peligro.

- **Detección de Jaque Mate:** El juego verifica si un jugador ha quedado en jaque mate, lo que significa que no puede mover al rey de manera legal para escapar del jaque. En tal caso, el juego termina.

- **Detección de Empate:** El juego verifica condiciones de empate, como el empate por regla de los 50 movimientos o el empate por repetición de posiciones.

- **Interfaz de Usuario:** El juego tiene una interfaz de usuario que permite a los jugadores seleccionar y mover las piezas utilizando el mouse.

## Cómo Jugar

1. Clona o descarga este repositorio en tu computadora.

2. Asegúrate de tener Python y la biblioteca Pygame instalados.

3. Ejecuta el juego ejecutando el archivo principal.

4. Selecciona una pieza haciendo clic en ella y, a continuación, selecciona una casilla de destino válida para moverla.

5. El juego verificará los movimientos legales y te indicará si estás en jaque o jaque mate.

## Personalización

Puedes personalizar el juego de ajedrez agregando características adicionales, mejorando la interfaz de usuario o ajustando las reglas según tus preferencias.

## Créditos

Este juego de ajedrez en Python con Pygame fue desarrollado por [Tu Nombre] y se basa en el conocimiento y tutoriales disponibles en línea sobre programación de juegos y ajedrez.

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.

2. Crea una rama para tu contribución: `git checkout -b mi-contribucion`.

3. Haz tus cambios y crea un commit: `git commit -m "Agrega mi contribución"`.

4. Sube tus cambios a tu repositorio: `git push origin mi-contribucion`.

5. Crea un pull request en GitHub.

![python](https://github.com/Hotbones/Ajedrez-python/assets/105388226/3485aee0-f298-4f78-8ce5-45ca0235b520)

