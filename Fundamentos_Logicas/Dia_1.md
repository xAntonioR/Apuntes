# FUNDAMENTOS DE LA PROGRAMACION 
## ¿Qué es una Computadora?

* Dispositivo para ejecutar programas a gran velocidad siempre y cuando los pasos compilados sean dados de forma precisa
<img width="304" height="304" alt="150127_codigo_computador_cronologia_finde_dv" src="https://github.com/user-attachments/assets/51828e64-b87f-4c55-9e61-7c62b5dad29b" />


## ¿Para qué sirve Algoritmo? 

* Es una serie de pasos escritos en lenguaje de alto nivel que son interpretados y/o compilados a lenguaje de maquina que sirven para que el computador pueda reconocerlos y seguirlos.
  #### Ejemplo:
  ```PY
    def preparar_cafe():
    print("1. Encender máquina")
    
    # Condición: ¿agua?
    hay_agua = input("¿Hay agua? (s/n): ").strip().lower()
    if hay_agua == 'n':
        print("-> Llenar depósito")
        
    # Condición: ¿cápsulas?
    hay_capsulas = input("¿Hay cápsulas? (s/n): ").strip().lower()
    if hay_capsulas == 'n':
        print("-> Hacer pedido")
        
    print("-> Introducir y ON")

if __name__ == "__main__":
    preparar_cafe()
```

### Algunos Lenguajes de Alto Nivel:
* Java
*  Ptyhon
*  C+
*  Typescrip

## 
