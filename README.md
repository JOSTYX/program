# program
public  void reves(String palabra) 
{  
     int em=0;
     int eM=0;
     String aux=""; 
     for(int i=palabra.length()-1;i>=0;i--) 
     { 
       if(palabra.charAT(i)=="e"){
         em++;
        }
        if(palabra.charAT(i)=="E"){
         eM++;
        }

       aux=aux+palabra.charAt(i); 
     } 
    System.out.println(aux); 
    System.out.println(''Frecuencia de e: ''+(em+eM))
} 
