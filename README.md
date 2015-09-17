#La leyenda de Tifis
Pequeño Juego hecho con Javascript en base al curso de [Platzi](https://platzi.com/clases/programacion-basica/)
#Como lo hice
Para acortar el código hice uso de la sentencia switch y los límites de madera los coloque dentro
de un array que contienen las coordenadas de los mismos.

<code>var limites = [{x : 0, y: 200}, 
              {x: 50, y: 200}, 
              {x: 100, y: 200},
              {x: 200, y: 0},
              {x: 200, y: 50},
              {x: 200, y:100},
              {x: 200, y:150},
              {x: 200, y:200},
              {x: 150, y:350},
              {x: 200, y:350},
              {x: 250, y:350},
              {x: 300, y:350},
              {x: 350, y:350},
              {x: 400, y:350},
              {x: 450, y:350}];
</code>
#Función map
Utilicé la función map para poder buscar dentro de un array multidimensional.
Lo pueden ubicar en [StackOverFlow](http://stackoverflow.com/questions/5181493/how-to-find-a-value-in-a-multidimensional-object-array-in-javascript)
