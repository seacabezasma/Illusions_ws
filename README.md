# Taller ilusiones visuales

## Propósito

Comprender algunos aspectos fundamentales de la [inferencia inconsciente](https://github.com/VisualComputing/Cognitive) de la percepción visual humana.

## Tareas

Implementar al menos 6 ilusiones de tres tipos distintos (paradójicas, geométricas, ambiguas, etc.), al menos dos con movimiento y dos con interactividad.

## Integrantes
(2, o 3 si van a participar en el [best illusion of the year contest](illusionoftheyear.com) o van a implementar algunas ilusiones como visual hack)

Complete la tabla:

| Integrante           | github nick |
|----------------------|-------------|
| Sergio Andres Cabezas|seacabezasma |
| Luis Zamora		   |zam403		 |

## Discusión

1. Complete la tabla

| Ilusión 		        | Categoria      	                    | Referencia                                                | Tipo de interactividad (si aplica) | URL código base (si aplica)               |
|-----------------------|---------------------------------------|-----------------------------------------------------------|------------------------------------|-------------------------------------------|
|Scintillating Grid     |Ilusión de Contraste                   |https://en.wikipedia.org/wiki/Grid_illusion                |(Aplica para todas) Pulse "a" para  |https://www.openprocessing.org/sketch/26605|
|Color Gradient         |Ilusión de Color                       |http://www.michaelbach.de/ot/lum-inducedGrating/index.html |activar o desactivar la ilusión.    |
|Reverse Spoke	        |Ilusión de Color, Ilusión de movimiento|http://www.michaelbach.de/ot/mot-spokes/index.html         |Pulse "espacio" para rotar entre las|                                           |
|Lilac Chaser           |Ilusión de Color, Ilusión de movimiento|http://www.michaelbach.de/ot/col-lilacChaser/index.html    |ilusiones                           |                                           |
|Munker-White Illusion  |Ilusión de Contraste                   |http://www.michaelbach.de/ot/lum-white/index.html          |                                    |                                           |
|Motion Binding         |Ilusión de movimiento                  |http://www.michaelbach.de/ot/mot-motionBinding/index.html  |                                    |                                           |
|Bulging Checkerboard   |Ilusión geométrica, Impresión 3D       |http://www.michaelbach.de/ot/geom_KitaokaBulge/index.html  |                                    |                                           |
|Hollow Face Illusion   |Ilusión de Perspectiva                 |http://www.michaelbach.de/ot/fcs-hollowFace/index.html     |                                    |                                           |

2. Describa brevememente las referencias estudiadas y los posibles temas en los que le gustaría profundizar:

_Scintillating Grid_: El proceso de inhibición lateral, en donde el campo receptivo (conjunto de receptores que responden a la presencia de un estímulo) sobre la retina,
el cual agrupa múltiples fotoreceptores sobre un area particular y que recibe estímulos de una célula de ganglios retinales, genera la ilusón tras la excitación de 
algunos fotoreceptores al ganglio en la zona central del campo cuando estos detectan un aumeto en la luminicencia, los fotoreceptores en el area circundante inhiben 
la célula de ganglios, luego, debido a que un punto en la intersección esta rodeado por mas luminicencia que otro punto en medio de una línea, el efecto de inhibicón 
aumenta, generando la sensación de obscuridad.

_Color Gradient_: Fenómeno prosiblemente ocurrido en la corteza visual, se presenta por la presencia de barras de color que constrastan con la barra central, obligando 
la sensación de contraste.

_Reverse Spoke_: A medida que el disco en gradiente gira, las lineas de sólidas de color gris se confunden con el tono de gris idéntico al de las lineas, de modo 
que al reaparecer la linea, se genera la sensación de movimiento.

_Lilac Chaser_: Ilusión generada por la combinación de 3 fenómenos diferentes, el primero relacionado con la estimulación de los conos que rodean la fobea, de manera
que los círculos de color lila que rodean el punto fijo permanecen sobre su posición bajo color en negativo, producto de la fatiga de los conos, esto solo sobre 
el espacio que reemplaza los circulos lila. El segundo, es la sensación cinematográfica de movimiento producto de la desaparación continua de los circulos, que, 
debido a que desaparecen circulos continuos, generan la ilusión de movimiento. El tercero es resultado de múltiples ciclos del proceso. El circulo verde que 
reemplaza los circulos lila periodicamente se reemplaza a medida que el circulo se "mueve", como resultado, los circulos lila "desaparecen", dejando solo el circulo 
en negativo como único objeto presente.

_Munker-White Illusion_: Esta ilusión aparentemente es una respuesta natural generada por el proceso de toda criatura con capacidad visual de diferenciar las ambigüedades 
del entorno, ademas de que dicha diferenciación surge de la relación estadística entre imegnes y escenas previamente percibidas. En este caso, las franjas negras se asocian
como entornos oscuros comparados con las franjas blancas, lo que lleva a interpretar la información rodeada por el color negro como una visualización de una imagen en 
un ambiente oscuro, y por ende, las imagenes y colores se comportan acorde a dicho entorno.

_Motion Binding_: En este caso, al interponer obstaculos sobre el cuadrado de lineas azules, se mantiene la persecpción de ser un cuadrado girando sobre sus vertices
sin embargo, si los obstáculos se tornan del mismo color que el fondo, se pierda información sobre los vertices del cuadrado azul, por lo que el cuadrado se interpreta como 
lineas oscilando en el espacio.

_Bulging Checkerboard_: Las lineas rectas del tablero parecen deformarce por la presencia de objetos a sus costados. Aquí, los cuadrados en el tablero hacen parecer
que el tablero se comba en su centro, siendo que siempre sigue siendo un tablreo de lineas rectas.

_Hollow Face Illusion_: Esto se debe principalmente a que la proyección sobre el plano de un objeto tridimensional implica la perdida de información. En este caso
con la iluminación adecuada, las sombras generadas por la mascara en su lado concavo concinciden con las sombras que se generan en su lado convexo, por lo que 
la reconstrucción que realiza nuestro cerebro de la imágen nos hace asumir ambos lados de la mascara como el mismo lado convexo.

De este ejercicio, sin lugra a dudas, el efecto producido por la mascara giratoria es el mas interesante. Es necesario investigar cómo es posible mantener la ilusión, 
y al mismo tiempo romperla a voluntad logrando los angulos precisos de cámaray luz de manera que se conserve el efecto, pero que a su vez sea mas sencillo percibir 
el lado concavo de la máscara. Nótese que al desactivar la iluminación, se genera un efecto similar a l visto en la [ilusión de la bailarina] (http://www.michaelbach.de/ot/sze-silhouette/index.html)
incluso cuando no hay un ángulo claro de inclinación de la cámara. 

## Entrega

* Modo de entrega: [Fork](https://help.github.com/articles/fork-a-repo/) la plantilla en las cuentas de los integrantes (de las que se tomará una al azar).
* Plazo: 18/3/18 a las 24h.
