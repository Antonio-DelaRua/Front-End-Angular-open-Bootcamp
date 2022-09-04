
Definición:
------------

Utilice la sentencia FOR para crear un bucle de programa FOR...NEXT. Un bucle de programa es una serie de sentencias que se ejecutan repetidamente hasta que se ha llevado a cabo el número de repeticiones especificado o hasta que se cumplen las condiciones especificadas.

Se asigna a *variable* el valor de *inicio*, que es el valor inicial del contador. En *fin* se especifica el valor final del contador.

Las *sentencias.bucle* que siguen a la cláusula FOR se ejecutan hasta que se encuentra la sentencia NEXT. El contador se ajusta conforme al valor especificado por la cláusula STEP.


Ejercicio:
-----------

package com.company;

public class Main {

    public static void main(String[] args) {
	for (int numeroFor = 0; numeroFor <= 3; numeroFor = numeroFor + 1){
        System.out.println(numeroFor);
     }
    }
}