# ESTRUCTURAS DE CONTROL 
* Las Estructuras de control nos permiten controlar el flujo de ejecución de nuestros programas. En Python, las estructuras de control más comunes son las estructuras condicionales y los bucles. Estas estructuras nos permiten tomar decisiones y repetir bloques de código según ciertas condiciones.
## Estructuras Condicionales
* Las estructuras condicionales nos permiten ejecutar diferentes bloques de código según se cumpla o no no determinada condición. En Python, las estructuras condicionales más utilizadas son if, if-else e if-elif-else.
  * IF
    * La estructuras if se utiliza para ejecutar un bloque de código si la condición es verdadera. La sintaxis básica es la sigiente:
   ```PY
    if condición:
       # Bloque de código a ejecutar si la condición es verdadera
       instrucciones
   ```
   ***Ejemplo***
```PY
   edad =18
   if edad >= 18:
      print ("Eres mayor de edad.")
```
>En este ejemplo, si la variable edad es mayor o igual a 18, se ejecutará el bloque de código dentro de if y se imprimirá el mensaje "Eres mayor de edad."
---
 * IF-ELSE
   * La estructura if-else nos permite especificar n bloque de código alternativo que se ejecutará si la condición de if es falsa. La sintaxis básica es la siguiente:
   ```PY
     edad = 15

     if edad >= 18:
        print ("Eres mayor de edad.")

     else:
        print ("eres menor de edad.")
   ```
>En este ejemplo, si la variable edad es mayor o igual a 18, se ejecutará el bloque de código dentro del if y se imprimirá el mensaje "Eres mayor de edad." De lo contrario, se ejecutará el bloque de código dentro del else y se imprimirá el mensaje "Eres menor de edad."
---
 * IF-ELIF-ELSE
   * La estructura if-elif-else nos permite especificar múltiples condiciones y bloques de código alternativos. La sintaxis básica es la siguiente:
  ```PY
     if condicion1:

        # Bloque de código a ejecutar si la condicion1 es verdadera
        instrucciones

     elif condicion2:

        # Bloque de código a ejecutar si la condicion2 es verdadera
        instrucciones

     else:

        # Bloque de código a ejecutar si ninguna condición anterior es verdadera
        instrucciones
  ```
   ***Ejemplo***
   ```PY
   calificacion = 85


   if calificacion >= 90:
      print ("Excelente")

   elif calificacion >= 80:
      print ("Muy bueno")

   elif calificacion >= 70:
      print ("Bueno")

   else:
      print ("Necesita mejorar")
   ```
>En este ejemplo, se evalúan múltiples condiciones en orden. Si la variable calificación es mayor o igual a 90, se imprime "Excelente". Si no se cumple la primera condición, pero calificación es mayor o igual a 80, se imprime "Muy bueno". Si no se cumplen las condiciones anteriores, pero calificación es mayor o igual a 70, se imprime "Bueno". Si ninguna de las condiciones anteriores es verdadera, se ejecuta el bloque else y se imprime "Necesita mejorar". 
