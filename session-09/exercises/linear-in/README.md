---
difficulty:
  - intermediate
OAs:
  - arrays
projects:
  - data-lovers
  - memory-match
---

# linearIn

[https://the-winter.github.io/codingjs/exercise.html?name=love6&title=Logic-1](https://the-winter.github.io/codingjs/exercise.html?name=love6&title=Logic-1)

Dados dos arrays de ints ordenados de forma creciente,
devuelve true si todos los números del segundo array
aparecen en el primero.

Nota: La mejor solución hace una sola pasada "lineal"
por ambas matrices, aprovechando que ambas matrices
ya están ordenadas.

**Ejemplo**

```js
    linearIn([1, 2, 4, 6], [2, 4]) → true
    linearIn([1, 2, 4, 6], [2, 3, 4]) → false
    linearIn([1, 2, 4, 4, 6], [2, 4]) → true
```
