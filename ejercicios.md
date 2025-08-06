# Ejercicios

1. Crear una función que reciba como parámetro un número de dos dígitos luego intercambie ese número y determine si el número ingresado es el mayor.

**Ejemplo**

```js
largestSwap(27) ➞ false largestSwap(43) ➞ true
```

> Explicación: En el caso del 27, devuelve false debido a que el número invertido es 72, y 27 no es mayor que 72. En el caso del 43 devuelve true, debido a que el número invertido de 43 es 34 y 43 es mayor que 34.

2. Crear una función que reciba como parámetro dos números, el primero es el punto inicial y el segundo el punto final, su tarea es imprimir en un array el cuadrado de todos los números comprendidos entre los números ingresados por el usuario incluyendo dichos números.

**Ejemplo.**

```js
power(3, 5) ➞ [9, 16, 25]

```

3. Crear una función que reciba 3 parámetros, los primeros dos serán números, y el tercero la operación que desea realizar (suma, resta, multiplicación o división

4. Crear una función que reciba un número y verifique si el número ingresado por el usuario es un número primo. Debe usar una función recursiva para resolverlo.

5. Crear una función que reciba como parámetro un array de números, hay que remover los valores repetidos de dicho array y retornar un nuevo array pero en orden inverso al ingresado.

**Ejemplo**

```js
[1, 3, 3, 5, 5] ➞ [5, 3, 1]
```

6. Crear un programa que permita determinar si un número ingresado por el usuario es múltiplo de 2, 5, 7 simultáneamente

7. Crear una función que retorne un nuevo array con valores pares y positivos únicamente (excluyendo el cero), el nuevo array debe estar en el mismo orden en que encuentre los valores.

**Ejemplo**

```js
uniqueArr([10, 6, -12, 13, 5, 13]) ➞ [10, 6]
```

8. Crear un programa que permita determinar cuántas veces se repite las letras **“i”**, **“a”** y **“u”** de un string. Debe imprimir la cantidad de cada una.

9. Crear una función que retorne un string pero únicamente retorne aquellos string que no se repite ningún carácter entre sí.

**Ejemplos**

```js
filterUnique(["abb", "abc", "abcdb", "aea", "bbb"]) ➞ ["abc"]
filterUnique(["88", "999", "989", "9988", "9898"]) ➞ []
filterUnique(["ABCDE", "DDEB", "BED", "CCA", "BAC"]) ➞ ["ABCDE", "BED", "BAC"]
```

10. Crear una función que reciba dos parámetros, el primero es un string y el segundo es una letra, debe invertir todas las palabras que comiencen con la letra ingresada.

**Ejemplos**

```js
specialReverse("word searches are super fun", "s") ➞ "word sehcraes are repus fun"

```

11. Crear una función que tome un array como parámetro y retorne el segundo número más grande del conjunto. Debe haber como mínimo dos números para hacer la comparación

12. Crear una función que reciba un número como parámetro, y devolver la suma total de ese número multiplicada por cada número entre 1 y 10. Debe usar una función recursiva.

**Ejemplo**

```js
multiSum(1) ➞ 55 // 1 x 1 + 1 x 2 + 1 x 3 ...... 1 x 9 + 1 x 10 = 55
```

13. Crear una función que reciba como parámetro un array. Devolver los dos valores más pequeños ingresados.

**Ejemplo**

```js
lowest([2, 3, 10, 1, 15]) ➞ [2, 1]
```

14. Crear una función que calcule el número de letras y dígitos que contiene un string. Devuelva el resultado como un objecto.

**Ejemplo**

```js
countAll("H3ll0 Wor1d") ➞ { "LETTERS":  7, "DIGITS": 3 }
```

15. Cree una función que encuentre el número entero más alto de un array usando recursividad.

**Ejemplo**

```js
findHighest([-1, 3, 5, 6, 99, 12, 2]) ➞ 99
```

16. Crear un programa que una todos los elementos de un array en un string separado por comas.

**Ejemplo**

```js
colors = ["Rojo", "Verde", "Blanco", "Negro"]; ➞ "Rojo,Green,White,Black"
```

17. Crear una función que reciba un número como parámetro y que retorne un nuevo array con el cuadrado de los dígitos del número ingresado.
**Ejemplo**

```js
squareDigits(9119) ➞ [81, 1, 1, 81]
```

18. Cree una función que encuentre el número entero más pequeño de un array usando recursividad.

**Ejemplo**

```js
findLowest([-1, 3, 5, 6, 99, 12, 2]) ➞ -1
```
