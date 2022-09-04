Sumar 3 parametros
----------------------------------------------------------------------
package com.company;


public class Main {

    public static void main(String[] args) {
        Ejercicio( 10,  46 , 40);
    }
        public static void Ejercicio(int a, int b, int c)  {
        int resultado;
        resultado = a + b + c ;

        System.out.println(resultado);

            

    }
}

Poner valores en el main
-----------------------------------------------------------------------
public class Main {

    public static void main(String[] args) {
	  int a = 10;
      int b = 30;
      int c = 20;
      Ejercicio(a, b, c);

      System.out.println(a + b + c);
    }
    public static void Ejercicio(int a, int b, int c){

    }
}

clase coche
-----------------------------------------------------------------------
pag:main
-----------------------------------------------------------
public class Main {

    public static void main(String[] args) {
	Coche micoche= new Coche();
    micoche.agregarP();
    micoche.agregarP();
    micoche.agregarP();
    micoche.agregarP();
    micoche.mostrarP();


    }

}



////////////////////////////////////////////


pag class coche
-------------------------------------------------
public class Coche {
    int numeroP=0;

    Coche(){

    }
    public void agregarP(){
        numeroP++;
    }
    public void mostrarP() {
        System.out.println("La cantidad de puerta es:"+numeroP);
    }
}