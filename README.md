# peso
package peso;

import java.util.Scanner;

public class Peso {

    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        
        int peso;
        
        System.out.print("Introduzca el peso: ");
        peso = entrada.nextInt();
        
        if(peso>40 && peso<=50){
            System.out.println("\nLa persona es muy delgada");
        }
        else if(peso>50 && peso<=70){
            System.out.println("\nLa persona es delgada");
        }
        else if(peso>70 && peso<=90){
            System.out.println("\nLa persona tiene un peso normal");
        }
        else if(peso>90){
            System.out.println("\nLa persona esta gorda");
        }
        else{
            System.out.println("\nTiene anemia");
        }
        
        
    }
    
}
