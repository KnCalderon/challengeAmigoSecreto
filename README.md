# challengeAmigoSecreto
Desafío Amigo Secreto del programa para principiantes ONE 

# Sorteo de Amigos

Este proyecto realiza un sorteo simple de nombres a partir de un arreglo de amigos utilizando **JavaScript** y el DOM.

## Descripción

El programa toma una lista de amigos, selecciona uno al azar y muestra el resultado en la página web. Está diseñado como un ejercicio práctico para comprender el uso de arreglos, generación de números aleatorios y manipulación del DOM.

## Funcionalidades

1. **Ingresar un listado de amigos**  
   ELjugador puede ir ingresando sus amigos uno a uno a partir del botón "agregar"

2. **Generar un índice aleatorio**  
   Se utiliza `Math.random()` junto con `Math.floor()` para calcular un índice válido dentro del arreglo `amigos`.

   ```javascript
   let indice = Math.floor(Math.random() * amigos.length);
