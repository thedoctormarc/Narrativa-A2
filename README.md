# Narrativa-A2
En este assignment he trabajado la opción de: 
* Pruebas de sistemas de control de personajes y seguimiento de cámaras 

El personaje es un boxeador que se encuentra ante un enemigo inofensivo (dummy). 

Para el control del personaje, el esquema es el siguiente:

WASD = move,
Q,E = dodge,
Left Mouse = attack

Cabe decir que para cada acción existe una animación correspondiente. 
Dichas animaciones provienen de Mixamo. 

He decidido que no se pueda atacar o esquivar mientras se mueve, pero que pueda moverse justo después de accionar un ataque 
o una esquiva, para proporcionar capacidad de reposicionamiento.

En cuanto a la cámara, he empleado el package de Cinemachine.

La cámara mira constantemente al enemigo, alrededor del pecho, como en un juego de peleas 3D 1vs1. 
Además, he alterado valores de "damping" para que el seguimiento tarde ligeramente en ajustar la cámara según se mueve el jugador.

Por último, he empleado el Cinemachine Impulse para simular un camera shake, el cual se manifiesta al atacar. 

Creo que el resultado es cercano a las propuestas de juegos de boxeo o lucha, aunque cabe tener en cuenta que el enemigo no tiene
comportamiento alguno, en cuyo caso podría atacar y habría un nuevo camera shake en todas direcciones, en caso de que te golpee. 
