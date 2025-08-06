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

19. Crear un programa que reciba un array de números, y que devuelva el número entero más alto que sea a su vez sea un número par. Si el usuario ingreso solo números impares se debe devolver -1.

**Ejemplo**

```js
largestEven([3, 7, 2, 1, 7, 9, 10, 13]) ➞ 10
```

20. Crear una función recursiva que permita determinar si un string es un palíndromo (es una palabra o frase que se lee igual en un sentido que en otro).

21. Crear un programa que permita determinar si un número ingresado por el usuario es múltiplo de 3, 5, y 11 simultáneamente.

22. Crear un programa que reciba un array de números, y que devuelva la sumatoria de todos los números. Para resolver el ejercicio debe usar una función recursiva.

**Ejemplo**

```js
sumArray([1, 2, 3]) ➞ 6
```

23. Crear una función que reciba un array como parámetro y retorne un array con dos elementos. Donde, el primer elemento debe sumar todos los números pares y el segundo elemento debe sumar todos los números impares.

**Ejemplo**

```js
sumOddAndEven([1, 2, 3, 4, 5, 6]) ➞ [12, 9] // 2 + 4 + 6 = 12 y 1 + 3 + 5 = 9
```

24. Crear un programa que permita determinar si un número ingresado por el usuario es múltiplo de 3, 5, y 10 simultáneamente.

25. Crear un programa que reciba un número y lo devuelva con sus cifras invertidas.

```js
 reverse(5121) ➞ "1215"
```

26. Crear un programa que reciba un array de números y retorne un array ordenado de mayor a menor.

**Ejemplo**

```js
[3, 6, 1, 8, 9, 2, 5] ➞ [9, 8, 6, 5, 3, 2, 1]
```

27. Crear una función que tome un array como parámetro y retorne el segundo número más pequeño del conjunto. Debe haber como mínimo dos números para hacer la comparación.

**Ejemplo**

```js
secondLowest([10, 40, 30, 20, 50]) ➞ 20
```

28. Crear una función que acepte dos strings como parámetros y retorne la cantidad de veces que se repite el primer string (tiene que ser un único carácter) en el segundo string.

**Ejemplo**

```js
charCount("b", "big fat bubble") ➞ 4
```

29. Crear un programa que reciba un array de números entre 1 y 10, pero al momento de ingresarlos se debe excluir un número, la función debe retornar el número que se excluyó.

**Ejemplo**

```js
missingNum([10, 5, 1, 2, 4, 6, 8, 3, 9]) ➞ 7
```

30. Crear una función que tome un número como parámetro, su tarea es sumar todos los números empezando en 1 hasta el número que el usuario ingresó.

**Ejemplo**

```js
si el usuario ingresa el número 4, el programa debe retornar 10, es decir, 1 + 2 + 3 + 4 = 10
```

31. Crear una función que acepte dos parámetros, el primero es un string y el segundo parámetro es un número entero, que simboliza la cantidad de veces que se debe repetir el string ingresado como primer parámetro.

**Ejemplo**

```js
repetition("cherry", 2) ➞ "cherrycherry"
```

32. Crear una función que acepte un array de números como parámetro, la función tiene que devolver la suma de todos los números negativos. Si la matriz no contiene números negativos, devuelve 0.

33. Crear una función con dos parámetros, el primer parámetro son todos los elementos del array y el segundo parámetro es el elemento que se va a mover al final del array.

**Ejemplo**

```js
moveToEnd([7, 8, 9, 1, 2, 3, 4], 9) ➞ [7, 8, 1, 2, 3, 4, 9]

moveToEnd(["a", "a", "a", "b"], "a") ➞ ["b", "a", "a", "a"]
```

34. Crear una función que acepte un string y retorne otro string pero con cada una de las letras repetidas una vez.

**Ejemplo**

```js
doubleChar("String") ➞ "SSttrriinngg" doubleChar("Hello World!") ➞ "HHeelllloo  WWoorrlldd!!"
```

35. Crear una función que acepte un número como parámetro, retorne un nuevo array en orden descendente.

**Ejemplo**

```js
sortDescending(123) ➞ [3, 2, 1]
```

36. Crear una función que acepte dos strings como parámetros, retorna true o false en caso de que los string sean un anagrama.

**Ejemplo**

```js
isAnagram("Dave Barry", "Ray Adverb") ➞ true. Ejemplo de Anagrama. Roma ➞ Amor
```

37. Crear una función que acepte un string y retorne un nuevo string pero en orden inverso.

**Ejemplo**

```js
reverseWords("the sky is blue") ➞ "blue is sky the". 
```

38. Crear una función que acepte un número y retorne el digito más alto de ese número.

**Ejemplo**

```js
highestDigit(377401) ➞ 7
```

39. Crear una función que acepte un número en formato string y retorne este número sin los ceros al inicio y al final de dicho número sin que afecten el valor del número.

**Ejemplo**

