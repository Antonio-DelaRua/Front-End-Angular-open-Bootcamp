
Definición:
-----------
La declaración switch evalúa una expresión, comparando el valor de 
esa expresión con una instancia case, y ejecuta declaraciones asociadas
 a ese case, así como las declaraciones en los case que siguen.

Syntaxis
switch (expresión) {
  case valor1:
    //Declaraciones ejecutadas cuando el resultado de expresión 
coincide con el valor1
    [break;]
  case valor2:
    //Declaraciones ejecutadas cuando el resultado de expresión 
coincide con el valor2
    [break;]
  ...
  case valorN:
    //Declaraciones ejecutadas cuando el resultado de expresión 
coincide con valorN
    [break;]
  default:
    //Declaraciones ejecutadas cuando ninguno de los valores 
coincide con el valor de la expresión
    [break;]
}
expresión
Es una expresión que es comparada con el valor de cada instancia case.
case valorN
Una instancia case valorN es usada para ser comparada con la expresión.
Si la expresión coincide con el valorN, las declaraciones dentro de la
 instancia case se ejecutan hasta que se encuentre el final de la
 declaración switch o hasta encontrar una interrupción break.
default
Una instancia default, cuando es declarada, es ejecutada si el 
valor de la expresión no coincide con cualquiera de las otras 
instancias case valorN.


Ejercicio:
-----------

package com.company;

public class Main {

    public static void main(String[] args) {
	var estacion = "Verano";
    switch (estacion){
        case "Primavera":
        case "Verano":
        case "Otoño":
        case "Invierno":

            System.out.println("estamos en :"+ estacion);
            break;
        default:
            System.out.println("por favor revise el contenido");
    }
    }
}