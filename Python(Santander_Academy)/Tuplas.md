# TUPLAS
 * Una tupla es una estructura de datos inmutable y ordenada que permite almacenar una colección de elementos. Los elementos de una tupla se encierran entre paréntesis (), separados por comas.
 ## Creación y Acceso
*Para crear una tupla, encierra los elementos entre paréntesis:*
  ```PY
     punto = (3, 4)
  ```
 *Para acceder a los elementos de una tupla, utiliza el índice del elemento entre corchetes, similar a las listas:*
  ```PY
     print(punto[0])  # Imprime 3
     print(punto[1])  # Imprime 4
  ```
> A diferencia de las listas, las tuplas son inmutables, lo que significa que no se pueden modificar una vez creadas. No se pueden agregar, eliminar o cambiar elementos en una tupla existente.
  > Las tuplas son útiles cuando necesitas almacenar una colección de elementos que no deben modificarse, como coordenadas o datos de configuración.
