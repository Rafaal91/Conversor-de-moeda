# Conversor-de-moeda

package primeiroprogram;

import java.util.Scanner;




/**
 *
 * @author rafael.silva
 */
public class PrimeiroProgram {

    /**
     *Classe principal
     */
    public static void main(String[] args) {
        // TODO code application logic here
    
      //Declarando Entrada de dados
       Scanner teclado = new Scanner(System.in);
       
       //entrada 
        System.out.print("Digite o valor é reais: ");
         Float real = teclado.nextFloat();
         
       //Saida de moeda convertida
        System.out.printf("$ %.2f \n", real / 5.08);
          System.out.printf("€ %.2f \n", real / 5.80);
          System.out.printf("£ %.2f \n", real / 6.29);
          System.out.printf("# %.2f \n", real * 22.10);
       
        
        
    }
    
}
