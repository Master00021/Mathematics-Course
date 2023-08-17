---
tags: higher-degree, syntheticdivision, therationalrootstest, polynomials, algebra
---


Como ocurre con las factorización de primos, esta solamente se puede aplicar sobre números que no sean primos. Si un numero es primo, eso significa que solamente se puede llegar a el multiplicándose por si mismo, junto con uno. 

Si no te habías dado cuenta hasta ahora, lo que hemos estado haciendo con los polinomiales, usando sus estrategias, de, **factorizarlos**, **completar el cuadrado** y utilizando la **formula cuadrática**, es literalmente encontrar los factores de los polinomios. Esto significa que, solamente los polinomios no sean primos, pueden ser resueltos utilizando alguna de estas tres estrategias previamente mencionadas. 

Eso quiere decir que, también existen los polinomios que son primos. Segun la siguiente formula.
#### $$ax^3+bx^2+cx+d$$
Cualquier polinomio que provenga de esta formula, _puede ser_ un polinomio primo.
Un ejemplo de un polinomio que es primo, y por consiguiente, no puede ser factorizado:
#### $$x^6+1$$
Sin embargo, el siguiente **si** puede ser factorizado:
#### $$x^6-1$$
**Necesitamos una forma para saber cuando un polinomial es divisible por una expresión particular.** Solamente así lograremos saber cuando utilizar cada herramienta para resolver el problema que tenemos enfrente de nosotros.

## Synthetic Division

Esta es similar a la **division larga**, la diferencia, es que en esta, utilizamos expresiones algebraicas dentro de la misma.

#### Performing Synthetic Division

#### $$x^4 + x^3 - 11^2 - 5x + 30 = 0$$
Esta estrategia puede ser utilizada solamente si ya sabemos una de las dos soluciones, y nos resultara de maravilla si tenemos entre manos una ecuación polinomial de grado 3 en adelante.

Primero, tenemos que barajar entre una seria de posibles respuestas correctas. 
Digamos que $x = 2$, y utilicémoslo, para ver si llegamos a la solución correcta.
Si resulta ser cierto, eso significa que el factor correcto seria $(x-2)$, el contrario de $2$.

[[Visual Synthetic Division|Visual Example.]]

La estrategia **division sintética**, es la mejor que hay para resolver ecuaciones polinomiales de gradeos superiores a 2. Es decir, de grado 3, 4, 5 y mas.

Pero falta una ultima parte para optimizar el uso de esta estrategia. Y eso es el como saber que números calcular para conseguir las soluciones. Tirar números al azar no nos llevara a ningún otro lado mas que perder el tiempo.

### The Rational Roots Test

Esta técnica nos dejara una lista llena de posibles soluciones por las cuales podemos probar.
Para conseguir dicha lista, primero tenemos que observar la expresión polinomial.
#### $$2x^3+3x^2-3x-2=0$$
Luego, hacemos una fracción basada en la expresión polinomial.
#### $$\frac{factors | of | the | constant | term}{factors | of | the | leading | coefficient}$$
En el numerador, pondremos todos los factores del termino constante, es decir, $d$.
En el denominador, pondremos todos los factores del primer termino, es decir, $a$.
#### $$\frac{1,2}{1,2}$$
Al ser ambos $2$, poseen los mismos factores.
Luego de esto, les agregamos un símbolo mas-menos.
Finalmente, resolvemos todas las posibles soluciones de este truco.
#### $$±1, ±\frac{1}{2}, ±2$$
Esta es la lista de posibles soluciones con la cual nos quedamos, con seis posibilidades.
Importante saber que estas son **posibles soluciones**, y que no siempre este truco nos dara alguna de la soluciones. Sim embargo, vale la pena usarlo, ya que si funciona, nos acortara el camino.
Ahora, pasamos al [[The Rational Root Test Visual Example|ejemplo visual.]]

Go [[Solving Higher-Degree Polynomials by Synthetic Division and the Rational Roots Test Comprehension|here]] for exercises.