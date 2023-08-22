#include<stdio.h>
void main ()
{
int x;
int *p1;
p1=&x;
*p1=30;
printf("%d",x);
}
