#include<stdio.h>

int main()
{
 int valor[5], i, soma=0;

 for(i=0; i<5; i++)
 {
 printf("informe o nmr: \n ", i+1);
 scanf("%d", &valor[i]);
 soma=soma+valor[i];
 }

 printf("O resultado eh: %d", soma);

} 
