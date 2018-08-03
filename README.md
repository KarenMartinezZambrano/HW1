# HW1
 Este código calcula los primeros n términos de una serie geométrica 
 
public class SerieGeometrica {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
    double a = 2;
    double r = 0.9;
    double n = 100;
    double resultado=0;
    for(int i=0; i<n; i++) {
    resultado+=a*Math.pow(r, i);
    }
    System.out.println(resultado);
    }
    
}
