//Find the area of circle
#include<stdio.h>
void main()
{
constant float pi=3.14;
float r=10,area;
area=pi*r*r;
printf("%.2f",area);
}

//FInd the area of circle using define
#include<stdio.h>
#define pi 3.14
void main()
{
int r;
float area;
area=pi*r*r;
printf(".2f",area);
}

//decimal to octal
#include<stdio.h>
void main()
{
int a=20;
printf("Octal number=%o",a);
}

//decimal to hexa
#include<stdio.h>
void main()
{
int a=20;
printf("Hexadecimal=%x",a);
}

//Octal to decimal
#include<stdio.h>
void main()
{
int a=010;
printf("Decimal=%d",a);
}

//Hexadecimal to decimal
#include<stdio.h>
void main()
{
int a=0x15;
printf("Decimal=%d",a);
}

//Print character and find ASCII value
#include<stdio.h>
void main()
{
char ch='g';
printf("ch=%c\n",ch);
printf("ch=%d,hence an integer\n",ch);
printf("ch1=%c\n,ch+1);
printf("ch1=%d,hence an integer",ch+1);
}

//To find quotient and ramainder
#include<stdio.h>
int main()
{
int a=5;
int q,r;
q=a/2;
r=a%2;
printf("Quotient=%d\n",q);
print("Remainder=%d",r);
return 0;
}

//Area of traingle
#include<stdio.h>
int main()
{
int b=3,h=3;
float area;
area= (1/2.0)*b*h;
printf("Area=%.2f",area);
return
}

//To swap two integers using third variable
#include<stdio.h>
int main()
{
int a=10,b=20,t;
printf("a=%d\tb=%d\n",a,b);
t=a;
a=b;
b=t;
print("a=%d\tb=%d",a,b);
return 0;
}

//Swapping without third variable
#include<stdio.h>
int main()
{
int a=10,b=20;
printf("a=%d\tb=%d\n",a,b);
a=b;
b=a/2;
printf("a=%d\tb=%d",a,b);
return 0;
}

//To dispaly a number if it is negative
#include<stdio.h>
int main()
{
int number;
scanf("%d",&number);
if (number<0){
printf("You entered %d\n",number);
}
printf("The if statement is easy");
return 0;
}

//To find whether a integer is odd or even
#include<stdio.h>
int main()
{
int n;
printf("Enter the number= ");
scanf("%d",&number);
if (n%2==0){
printf("%d is even",n);
}
else{
printf("%d is odd",n);
}
return 0;
}

//Eligible to vote or not
#include<stdio.h>
int main()
{
int age;
printf("Enter the age =");
scanf("%d",&age);
if (age>18)
{
print("%d is eligible to vote",age);
}
else{
printf("%d is not elligible to vote",age);
}
return 0;
}

//To find a student pass or fail
#include<stdio.h>
int main()
{
int n;
printf("Enter the n= ");
scanf("%d",&n);
if (n>=35)
{
printf("%dis pass",n);
}
else
{
printf("%d is fail",n);
}
return 0;
}
