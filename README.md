# Factorial-de-un-numero
package factorialdeunnumero;
import java.util.*;

public class FactorialDeUnNumero {

   
    public static void main(String[] args) {
       Scanner lec=new Scanner(System.in);
       int N,C=2,F=1;
    
    System.out.print("Introduce un Número: ");
    N=lec.nextInt();
    
    while(C<=N){
    F=F*C;
    C++;
    }System.out.println("El Factorial de "+N+" es: "+F);
        
    }
    
}
