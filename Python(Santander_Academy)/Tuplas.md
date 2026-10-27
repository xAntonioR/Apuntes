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
---
 ## Métodos de Tuplas
*Aunque las tuplas son inmutables, Python proporciona varios métodos útiles para trabajar con ellas:*
 * **count**(elemento): devuelve el número de veces que aparece un elemento en la tupla.
 * **index**(elemento): devuelve el índice de la primera aparición de un elemento en la tupla. Opcionalmente, se puede especificar el inicio y fin de la búsqueda.
 * **len**(tupla): aunque no es un método de tupla propiamente dicho, esta función incorporada devuelve la longitud de la tupla.
```PY
   mi_tupla = (1, 2, 3, 2, 4, 2)

   print (mi_tupla.index(2))   # Salida: 1
   print (mi_tupla.index(2, 2))   #Salida: 3
   print (mi_tupla.index(2, 2, 4))   #Salida: 3
```
<img width="465" height="473" alt="image" src="https://github.com/user-attachments/assets/77f69533-7309-4d8d-988c-ef19970ee1ad" />

---
