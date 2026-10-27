# ESTRUCTURA DE DATOS
  * Las estructuras de datos nos permiten organizar y almacenar datos de manera eficiente en nuestros programas. Python proporciona varias estructuras de datos integradas, como listas, tuplas, diccionarios y conjuntos, cada una con sus propias características y usos.
## **Listas**
   * Una lista es una estructura de datos mutable y ordenada que permite almacenar una colección de elementos. Los elementos de una lista pueden ser de diferentes tipos de datos y se encierran entre corchetes [], separados por comas.
### Creación y Acceso
   * Para crear una lista, simplemente encierra los elementos entre corchetes:
     ```PY
        frutas = ["manzana", "banana", "naranja"]
     ```
   * Para acceder a los elementos de una lista, utiliza el índice del elemento entre corchetes. Los índices comienzan desde 0.
     ```PY
        print(frutas[0])  # Imprime "manzana"
        print(frutas[1])  # Imprime "banana"
        print(frutas[2])  # Imprime "naranja"
     ```
   * También puedes acceder a los elementos desde el final de la lista utilizando índices negativos. El índice -1 representa el último elemento, -2 representa el penúltimo, y así sucesivamente.
     ```PY
        print(frutas[-1])  # Imprime "naranja"
        print(frutas[-2])  # Imprime "banana"
        print(frutas[-3])  # Imprime "manzana"
     ```
 ### Métodos de listas
  ***Las listas en Python tienen varios métodos incorporados que nos permiten manipular y modificar los elementos de la lista. Algunos métodos comunes son:***
   + **append**(elemento): agrega un elemento al final de la lista.
   + **insert**(indice, elemento): inserta un elemento en una posición específica de la lista.
   + **remove**(elemento): elimina la primera aparición de un elemento en la lista.
   + **pop**(indice): elimina y devuelve el elemento en una posición específica de la lista.
   + **sort**(): ordena los elementos de la lista en orden ascendente.
   + **reverse**(): invierte el orden de los elementos en la lista.
 ***Ejemplo:**
     ```PY
        frutas = ["manzana", "banana", "naranja"]


        frutas.append("pera")
        print(frutas)  # Imprime ["manzana", "banana", "naranja", "pera"]

        frutas.insert(1, "uva")
        print(frutas)  # Imprime ["manzana", "uva", "banana", "naranja", "pera"]

        frutas.remove("banana")
        print(frutas)  # Imprime ["manzana", "uva", "naranja", "pera"]

        fruta_eliminada = frutas.pop(2)
        print(frutas)  # Imprime ["manzana", "uva", "pera"]
        print(fruta_eliminada)  # Imprime "naranja"

        frutas.sort()
        print(frutas)  # Imprime ["manzana", "pera", "uva"]

        frutas.reverse()
        print(frutas)  # Imprime ["uva", "pera", "manzana"]
     ```
 ### Listas de Compresión
  
