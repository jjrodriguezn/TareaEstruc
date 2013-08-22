TareaEstruc
===========
package piramide12;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.Reader;
import java.util.Scanner;


public class Piramide12 {

   
    public static void main(String[] args) throws IOException{
   
        int n;
        int c=0;
        int s;
        int m;
        int t=1;
        String h;
        
        
    
     Scanner digite = new Scanner(System.in);   
        System.out.print("ingrese un numero ");
        h = digite.next();
        n = Integer.parseInt(h);
        for(s=1; s<=n;s+=2){
        for(m=n;m>=1;m--){
        System.out.print(n+" ");
        c++;
        if(c==t){
        System.out.print("\n");
        c=0;
        t++;
        }
        
        }
        }
        
    }
}
