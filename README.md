# code-Arrays
Leer 4 números, guardarlos en un arreglo y mostrarlos en el mismo orden introducido
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package arrays1;

import java.util.Scanner;

/**
 *
 * @author GoPenTest
 */
public class Arrays1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        Scanner entrada = new Scanner (System.in); //se crea una entrada de datos
        
        int numeros [] = new int [4]; //Se define el tipo de dato y el nombre del arreglo y los espacios.
       System.out.println("Datos del arreglo"); // se realiza un enunciado de lo datos del arreglo.
      for(int i=0;i<4;i++) { // se crea un ciclo bucle for 
          System.out.print((i+1)+". Digite un numero: ");
          numeros [i] = entrada.nextInt(); //el iterador comienza en el indice 0 y como avanza el bucle y el arreglo es de tipo de dato in 
      }
      
       System.out.println("\nimprimir los numeros del arreglo");
          for(int i:numeros){
             System.out.println(i);
        
    }
    
        
    }
}
    

