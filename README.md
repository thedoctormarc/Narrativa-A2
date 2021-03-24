# Narrativa-A2
En este assignment he trabajado la opción de: 
* Pruebas de sistemas de control de personajes y seguimiento de cámaras 

El personaje es un boxeador que se encuentra ante un enemigo inofensivo (dummy). 

Para el control del personaje, el esquema es el siguiente:

WASD = move
Q,E = dodge
Left Mouse = attack

Cabe decir que para cada acción existe una animación correspondiente. He decidido
que no se pueda atacar o esquivar mientras se mueve.

En cuanto a la cámara, he empleado el package de Cinemachine.

La cámara mira constantemente al enemigo, alrededor del pecho, como en un juego de peleas 3D 1vs1. 
Además, he alterado valores de "damping" para que el seguimiento tarde ligeramente en ajustar la cámara según se mueve el jugador.

Por último, he empleado el Cinemachine Impulse para simular un camera shake, el cual se manifiesta al atacar. 
