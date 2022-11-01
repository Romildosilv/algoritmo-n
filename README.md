algoritmo-n
Intervalo //

#include <stdio.h>
#include <math.h>
float valor;


int main(){
    printf ("digite um valor: ");
    scanf("%f",&valor);
  if (valor>=0 && valor<=25){
  printf ("\nintervalo [0,25]");
  }
  else if (valor>=25 && valor<50){
 printf ("\nintervalo (25,50]");     
  }
  else if (valor>=50 && valor<75){
  printf ("\nintervalo (50,75]");
  }
  else if (valor>=75 && valor<100){
   ("\nintervalo (75,100]");
  }
  
else{
    printf("\nFora de intervalo");
}

    return 0;
}
