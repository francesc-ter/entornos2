# Tarea de depuracion 3.

1. Explicar QUÉ HACE EL MÉTODO MAIN.

El main de este ejercicio hace que se ejecute el programa creando una lista con un constructor. Para ello ultiliza la clase cosa y el propio main.

2. Poner un punto de ruptura (breakpoint) en la línea 26 (primer bucle del método main) y,
basándoos en los valores que van tomando las variables, explicad qué hace y cómo
funciona el método. Podéis crear tablas para ver cómo cambian los valores de las
variables y del array.

El primer bucle lo que hace es rellenar la lisa hasta que la variable i sea mayor a la variable kMAX. En este caso kMAX es 10. entonces pedira 10 numeros. 

El primer paso de este bucle es pedir un numero por teclado, luego comprueva el numero y lo introduce en una de las dos listas, para ello utiliza un if y un else. Lo que hacen estos comandos es evitar que un numero se repita y se meta 2 veces en la lista. En caso que se repita entra en otra lista y va contando las veces que se va repitiendo los valores. 

Por ejemplo si el primer numero que introducimos es 1 este ira directamente a la lista y el construtor lo creara y c (que es el hueco donde se va a trabjar) suma uno cuando termina de meter el valor en la lista. Luego si volvemos a introducir el numero 1 cuando nos pida otro valor entra en el if y lo que pasa es que el numero se covierte en 1 para ir conando las veces que se ha repetido un numero.

3. Basándoos en el funcionamiento, determinad qué indican o a qué hacen referencia
las variables “a” y “b” de la clase “cosa”.

Basándonos en la funcionamiento del programa vemos que la variable de "a" hace referencia al numero me que se intoduce por teclado para incormporarlo a la lista, y la varible "b" hace referecnia a la cantidad de veces que se ha metido ese numero.

a = es enumero que metes

b = es la cantidad de veces que has metido ese numero 