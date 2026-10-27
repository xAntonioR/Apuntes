# BUCLES / LOOPS
 * Los bucles nos permiten repetir un bloque de código varias veces. En Python, los bucles más comunes son los siguientes:
## **For**
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
## **While**
  * El bucle while se utiliza para repetir un bloque de código mientras una condición sea verdadera. La sintaxis básica es la siguiente:
       ```PY
          while condicion:

              # Bloque de código a repetir
              instrucciones
       ```
       ***Ejemplo***
       ```PY
          contador = 0


          while contador < 5:

              print(contador)
              contador += 1
       ```
     >En este ejemplo, el bucle while se ejecuta mientras la variable contador sea menor que 5. En cada iteración, se imprime el valor de contador y luego se incrementa en 1 mediante la instrucción contador += 1. El bucle se detendrá cuando contador alcance el valor de 5.
  >Es importante tener cuidado al usar el bucle while, ya que, si la condición nunca se vuelve falsa, el bucle se ejecutará indefinidamente, lo que se conoce como un bucle infinito.

# CONTROL DE BUCLES
 * Python proporciona algunas instrucciones especiales para controlar el flujo de ejecución dentro de los bucles:
## **Break**
   
