# Traductor de números a binario

## Introducción al programa
Este programa se trata de un traductor de números al código binario, **el programa es compatible con números naturales y negativos**, el procedimiento es sencillo 😄.

## Uso correcto del programa
_El programa es más simple imposible_:
-1️⃣: El programa te pedirá un número en decimal **entero**.
-2️⃣: el programa te pide un número de bits (los bits son los dígitos que tendrá el número en binario).
-3️⃣: ¡Disfruta de tu número recién traducido!

## ¿Cómo funciona?
El programa se basa en una única función llamada ***dec2bin***.
1. El programa primero pide el valor de las variables **numero_decimal** y **numero_bits**.
2. El programa usa esas mismas variables para establecer otra variable llamada **numero_binario** como el resultado de **dec2bin(numero_decimal, numero_bits).
3. La función **dec2bin** comprueba si el número es mayor o igual a 0, si es así los bits sobrantes serán rellenados con varios 0's a la izquierda, sino rellenará con 1's a la izquierda.
4. Finalmente retorna el valor a la variable, para que el print() final muestre texto y el valor de las tres variables.

## Fin
![Rick tells you to say goodbye](https://i.pinimg.com/1200x/39/80/81/398081ba32bcccafeb73ec1a67e830bd.jpg)
