# program1
program to check whether number is positive or negative or zero
#include<stdio.h>
void main()
{
 int n;
 printf("Enter the number");
 scanf("%d",&n);
 if(n < 0)
 {
   printf("the number is negative");
 }
 else if( n>0)
 {
   printf("The number is positive");
 }
 else
 {
    printf("The number is zero");
 }
 return 0;
}
