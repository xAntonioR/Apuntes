# BUCLES / LOOPS
 * Los bucles nos permiten repetir un bloque de código varias veces. En Python, los bucles más comunes son los siguientes:
   * **For**
     * El bucle **for** se utiliza para iterar sobre una secuencia (como una lista, una tupla o una cadena) o cualquier objeto iterable. La sintaxis básica es la siguiente:
       ```PY
          for variable in secuencia:

              # Bloque de código a repetir
              instrucciones
       ```
       ***Ejemplo***
       ```PY
          frutas = ["manzana", "banana", "naranja"]


          for fruta in frutas:
          print(fruta)
       ```
     >En este ejemplo, el bucle **for** itera sobre la lista de frutas. En cada iteración, la variable fruta toma el valor de un elemento de la lista, y se ejecuta el bloque de código dentro del bucle. En este caso, se imprime cada fruta en una línea separada.
   * **While**
