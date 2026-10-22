# FUNDAMENTOS DE LA PROGRAMACION 
## ¿Qué es una Computadora?

* Dispositivo para ejecutar programas a gran velocidad siempre y cuando los pasos compilados sean dados de forma precisa
<img width="304" height="304" alt="150127_codigo_computador_cronologia_finde_dv" src="https://github.com/user-attachments/assets/51828e64-b87f-4c55-9e61-7c62b5dad29b" />


## ¿Para qué sirve Algoritmo? 

* Es una serie de pasos escritos en lenguaje de alto nivel que son interpretados y/o compilados a lenguaje de maquina que sirven para que el computador pueda reconocerlos y seguirlos.
  #### Ejemplo:
  ```HTML
  <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Algoritmo Café</title>
</head>
<body>

    <h2>Algoritmo para preparar café</h2>
    <button onclick="ejecutarAlgoritmo()">Iniciar Proceso</button>

    <div id="log" style="margin-top: 20px; font-family: monospace;"></div>

    <script>
        function ejecutarAlgoritmo() {
            let log = document.getElementById("log");
            log.innerHTML = ""; // Limpiar resultados anteriores

            // 1. Encender máquina
            log.innerHTML += "1. Encender máquina<br>";

            // 2. ¿Hay agua?
            let hayAgua = confirm("¿Hay agua en el depósito?");
            if (!hayAgua) {
                log.innerHTML += "-> No hay agua: Llenar depósito<br>";
            } else {
                log.innerHTML += "-> Sí hay agua<br>";
            }

            // 3. ¿Hay cápsulas?
            let hayCapsulas = confirm("¿Hay cápsulas?");
            if (!hayCapsulas) {
                log.innerHTML += "-> No hay cápsulas: Hacer pedido<br>";
            } else {
                log.innerHTML += "-> Sí hay cápsulas<br>";
            }

            // 4. Introducir y ON
            log.innerHTML += "<b>4. Introducir cápsula y presionar ON</b><br>";
        }
    </script>

</body>
</html>
```

### Algunos Lenguajes de Alto Nivel:
* Java
*  Ptyhon
*  C+
*  Typescrip

## 
