# Codigosolucion
Este codigo calcula la cantidad de claves de involucion de 2X2 con determinante -1 


package sistemaafin;

public class Sistemaafin {

    public static void main(String[] args) {
        int cont=0;
            for (int a = 0; a < 26; a++) {
                for (int b = 0; b < 26; b++) {
                    for(int c=0;c<26;c++)
                    {
                    if((a*a+b*c)%26==1)
                    {
                    cont++;
                    }
                    }
                }
            }
        System.out.println(cont);
    }

}
