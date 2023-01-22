# ejercicio-3-open-bootcamp

public class Main {
    public static void main(String[] args) {
        suma(5, 25, 15);

        Coche coche = new coche();

        coche.agregarpuerta();
        System.out.println("El coche ahora posee: " + coche.puertas + ".");
    }
 // Primera parte:
   public static void suma(int num1, int num2, int num3) {
       int resultado;

       resultado = num1 + num2 + num3;
       system.out.println("El resultado de la suma de números es: " + resultado + ".");
       }
   }


   class Coche {
    public int puertas= 4;

    public void agregarPuerta() {
       this.puertas++;


    }
}