```js
removeZeros ("230.000") ➞ "230" 
removeZeros ("00402") ➞ "402"
removeZeros ("03.1400") ➞ "3.14" 
removeZeros("30") ➞ "30"
```

40. Crear una función que acepte un número y retorne la cantidad de dígitos que contiene dicho número. No puede convertir a string el número para resolver el ejercicio.

**Ejemplo**

```js
num_of_digits(1000) ➞ 4 
```

41. Crear una función que acepte un array de string y que retorne un nuevo array ordenado de la palabra más pequeña a la más grande.

**Ejemplo**

```js
sortByLength(["Turing", "Einstein", "Jung"]) ➞ ["Jung", "Turing", "Einstein"]
```

42. Crear una función que acepte tres números y retorne la cantidad de números que son iguales.

**Ejemplo**

```js
equal(3, 4, 3) ➞ 2
```

43. Crear una función que acepte un array de números, remueva los números duplicados utilizando la función “reduce”.

**Ejemplo**

```js
[18, 21, 1, 1, 51, 18, 21, 5, 18, 7, 10] ➞ [18, 21, 1, 51, 5, 7, 10]
```

44. Crear una función que acepte un array de números y retorne la sumatoria de los números cuadrados de los números ingresados.

**Ejemplo**

```js
sumOfPower([3, 4]) ➞ 25
```

45. Crear una función que acepte un string, y retorne un nuevo string con la primera letra de cada palabra en mayúsculas.

**Ejemplo**

```js
hola como estas ➞ Hola Como Estas
```

46. Crear una función que acepte dos números como parámetros, y retorne un nuevo array con los múltiplos del primer parámetro y que lleguen hasta el array alcance la longitud del segundo parámetro.

**Ejemplo**

```js
arrayOfMultiples(7, 5) ➞ [7, 14, 21, 28, 35] 
```

47. Crear una función que acepte un string y retone el string en orden inverso. Tiene que usar una función recursiva.

**Ejemplo**

```js
“hello” ➞ “olleh”
```

48. Crear una función que acepte un string, y retorne si el string es o no un palíndromo. Un palíndromo es una palabra que se lee igual de derecha a izquierda y viceversa.

49. Crear una función que acepte un array de números y retorne el segundo número más alto y el segundo número más pequeño.

**Ejemplo**

```js
[1,2,3,4,5] ➞ [2, 4]
```

50. Crear una función que acepte un string de países y retorne el país más grande.

**Ejemplo**

```js
["Australia", "Alemania", “Estados Unidos"] ➞ Estados Unidos
```

51. Crear una función que solicite un año al usuario, debe determinar si el año ingresado es bisiesto o no.

52. Crear una función que acepte dos números como parámetros, se debe retornar un nuevo array con rango de valores entre esos números. Debe usar una función recursiva.

**Ejemplo**

```js
range(2, 9) ➞ [3, 4, 5, 6, 7, 8]
```

53. Crear una función que acepte un array de números, calcule la sumatoria del cuadrado de los números ingresados utilizando una función de flecha y al final calcule el promedio.

54. Crear una función que acepte un número, su tarea es retornar la sumatoria de todos los dígitos de ese número.
**Ejemplo**

```js
124 ➞ 7
```

55. Crear una función que acepte un array de números, su tarea es rotar dicho array una posición a la izquierda.

**Ejemplo**

```js
[1, 2, 3] ➞ [2,3,1] 

```

56. Crear una función que acepte dos arrays como parámetros, su tarea es combinar ambos arrays en uno solo.

**Ejemplo**

```js
array1 = [1, 2, 3]; array2 = [4, 5, 6]; ➞ [1, 2, 3, 4, 5, 6] 
```

57. Crear una función que acepte un string como parámetro y determine si el string ingresado es un palíndromo, es decir, una palabra que se lee igual de izquierda a derecha y viceversa, debe usar una función recursiva.

58. Crear una función que reciba como parámetro un número de dos dígitos luego intercambie ese número y determine si el número ingresado es el menor.

**Ejemplo**

```js
lowestSwap(27) ➞ true 
lowestSwap(43) ➞ false
```

> **Explicación**: En el caso del 27, devuelve true debido a que el número invertido es 72, y 27 es menor que 72. En el caso del 43 devuelve false, debido a que el número invertido de 43 es 34 y 43 no es menor que 34.

59. Crear una función que reciba como parámetro dos números, el primero es el punto inicial y el segundo el punto final, su tarea es imprimir en un array el cubo de todos los números comprendidos entre los números ingresados por el usuario incluyendo dichos números.

**Ejemplo**

```js
cube(3, 5) ➞ [27, 64, 125]
```

60. Crear una función que reciba un parámetro numérico, en base a ese número calcular la serie de Fibonacci, usando una función recursiva.

```js
Serie de Fibonacci 0, 1, 1, 2, 3, 5, 8, 13, 21, 34…
```
