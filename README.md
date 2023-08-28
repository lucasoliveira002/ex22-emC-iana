# ex22-emC-iana
#include <stdio.h>
int main(void){
    int n, num;

    // TESTE DO COMANDO WHILE
    
while (num < 4)
{

printf ("\n Digite um numero:");
scanf ("%d", & n);


 if (n>0 && n<20){
 switch (n)
  {
    case 1 :
    printf ("um \n");
    break;
    case 2 :
    printf ("dois \n");
    break;
    case 3 :
    printf ("tres \n");
    break;
    case 4 :
    printf ("quatro \n");
    break;
    case 5 :
    printf ("cinco \n");
    break;
    case 6 :
    printf ("seis \n");
    break;
    case 7 :
    printf ("sete \n");
    break;
    case 8 :
    printf ("oito \n");
    break;
    case 9 :
    printf ("nove \n");
    break;
    case 10 :
    printf ("dez \n");
    break;
    case 11 :
    printf ("onze \n");
    break;
        case 12 :
    printf ("doze \n");
    break;
        case 13 :
    printf ("treze, FAZ O L\n");
    break;
        case 14 :
    printf ("catorze ou quatorze \n");
    break;
        case 15 :
    printf ("quinze \n");
    break;
        case 16 :
    printf ("dezesseis \n");
    break;
        case 17 :
    printf ("dezessete \n");
    break;
        case 18 :
    printf ("dezoito \n");
    break;
        case 19 :
    printf ("dezenove \n");
    break;
  }
  }
  if (n>=20){
if (n/10==2){
    printf (" vinte");}
    if (n/10==3){
    printf (" trinta");}
    if (n/10==4){
    printf (" quarenta");}
    if (n/10==5){
    printf (" cinquenta");}
    if (n/10==6){
    printf (" sessenta");}
    if (n/10==7){
    printf (" setenta");}
    if (n/10==8){
    printf (" oitenta");}
    if (n/10==9){
    printf (" noventa");}

if (n%10==1){
    printf (" e um");}
if (n%10==2){
    printf (" e dois");}
if (n%10==3){
    printf (" e tres");}
if (n%10==4){
    printf (" e quatro");}
if (n%10==5){
    printf (" e cinco");}
   if (n%10==6){
    printf (" e seis");}
   if (n%10==7){
    printf (" e sete");}
   if (n%10==8){
    printf (" e oito");}
   if (n%10==9){
    printf (" e nove");}

if (n==100){
    printf("\n cem");
}
  }
num ++;
}
return 0;
}
