# ESTRUCTURAS DE CONTROL 
* Las Estructuras de control nos permiten controlar el flujo de ejecución de nuestros programas. En Python, las estructuras de control más comunes son las estructuras condicionales y los bucles. Estas estructuras nos permiten tomar decisiones y repetir bloques de código según ciertas condiciones.
## Estructuras Condicionales
* Las estructuras condicionales nos permiten ejecutar diferentes bloques de código según se cumpla o no no determinada condición. En Python, las estructuras condicionales más utilizadas son if, if-else e if-elif-else.
  * IF
    * La estructuras if se utiliza para ejecutar un bloque de código si la condición es verdadera. La sintaxis básica es la sigiente:
   ```Markdown
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
