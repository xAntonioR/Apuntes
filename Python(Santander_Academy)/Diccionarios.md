# DICCIONARIOS
* Un diccionario es una estructura de datos mutable y no ordenada que permite almacenar pares de clave-valor. Cada elemento en un diccionario consiste en una clave única y su valor correspondiente. Los diccionarios se encierran entre llaves {}, y los pares clave-valor se separan por comas.
### **Creación y Acceso**
 * ***Para crear un diccionario, utiliza llaves y separa las claves y valores con dos puntos.***
 * ***persona = {"nombre": "Juan", "edad": 25, "ciudad": "Madrid"}***
 * ***Para acceder a los valores de un diccionario, utiliza la clave correspondiente entre corchetes:***
   ```PY
      print(persona["nombre"])  # Imprime "Juan"
      print(persona["edad"])    # Imprime 25
      print(persona["ciudad"])  # Imprime "Madrid"
   ```
   > También puedes utilizar el método get() para obtener el valor de una clave. Si la clave no existe, devuelve un valor predeterminado (por defecto, None).

### Métodos de Diccionario 
***Los diccionarios en Python tienen varios métodos incorporados para manipular y acceder a los elementos. Algunos métodos comunes son:***
 * **keys**(): devuelve una vista de todas las claves del diccionario.
 * **values**(): devuelve una vista de todos los valores del diccionario.
 * **items**(): devuelve una vista de todos los pares clave-valor del diccionario.
 * **update**(otro_diccionario): actualiza el diccionario con los pares clave-valor de otro diccionario.
 ***Ejemplo***
    ```PY
      persona = {"nombre": "Juan", "edad": 25, "ciudad": "Madrid"}

      print(persona.keys())    # Imprime dict_keys(["nombre", "edad", "ciudad"])
      print(persona.values())  # Imprime dict_values(["Juan", 25, "Madrid"])
      print(persona.items())   # Imprime dict_items([("nombre", "Juan"), ("edad", 25), ("ciudad", "Madrid")])

      persona.update({"profesion": "Ingeniero"})
      print(persona)  # Imprime {"nombre": "Juan", "edad": 25, "ciudad": "Madrid", "profesion": "Ingeniero"}
   ```
  
<img width="428" height="405" alt="image" src="https://github.com/user-attachments/assets/d250a9d1-c127-4eec-8d7e-e3dac2641b6f" />
