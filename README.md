# Estructuras De Datos

## ¿Qué demonios son las estructuras de datos? 
Si te dedicas a la programación, de seguro te has topado con este tema. Y no te preocupes si al leer acerca del tema la primera vez te aya resultado difícil entenderlo del todo. A todos nos pasa, o al menos a la mayoría. 

Hablando de una forma sencilla, las estructuras de datos son formas de representar información de manera estructurada.

De igual manera que utilizamos los Arrays para almacenar una cantidad determinada de elementos, podemos utilizar las estructuras de datos con un comportamiento interno definido por nosotros, o en otros casos, por otro programador.

Para entender un poco mejor, veamos un ejemplo:

Supongamos que realizaremos un sistema para el registro de un numero indeterminado de personas y que me devuelva la ultima persona registrada.

Para un caso como este, la mejor opción es utilizar una estructura de datos conocida como Stack, la cual apila elementos, y siempre devuelve el ultimo agregado.

He agrupado una serie de implementaciones de estructuras de datos escritas en Python. Todas ellas dinámicas, tanto lineales como no lineales. 

Mencionare algunas. Si quieres ver todas las implementaciones. Ingresa al siguiente enlace: https://github.com/LuisAlejandroSalcedo/Estructuras-De-Datos.

### 1- Árbol AVL:

Un árbol AVL es un tipo especial de árbol binario ideado por los matemáticos rusos Adelson-Velskii y Landis. Fue el primer árbol de búsqueda binario auto-balanceable que se ideó.

Es un árbol binario de búsqueda en el que para cada nodo, las alturas de sus subárboles izquierdo y derecho no difieren en más de 1.

No se trata de árboles perfectamente equilibrados, pero sí son lo suficientemente equilibrados como para que su comportamiento sea lo bastante bueno como para usarlos donde los ABB no garantizan tiempos de búsqueda óptimos.

El algoritmo para mantener un árbol AVL equilibrado se basa en reequilibrados locales, de modo que no es necesario explorar todo el árbol después de cada inserción o borrado.

Ejemplo de un Árbol AVL en Python: https://github.com/LuisAlejandroSalcedo/Estructuras-De-Datos/blob/master/AVL/AVL.py.

### 2- Grafo:
En matemáticas y ciencias de la computación, un grafo (del griego grafos: dibujo, imagen) es un conjunto de objetos llamados vértices o nodos unidos por enlaces llamados aristas o arcos, que permiten representar relaciones binarias entre elementos de un conjunto.​ Son objeto de estudio de la teoría de grafos.

Ejemplo de grafos en Python: https://github.com/LuisAlejandroSalcedo/Estructuras-De-Datos/tree/master/Graph.

### 3- Listas Enlazadas:
En ciencias de la computación, una lista enlazada es una de las estructuras de datos fundamentales, y puede ser usada para implementar otras estructuras de datos

Ejemplos de listas enlazadas en Python: https://github.com/LuisAlejandroSalcedo/Estructuras-De-Datos/tree/master/LinkedList.

### 4- Arboles Binarios:
En ciencias de la computación, un árbol binario es una estructura de datos en la cual cada nodo puede tener un hijo izquierdo y un hijo derecho. No pueden tener más de dos hijos. Si algún hijo tiene como referencia a null, es decir que no almacena ningún dato, entonces este es llamado un nodo externo.

Ejemplo de arboles binarios en Python: https://github.com/LuisAlejandroSalcedo/Estructuras-De-Datos/tree/master/BinaryTree.
