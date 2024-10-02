# EjercicioPractico2

### Enunciado 

Escribir un programa que haga que un conjunto de 10 hebras rellenen de forma
concurrente el contenido de un array de 1000 posiciones común a todas ellas.
Se tendrán en cuenta las siguientes indicaciones:

1. Se declarará una estructura del tipo est_t que consistirá en dos valores
   enteros, uno de ellos corresponderá a una posición del array (pos) y el
   otro al valor de relleno (val).


2. Se implementará una función rellenar sobre la que se crearán las hebras
   y que recibirá por parámetro un puntero a una estructura definidas en a).
   La función rellenará, a partir de la posición pos, 100 posiciones del array
   con el valor indicado por el campo val.


3. Se creará un programa que declare un array de 1000 posiciones de valores enteros, un array para 10 estructuras como las definidas en a) y un
   array para 10 hebras.


4. Se inicializará el array de estructuras para que cada una almacene en su
   campo pos una posición múltiplo de 100 (0, 100, 200,…,900) y en su
   campo val el entero resultante de la división entera entre pos y 100, es
   decir, los valores 0, 1, 2, …9.


5. Se crearán las hebras necesarias para rellenar el array. Se esperará a su
   terminación y se mostrará el array por pantalla