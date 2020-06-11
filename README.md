#include<stdio.h>
int main()
{
float p,r,t,simpleinterest;
printf("enter principal\n");
scanf("%f",&p);
printf("enter rate\n");
scanf("%f",&r);
printf("enter time\n");
scanf("%f",&t);
simpleinterest=(p*r*t)/100;
printf("simpleinterest=%f",simpleinterest);
return 0;
}
