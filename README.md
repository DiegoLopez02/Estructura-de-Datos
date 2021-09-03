package examen.diagnostico;
import java.util.Scanner;

public class Ejercicio_1 {
    public void matriz1(){
        Scanner teclado = new Scanner(System.in);
        
        System.out.println("Ingrese el tamaño de la matriz: ");  //Aquí se declara la medida de la matriz
        int n = teclado.nextInt();
        
        for(int i = 0; i < n; i++)  //Este ciclo determina la fila superior del marco
        {
            System.out.print("*");
        }
        
        System.out.println();  //Esta instrucción da un salto de linea
        
        for(int i = 0; i < n - 2; i++)  //Este ciclo determina el "cuerpo" del marco
        {
            System.out.print("*");
            for(int j = 0; j < n - 2; j++)
            {
                System.out.print(" ");
            }
            System.out.println("*");
        }
        for(int i = 0; i < n; i++)  //Este ciclo determina la fila inferior del marco
        {
            System.out.print("*");
        }
        System.out.println();  //Esta instrucción da un salto de linea
    }
}
//NOTA: Este ejercicio es el 3° del examen; lo hice con matriz cuadrada porque se me hizo mas facil hacerlo de este modo.
