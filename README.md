# React-ive Snake
### Descripción
En este repositorio realicé una versión de Snake hecha completamente con React directamente desde el navegador, utilizando Babel a través de CDN en un solo archivo.

Este repositorio fue hecho principalmente para entender cómo funciona React, por lo que lo único que se utilizó fue el archivo `index.html`. Por ende, lo único necesario para jugar mi versión de Snake es un servidor simple que pueda servir el `index.html`, tal como el servidor integrado de python `python3 -m http.server` o cualquier otro de esa índole.

### Instrucciones
Teniendo ya algún servidor sirviendo (valga la redundancia) el index, ahí se podrá ver el menú principal de todo el juego, que mostrará: el tablero, el puntaje más alto alcanzado, algunas configuraciones de dificultad (velocidad y tamaño del tablero) y el botón de comenzar justo debajo del tablero.

Para jugar, simplemente se debe de presionar ese último botón y automáticamente empezará el juego. Únicamente se detendrá hasta que el jugador choque contra sí mismo, choque contra una pared, pause el juego o bien gane haciendo que la serpiente ocupe toda la longitud posible del tablero.
