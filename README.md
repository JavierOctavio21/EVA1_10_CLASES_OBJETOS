import MisClases.OtraClase;
import java.util.Scanner;

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author Javier Octavio
 */
public class Principal {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner input = new Scanner(System.in);
        input.nextLine();
        int iVal = 10;
        Ejemplo eMiObjetoEjem;
        eMiObjetoEjem = new Ejemplo();
        
        Ejemplo eObj2 = new Ejemplo();
        
        Ejemplo eObj3;
        
        OtraClase oOtroObj = new OtraClase();
        
        System.out.println(eMiObjetoEjem);
    }
    
}
//TIPOS ABSTRACTOS DE DATOS
class Ejemplo{
    int iVal = 10;

}
