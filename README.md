#include<stdio.h>
int main ()
{
    int p=10,t=10,r=5;
    float simple_interest;
    scanf("%d%d%d",p,t,r);
    simple_interest=p*t*r/100.0;
    printf("the simple interest is %d",simple_interest);
    return 0;
}

#include<stdio.h>
int main ()
{
    float f,c;
    scanf("%d",&f);
    c=f*0.5-32*0.5;
    printf("the celsius is %f",c);
    return 0;
}

int main ()
{
    int l,b,perimeter,area;
    scanf("%d%d",&l,&b);
    perimeter=2*l+2*b;
    area=l*b;
    printf("the perimeter is %d",perimeter);
    printf("the area is %d",area);
    return 0;
}

int main ()
{
    int a,area;
    scanf("%d",&a);
    area=a*a;
    printf("the area of the square is %d",area);
    return 0;
}

int main ()
{
    int r;
    float area;
    scanf("%d",&r);
    area=3.14*r*r
    printf("the area is %d",area);
    return 0;
}

int main ()
{
    int a,b;
    float area;
    scanf("%d%d",&a,&b);
    area=1/2.0*a*b;
    printf("the area of the triangle is %f",area);
    return 0;
}

int main ()
{
    float f,c;
    scanf("%d",&c);
    f=c*1.8+32;
    printf("the farenheit is %f",f);
    return 0;
}

int main ()
{
    float a,b,sum;
    scanf("%f%f",&a,&b);
    sum=a+b;
    printf("the sum of floating points is %f",sum);
    return 0;
}

int main ()
{
    int a,b,sum;
    scanf("%d%d",&a,&b);
    sum=a+b;
    printf("the sum of two integers is %d",sum);
    return 0;
}

//To display our name.
#include<stdio.h>
int main()
{
printf("My name is panda");
printf("Welcome to SIMATS");
return 0;
}


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


#include <stdio.h>

int main()
{
    int i;

    for(i = 1; i <= 10; i++)
    {
        if(i == 5)
            break;

        printf("%d ", i);
    }

    return 0;
}


#include <stdio.h>

int main()
{
    int i;

    for(i = 1; i <= 10; i++)
    {
        if(i == 5)
            continue;

        printf("%d ", i);
    }

    return 0;
}


#include <stdio.h>

int main()
{
    int i = 1;

start:
    if(i <= 5)
    {
        printf("%d ", i);
        i++;
        goto start;
    }

    return 0;
}


#include <stdio.h>

int main()
{
    int i = 1;

    while(i <= 10)
    {
        printf("%d\n", i);
        i++;
    }

    printf("END");

    return 0;
}


#include <stdio.h>

void main() {
    int i = 1; // Initialize variable
    
    while (i <= 10) { // Condition to check if i is less than or equal to 10
        printf("%d ", i);
        i++; // Increment i by 1
    }
}


#include <stdio.h>

void main() {
    int i = 10; // Initialize variable at 10
    
    while (i >= 1) { // Condition to check if i is greater than or equal to 1
        printf("%d ", i);
        i--; // Decrement i by 1
    }
}


#include <stdio.h>

void main() {
    int i = 1;
    
    while (i <= 10) {
        if (i % 2 == 1) { // Check if remainder is 1
            printf("%d ", i);
        }
        i++; // Move to the next number
    }
}


#include <stdio.h>

void main() {
    int i = 1;
    
    while (i <= 10) {
        if (i % 2 == 0) { // Check if remainder is 0
            printf("%d ", i);
        }
        i++; // Move to the next number
    }
}


#include <stdio.h>

void main() {
    int i = 1, sum = 0; // Initialize sum at 0
    
    while (i <= 10) {
        sum = sum + i; // Add the current value of i to sum
        i++;
    }
    
    printf("sum = %d\n", sum);
    printf("END");
}


#include <stdio.h>

void main() {
    int i = 1, sum = 0;
    
    while (i <= 10) {
        if (i % 2 == 1) { // Only add to sum if the number is odd
            sum = sum + i;
        }
        i++; // Increment happens every time to check the next number
    }
    
    printf("sum = %d\n", sum);
    printf("END");
}


#include <stdio.h>

