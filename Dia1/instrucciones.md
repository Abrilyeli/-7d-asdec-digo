# Desafío Día 1: Comprensión de Tipos de Variables y Comparaciones en JavaScript

¡Bienvenido al primer día del #7DaysOfCode! En este desafío, abordarás uno de los problemas más comunes que enfrentan los desarrolladores al usar JavaScript: la comparación de variables con diferentes tipos de datos.

## Objetivo del Desafío

El objetivo de este primer desafío es que entiendas cómo JavaScript maneja las comparaciones entre variables de diferentes tipos y cómo puedes evitar errores comunes que ocurren debido a las conversiones automáticas de tipo.

### Contexto

En muchos lenguajes de programación compilados, como Java y C#, los errores de tipo son detectados durante la compilación. Sin embargo, en JavaScript, estos errores solo se manifiestan en tiempo de ejecución, lo que puede llevar a comportamientos inesperados.

Por ejemplo, en JavaScript, las siguientes comparaciones retornarán `true`:

```javascript
console.log(false == '0'); // true
console.log(null == undefined); // true
console.log(" \t\r\n" == 0); // true
console.log(' ' == 0); // trueEsto puede ser confuso, especialmente para principiantes.Desafío de CódigoTu tarea de hoy es reescribir el siguiente código para que imprima información correcta, que tenga sentido y sin errores:let numeroUn = 1;
let stringUn = '1';
let numeroTreinta = 30;
let stringTreinta = '30';
let numeroDiez = 10;
let stringDiez = '10';

if (COMPARAR numeroUn y stringUn) {
    console.log('Las variables numeroUn y stringUn tienen el mismo valor, pero tipos diferentes');
} else {
    console.log('Las variables numeroUn y stringUn no tienen el mismo valor');
}

if (COMPARAR numeroTreinta y stringTreinta) {
    console.log('Las variables numeroTreinta y stringTreinta tienen el mismo valor y el mismo tipo');
} else {
    console.log('Las variables numeroTreinta y stringTreinta no tienen el mismo tipo');
}

if (COMPARAR numeroDiez y stringDiez) {
    console.log('Las variables numeroDiez y stringDiez tienen el mismo valor, pero tipos diferentes');
} else {
    console.log('Las variables numeroDiez y stringDiez no tienen el mismo valor');
}InstruccionesCorrige el Código: Reescribe el código anterior para que las comparaciones sean correctas y el programa imprima mensajes verdaderos basados en las comparaciones realizadas.Ejecuta en el Navegador: Si no estás familiarizado con editores de código como Visual Studio Code, puedes ejecutar este programa directamente en la consola de tu navegador:Haz clic derecho en cualquier página web.Selecciona la opción "Inspeccionar".Ve a la pestaña "Consola" y pega tu código allí para probarlo.ConsejosUsa === en lugar de == para comparar tanto el valor como el tipo de las variables.Puedes cambiar los nombres de las variables y los valores si lo deseas, pero asegúrate de que los mensajes sean precisos y reflejen la verdad.ExtraPara aprender más sobre operadores de comparación en JavaScript, puedes leer el siguiente artículo de Alura:
Cómo utilizar operadores de comparación en JavaScript
