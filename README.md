#include<stdio.h>

int main()
{
int n1,n2;
int n3 = 2;
float n4 = 0.8;
int n5 = 4;
int n6 = 9;
int n7 = 35;
int n8 = n3 * n5;
float n9 = n4 * n6;

printf("CALCULADORA PARA UMA BOA DIETA\n");
printf("Informe o seu peso:");
scanf("%d", &n1);
printf("Informe quantas calorias voce pretende consumir diariamente:");
scanf("%d", &n2);
printf("Para uma boa alimentacao e ingestao de agua, eh recomendado:\n");
printf("------------------------------------------------------------\n");
printf("Proteinas = %d gramas\n", n1 * n3 * n5);
printf("Gorduras = %f gramas\n", n1 * n4 * n6);
printf("Carboidratos = %f gramas \n", n2 - ((n1 * n8) + (n1 * n9)));
printf("Agua = %d\n", n1 * n7);
printf("------------------------------------------------------------\n");
return 0;
}
