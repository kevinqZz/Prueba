/* 
 * Programa que calcula el volumen de una esfera
 */
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        double radio, volumen;
        System.out.print("Introduzca radio de la esfera: ");
        radio = sc.nextDouble();
        System.out.println("Volumen de la esfera de radio " + radio + " = " + (4.0/3)* Math.PI * Math.pow(radio, 3));  
    }
}
