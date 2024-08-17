# Desafío: Comparar Tipos en JavaScript

Este desafío te ayudará a entender cómo JavaScript compara valores y tipos de variables.

## Objetivo

Vamos a comparar dos variables para ver si tienen el mismo **valor** y/o el mismo **tipo**.

### Operadores Importantes

- `==`: Compara solo el **valor** (puede convertir tipos de forma automática).
- `===`: Compara el **valor** y el **tipo** (sin convertir nada).

## Ejemplo

En JavaScript, estas comparaciones extrañas dan `true`:

```javascript
console.log( false == '0' );  // true
console.log( null == undefined );  // true
