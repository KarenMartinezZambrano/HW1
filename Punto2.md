# HW1
 Este código calcula los primeros numeros primos de Fibonacci
 
public class PrimosFibonacci {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
    long n=3;
    long a=1;
    long b=1;
    long c;
    while(true) {
    c=a+b;
    a=b;
    b=c;
    if(n==4) {
    System.out.println("F"+n+": "+c); 
    }else {
    boolean primo=true;
    for(int i=2; i<n; i++) {
    if(n%i==0) {
    primo=false;
    }
    }
    if(primo==true) {
    boolean primoFibonacci=true;
    for(int i=2; i<c; i++) {
    if(c%i==0) {
    primoFibonacci=false;
    }
    } 
    if(primoFibonacci) {
    System.out.println("F"+n+": "+c); 
    }
    }
    }
    n++;
    }
    
    }
}

