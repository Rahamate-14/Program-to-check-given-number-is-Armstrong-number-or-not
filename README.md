# Program-to-check-given-number-is-Armstrong-number-or-not
#include<stdio.h>
void main()
{
int s=0,n,r,t;
printf("enter a number: ");
scanf("%d",&n);
t=n;
while (n>0)
{
r=n%10;
s=s+(r*r*r);
n=n/10;
}
if(t==s)
      printf("\n %d is armstrong number ",t);
 else
      printf("\n %d is not armstrong number ",t);
 }
