# TP5 de Programación de Video Juegos 2: Nivel 3D

## Metodología

|                        |                                   |
| ---------------------- | --------------------------------- |
| Integrantes por grupo: | 1                                 |
| Se aprueba con         | 6                                 |
| Fecha de entrega       | Jueves 17 de Septiembre, 23:59 hs |
| Fecha de re-entrega    | Jueves 24 de Septiembre, 23:59 hs |


### Objetivos

- Aprender las bases de a diseñar un nivel 3D que tenga sentido con el juego que están haciendo
- Aprender como agregarle efectos visuales al nivel

Recuerden que, por lo general, la solución más simple es la mejor.

----

## Entrega

### Código

Todo lo van a resolver en un repositorio de GitHub. Tiene que haber una `tag` que se llame `tp5`. Ese commit es el que voy a corregir.

 Antes de la fecha limite me tienen que mandar el link a la tag `tp5` por mail a <me@diegofreijo.com>.
 
### Defensa

Les voy a estar mandando horarios para que cada uno se conecte y tengamos la devolución por Google Meet.

----

## Requerimientos

En el TP4 ya hicieron al personaje que el jugador usa para interactuar con el nivel. Ahora hay que hacer ese nivel. 

Los objetivos genéricos del TP son que entreguen el nivel cumpliendo con:

1. Actualicen la ficha técnica con el gameplay que esperan que haya en el nivel
2. Que el nivel permita desarrollar el gameplay que pusieron en la ficha técnica
3. Que tenga un nivel mínimo de efectos visuales, para "aumentar el game feel"
4. Además, mejorar los efectos visuales del TP4


### 1. Diseño y ficha técnica

La función mas importante del nivel es que permita que el juego se desarrolle. Un nivel lindo que no le permite al jugador hacer lo que debe hacer, no sirve. 

Para saber que evaluarles, lo primero que necesito es que me digan que hicieron. Para ello voy a necesitar que vuelvan a agregar el archivo con la ficha técnica que armaron para el TP4 pero esta vez además le agreguen un apartado nuevo, TP5. Ahí van a explicar el objetivo del nivel que desarrollaron.

Si ven que hace falta, pueden también comentarme cual es el objetivo de todo el juego aunque este cuatrimestre solamente van a trabajar en un nivel solo. Puede servir para comunicar mejor la idea que tienen en la cabeza.

Viendo sus TPs hasta ahora, los objetivos me imagino que van a venir más o menos por estos lados:

- Los que van hacia la acción: Matar a todos los enemigos, que no te maten y llegar a la salida (Vampy, Fede)
- Los que van hacia el sigilo: Encontrar objetos desparramados por el nivel, mientras hay uno o varios bichos queriendo comerte (Thiago, Lucas, Estefy, Lola)

Alguno puede que quiera hacer un blend de direcciones, o agregar otro tipo de objetivo. Siéntanse libres de hacerlo. Puse esos puntos como ejemplos para que se den una idea de lo que pido. 

### 2. Armado del nivel

Asegúrense que el nivel permita que el jugador logre los objetivos planteados. Y que no tenga forma de hacer trampa, abusar de algún exploit, etc.

- Que tenga un camino posible para hacer lo que debe hacer
- Que los pickups estén en lugares donde tenga sentido que estén
- Que la cantidad de pickups sea suficiente para que pueda jugar, pero no demasiados como para que no se le haga muy fácil. Acá me refiero mas que nada a los pickups que dan municiones, salud, maná, etc
- Que los ítems necesarios para desbloquear puertas estén. Y permitan desbloquear las puertas (llaves, documentos, etc)
- Que el jugador no pueda atravesar / noclippear una pared, para que no se saltee el nivel y vaya de una a la salida

No pido mas que una escena. Pero si quieren usar mas de una, pueden hacerlo.

### 3. Embelesamiento del nivel

Una vez que el nivel se pueda jugar, es hora de hacerlo lindo. Quiero que vuelvan a leer la oración anterior dos veces más. No se pongan a hacer un nivel lindo si no es funcional, o van a laburar al cuete si hay que corregir algo que no anda.

La idea es mejorar el game feel. Que la escena transmita lo que tiene que transmitir: realista, lindo, tenebroso, suspenso, etc. Para ello, espero como mínimo:

- Sistema de luces "razonable". Como dije en clase, no espero una escena con el mejor sistema de luces. Solamente espero que:
  - si hay una lámpara o una llama o una bola de hielo, pongan una luz de point acorde
  - si hay un farol en la calle o una linterna, pongan una luz de spot acorde
  - si hay sol y es al aire libre, pongan una luz direccional acorde
- Recuerden que no hace falta que bakeen las luces. Con que sean realtime ya está. Es más trabajo para la GPU pero menos trabajo para ustedes.
- Al menos un sistema de partículas en el nivel que lo resalte: chispas de algún fuego, humo, fuegos artificiales, luciérnagas, etc.
- Si el nivel sucede al aire libre, agréguenle un skybox que tenga sentido con el resto de la escena.

### 4. Embelesamiento del TP4

Ahora que conocen de luces y partículas, espero que mejoren lo del TP anterior. Por ejemplo:

- Que los impactos de proyectiles contra la pared larguen algún chispazo (partículas)
- Las linternas sean una luz de spot y se vea realista
- Que los hechizos tengan una luz (point, probablemente) y larguen algún efecto de partículas
- etc
