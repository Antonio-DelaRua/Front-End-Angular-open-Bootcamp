
WHILE
--------------------------------------------------------------------
Definición:
Utilice la sentencia `while` para ejecutar en bucle un conjunto de instrucciones hasta que se cumpla una condición determinada.

Puede utilizar la sentencia `while` para repetir un conjunto de operaciones hasta que se cumpla la condición especificada. La sentencia `while` utilizada en el Lenguaje de políticas de Impact es la misma que la utilizada en lenguajes de programación tales como C, C++ y Java.

La sintaxis de la sentencia `while` consta de la palabra clave `while` seguida de una expresión booleana encerrada entre paréntesis. Esta expresión está seguida por un bloque de sentencias delimitado por llaves de cierre.

ejercicio:
----------
public class Main {

    public static void main(String[] args) {
	int numero = 2;
    while (numero > 1){
        System.out.println(numero );
        numero = numero +1;
    }
    }
}


DO WHILE
-----------------------------------------------------------------------
Definición:

En caso de que la condición se cumpla, se volverá a repetir este proceso hasta que se deje de cumplir la condición, mientras que en el bucle While
 se comprueba la condición antes de ejecutar el código, siendo ésta es la única diferencia entre los bucles While y Do While.

Ejercicio:
----------

package com.company;

public class Main {

    public static void main(String[] args) {
	 int marcador = 10;

     do{
         System.out.println(marcador);
         marcador = marcador -1;
     } while (marcador > 1);
    }
}