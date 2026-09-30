#include <stdio.h>
int main()
{
float unit,rate,bill;
printf(”enter units consumed");
scanf(”%f",&unit);
printf(”enter rate per unit");
scanf(”%f,&rate);
bill=unit*rate;
printf(”total electricity bill=%2f"bill);
  return 0;
}