void main() {
    int i = 1, factorial = 1; // Start with 1 because multiplying by 0 results in 0
    int n = 5; // Example: Finding the factorial of 5
    
    while (i <= n) {
        factorial = factorial * i; // Multiply the current total by i
        i++;
    }
    
    printf("factorial = %d\n", factorial);
    printf("END");
}


#include <stdio.h>
int main()
{
    int a = 0, b = 1, c, i = 1, sum = 0;
    sum = a + b;
while(i <= 8)
    {
        c = a + b;
        sum = sum + c;
        a = b;
        b = c;
        i++;
    }
printf("Sum of first 10 Fibonacci numbers = %d", sum);
return 0;
}


#include<stdio.h>
int main ()
{
    int a=7,b=5,c=2;
    scanf("%d%d%d",&a,&b,&c);
    if ((a>b)&&(a>c)){
        printf("a is the greatest");
    }
    else if (b>c)
    printf("b is the greatest");
}
else {
printf("c is the greatest")
}
return 0;
}


#include<stdio.h>
int main ()
{
    int marks=89;
    scanf("%d",&marks);
    if (marks<0 && marks>100){
        printf("invalid");
    }
    else if (marks>=90){
    printf("grade is a");
  }
else if (marks>=80){
    printf("grade is b");
  }
else if (marks>=70){
    printf("grade is c");
  }
else if (marks>=60){
    printf("grade is d");
  }
else if (marks>=50){
    printf("grade is e");
  }
else {
    printf("fail");
  }
return 0;
}


#include<stdio.h>
int main ()
{
    int a=2024;
    scanf("%d",&a);
    if (a%4==0){
        printf("a is leap year");
    }
    else 
    printf("b is not leap year");
}


#include<stdio.h>
int main ()
{
    int a=7,b=10;
    int max;
    max=(a>b)?a:b;
    printf("the maximum value is:%d",max);
    return 0;
}


int main()
{
    int percentage;

    printf("Enter the student's percentage: ");
    scanf("%d", &percentage);

    if (percentage >= 0 && percentage <= 100)
    {
        if (percentage >= 90)
        {
            printf("Grade: A");
        }
        else if (percentage >= 80)
        {
            printf("Grade: B");
        }
        else if (percentage >= 70)
        {
            printf("Grade: C");
        }
        else if (percentage >= 60)
        {
            printf("Grade: D");
        }
        else if (percentage >= 50)
        {
            printf("Grade: E");
        }
        else
        {
            printf("Fail");
        }
    }
    else
    {
        printf("Invalid input. Percentage must be between 0 and 100.");
    }

    return 0;
}



int main() {
    int num = -15;
    if (num < 0) {
        num = num * -1; 
    }
    printf("The absolute value is %d\n", num);
    return 0;

    
int main ()
{
    int a=7,b=5,c=2;
    scanf("%d%d%d",&a,&b,&c);
    if ((a>b)&&(a>c)){
        printf("a is the greatest");
    }
    else if (b>c)
    printf("b is the greatest");
}
else {
printf("c is the greatest")
}
return 0;
}
0 commit comments
Comments


int main ()
{
    int a=7;
    scanf("%d",&a);
    if ((a>=0)&&(a<=100)){
        printf("within range");
    }
    else {
    printf("not in range");
}
return 0;
}


int main ()
{
    char ch;
    scanf("%c",&ch);
    if (ch>='a' && ch<='z'){
        printf("within range");
    }
    else {
    printf("not in range");
}
return 0;
}
0 commit comments
Comments


int main ()
{
    int a=7;
    scanf("%d%d",&a);
    if ((a%5==0)||(a%3==0)){
        printf("a divisible by 5 or 3");
    }
    else 
    printf(" a is not divisible by 5 or 3");
}
0 commit comments
Comments


int main()
{
int i,x,y;
i=10;
x=i++;
y=++i;
printf("post increment=%d",x);
printf("pre increment=%d",y);
return 0;
}


int main()
{
    int day;

    printf("Enter a number (1-7): ");
    scanf("%d", &day);

    switch(day)
    {
        case 1:
            printf("Monday");
            break;

        case 2:
            printf("Tuesday");
            break;

        case 3:
            printf("Wednesday");
            break;

        case 4:
            printf("Thursday");
            break;

        case 5:
            printf("Friday");
            break;

        case 6:
            printf("Saturday");
            break;

        case 7:
            printf("Sunday");
            break;

        default:
            printf("Invalid input");
    }

    return 0;
}
