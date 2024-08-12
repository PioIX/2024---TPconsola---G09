# 2024---TPconsola---G09

Descripción de console.log()

La función console.log() es una herramienta de depuración en JavaScript que se usa para imprimir mensajes en la consola del navegador o en la consola de un entorno de ejecución como Node.js. Es esencial para desarrollar, depurar y monitorear el estado de las aplicaciones.

Parámetros de console.log()

- Parámetro 1: El primer parámetro es el mensaje que deseas imprimir. Puede ser un texto simple (cadena de caracteres), un número, un objeto, un array, etc.
- Parámetro 2 en adelante: Puedes pasar múltiples parámetros a console.log(). Estos se imprimen en la consola en el orden en que se pasan, separados por espacios.

Ejemplos

1. Texto simple:
   console.log("Hola, mundo!");

2. Números:
   console.log(123);

3. Objetos:
   const persona = { nombre: "Juan", edad: 30 };
   console.log(persona);

4. Arrays:
   const numeros = [1, 2, 3, 4];
   console.log(numeros);

5. Múltiples parámetros:
   console.log("Nombre:", "Juan", "Edad:", 30);

Uso en Front-end vs Back-end

Front-end

En el desarrollo front-end (interfaz de usuario), console.log() se utiliza comúnmente para:

1. Depurar eventos: Verificar que los eventos del usuario, como clics o entradas de teclado, se manejan correctamente.
   document.getElementById("miBoton").addEventListener("click", function() {
     console.log("Botón clickeado!");
   });

2. Verificar estados de variables: Ayuda a verificar los valores de las variables y el flujo de ejecución del código.
   let contador = 0;
   function incrementar() {
     contador++;
     console.log("Contador:", contador);
   }

3. Depurar datos de formularios: Verificar la entrada del usuario antes de procesarla.
   function enviarFormulario() {
     const nombre = document.getElementById("nombre").value;
     console.log("Nombre ingresado:", nombre);
   }
