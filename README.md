# Árboles en c++
Con la definicion de arbol y nodo, crear un programa que permita realizar diversas operaciones que demuestren las teorias.
Cada grupo debe considerar los siguientes criterios:

1. Aplicacion de conceptos tecnicos (ver sección)
2. Eficiencia de codigo (numero de lineas)
3. Aplicacion de codigo limplio.
4. Entrega de versiones de producto funcionales.
5. Aplicacion de conceptos de arboles


# Conceptos tecnicos.

1. Clases y métodos
2. Arboles
3. Punteros.
4. Recursividad
5. Pruebas unitarias.
6. variables public, private y friend.
7. Tipo de datos string
8. Funciones.
9. curso gratis de c++

# Herramientas 

1. Gherkin (Descripcion de requerimientos)
2. Utilizar metodologias agiles (Scrum)
3. Entregas de productos funcionales (MVP)
4. [CodeBlocks](http://www.codeblocks.org/downloads) (software para desarrollo)
5. [Git](https://github.com/)
6. [Curso gratis de C++](https://www.udemy.com/curso-de-cpp-basico-a-avanzado/)
7. [Cmder](http://cmder.net/) 

# Aplicaciones

1. [Indices en base de datos](https://github.com/jorge190588/basedatosII) (Sistemas de Bases de Datos, 2da Edición - Ramez Elmasri y Shamkant B. Navathe) pg 118.

# VERSION 1. 

La primera version del programa incluye crear y mostrar nodos consecutivos.

### Caracteristica: como usuario necesito acceder al programa y que muestre un menu	

+ **Given(Dado):** Un usuario inicia el programa.
+ **When(Cuando):**	Carge el sistema
+ **Then:** (Entonces)	debe mostrar un el siguiente menu

Ejemplo:

	1. Insertar un nodo
	2. Listar nodos usando while
	3. Listar nodos usando recursividad
	4. Salir


### Caracteristica: como usuario requiero opcion para ingresar nodos consecutivos	

+ **Given:** Ingreso al menu
+ **When:**	Accedo a la opcion 1. insertar un nodo
+ **Then:**	Puedo escribir un valor de un nodo y crearlo
	
### Caracteristica: como usuario requiero una opcion listar los nodos que he ingresado	

Escenario 1	
+ **Given:** Ingreso al menu
+ **When:**	Accedo a la opcion 2. Lista nodos usando while
+ **Then:**	el resultado se debe ser:

Ejemplo: 

	Codigo nodo: 0001, Valor del nodo: 10, nodo siguiente: 002
	Codigo nodo: 0002, Valor del nodo: 20, nodo siguiente: 003
	Codigo nodo: 0003, Valor del nodo: 30, nodo siguiente: 000


Escenario 2	

+ **Given:** Ingreso al menu
+ **When:**	Accedo a la opcion 3. Lista nodos usando recursividad
+ **Then:**	El resultado se debe ser 

Ejemplo:

	Codigo nodo: 0001, Valor del nodo: 10, nodo siguiente: 002
	Codigo nodo: 0002, Valor del nodo: 20, nodo siguiente: 003
	Codigo nodo: 0003, Valor del nodo: 30, nodo siguiente: 000


# VERSION 2. Agregar nodo izquierdo y derecho.

### Caracteristica: como usuario requiero opcion para ingresar un nodo izquierdo y derecho	

Escenario 1	
+ **Given:**	Ingreso al menu
+ **When:**	Accedo a la opcion 1. insertar un nodo
+ **Then:**	Puedo escribir el valor de nodo izquierdo y no escribir el valor del nodo derecho
	
Escenario 2	
+ **Given:**	Ingreso al menu
+ **When:**	Accedo a la opcion 1. insertar un nodo
+ **Then:**	Puedo escribir el valor de nodo izquierdo y  el valor del nodo derecho
	
Escenario 2	
+ **Given:** Ingreso al menu
+ **When:** Accedo a la opcion 1. insertar un nodo
+ **Then:** Puedo escribir el valor de nodo derecho y no escribir el valor del nodo izquierdo

	
### Caracteristica: como usuario requiero una opcion para listar los nodos que he ingresado	

Escenario 1	
+ **Given:** ingreso al menu
+ **When:** accedo a la opcion 2. Lista nodos usando while
+ **Then:** el resultado se debe ser como el ejemplo

Ejemplo:

	Codigo nodo: 0001, Valor del nodo: 10, nodo izquierdo: 002, nodo derecho: 003
	Codigo nodo: 0002, Valor del nodo: 20, nodo izquierdo: 004, nodo derecho: 005
	Codigo nodo: 0003, Valor del nodo: 30, nodo izquierdo: 006, nodo derecho: 007

Escenario 2	
+ **Given:+ ** ingreso al menu
+ **When:** accedo a la opcion 3. Lista nodos usando recursividad
+ **Then:**	el resultado se debe ser como el ejemplo
	
Ejemplo:

    Codigo nodo: 0001, Valor del nodo: 10, nodo izquierdo: 002, nodo derecho: 003
	Codigo nodo: 0002, Valor del nodo: 20, nodo izquierdo: 004, nodo derecho: 005
	Codigo nodo: 0003, Valor del nodo: 30, nodo izquierdo: 006, nodo derecho: 007
  
### Caracteristica: como usuario requiero una opcion para buscar un nodo

+ **Given:** ingreso al menu
+ **When:** carge el sistema
+ **Then:** debe de aparecer una opcion con nombre "4. Buscar un nodo por valor"

### Caracteristica: como usuario requiero cambiar reemplazar el titulo de la opcion salir

+ + **Given:** ingreso al menu
+ **When:** carge el sistema
+ **Then:** cambiar la opcion "4. Salir" a "5. Salir"


## Caracteristica: como usuario requiero buscar un nodo por valor

+ **Given:** ingreso al menu
+ **When:** entre a la opcion "4. Buscar un nodo por valor"
+ **And** ingrese el valor a buscar
+ **Then:** debe de mostrar el resultado del ejemplo

Ejemplo:

     Codigo nodo: 0001, Valor del nodo: 10, nodo izquierdo: 002, valor nodo izquierdo:20, nodo derecho: 003 y valor nodo derecho: 9


# VERSION 3. 

Eliminar un nodo, identificar un nodo (hijo, raiz, padre, hermano, rama, hoja), Describir caracteristicas (camino, longitud, algura, nivel, grado, orden)

# VERSION 4. 

Recorridos (Amplitud)
