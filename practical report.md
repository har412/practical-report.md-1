## **PROGRAMMING FOR PROBLEM SOLVING ESC-18105**
### Name: _Gurdeep Singh_
### Roll Number: _1915023_
### Branch- _Computer Science_

## 1. Program to display a welcome message using puts
```C
#include<stdio.h>
int main()
{
puts("\nHELLO BUDDING ENGINEERS\n");
return 0;
}
```
## Output of Program
```C
HELLO TO BUDDING ENGINEERS
```

## 2. Program to print Address using puts.
```C
#inlude<stdio.h>
int main()
{
puts("Gurdeep Singh \n Roll no.:1915023 \n Department:CSE A1\n\
Address: #5104,st no 3, new shimlapuri,Ludhiana")
return 0;
}
```
## Output of Program
```C
Gurdeep Singh
Roll no.:1915023
Department:CSE A1
Address: #5104,st no 3, new shimlapuri,Ludhaiana
```
## 3. Program to find sum of two numbers
```C
#include<stdio.h>
int main()
{
int a=10,b=30,c;
c=a+b;
printf("The sum of numbers is %d",c);
return 0;
}
```
## Output of Program
```C
The sum of numbers is 40
```
## 4. Program to convert centigrade into fahrenheit.
```C
#include <stdio.h>

int main()
{
float celsius, fahrenheit;
printf("Enter temperature in Celsius: \n");
scanf("%f", &celsius);
fahrenheit = (celsius * 9 / 5) + 32;
printf("%.2f Celsius = %.2f Fahrenheit", celsius, fahrenheit);
return 0;
}
```
## Output of Program
```C
Enter the temperature in Celsius: 100
100 Celsius = 212.00 Fahrenheit
```
## 5. Program to find area and perimeter of circle.
```C
#include <stdio.h> 
float main()
{ float radius,perimeter,area;
 float pi=22/7.0;
printf("Enter the radius:");
scanf("%f",&radius);
perimeter=pi*2*radius;
area=perimeter*radius/2.0; 
printf("radius:%.1f\nperimeter:%.1f\narea:%.7f",radius,perimeter,area);
}
```
## Output of Program
```C
Enter the radius: 5
radius: 5.0
perimeter: 31.4
area: 78.5714264
```
## 6. Program to swap two numbers without using 3rd number.
```C
#include<stdio.h> 
int main()
{ int a,b;
printf("enter the numbers to swap:");
scanf("%d\t%d",&a,&b);
a=a+b;
b=a-b;
a=a-b;
printf("the result is %d\t%d",a,b);
return 0;
}
```
## Output of Program
```C
enter the numbers to swap: 3  9
the result is 9  3
```
## 7. Program to find odd or even number.
```C
#include <stdio.h>
int main ()
{ int s ;
printf ("Enter the integer:");
scanf ("%d",&s);
if (s%2==0)
printf ("The number is even");
else 
printf ("The number is odd:");
return 0;
}
```
## Output of Program
```C
Enter the integer: 3
The number is odd:
```
## 8. Program to find Factorial
```C
#include <stdio.h>
int main()
{
int c, n, fact = 1;
printf("Enter a number to calculate its factorial\n");
scanf("%d", &n); 
for (c = 1; c <= n; c++)
fact = fact * c;
printf("Factorial of %d = %d\n", n, fact);
return 0;
}
```
## Output of Program
```C
Enter a number to calculate its factorial
3
Factorial of 3 = 6
```
## 9. Program to find reverse of number.
```C
#include <stdio.h>
int main ()
{
int n , reverse =0;
printf ("Enter the number to be reversed:\n");
scanf ("%d",&n);

while(n!=0)
{
reverse = reverse*10;
reverse = reverse + n%10;
n=n/10;
}
printf ("Reverse number is:%d\n",reverse);
return 0;
}
```
## Output of Program
```C
Enter a number to be reversed:
265
Reverse number is:562
```
## 10. Program of multiple of 3 and 5(Fizz Buzz)
```C
#include <stdio.h>
int main ()
{
int a;
for (a=0;a<=15;a++)
if (a%3==0)
printf ("Fizz\n");
else if (a%5==0)
printf ("Buzz\n");
else if (a%15==0)
printf ("FizzBuzz\n");
else 
printf ("%d\t",a);
return 0;
}
```
## Output of Program
```C
1 2 fizz 4 buzz fizz 7 8 fizz buzz 11 fizz 13 14 fizzbuzz
```
## 11. Program of days of week using switch case
```C
#include <stdio.h>
int main()
{
printf("Enter 'm' for monday,\nt for tuesday,\nw for wednesday ,\nh for thursday,\nf for friday,\n\
s for saturday,\nd for sunday:");                         
scanf("%c",&ch);         
switch(ch)
{
case'm':
case'M':
printf("monday\n");
break;
case't':
case'T':
printf("tuesday\n");
break;
case'w':
case'W':
printf("wednesday\n");
break;
case'h':
case'H':
printf("thursday\n");
break;
case'f':
case'F':
printf("friday\n");
break;
case's':
case'S':
printf("saturday\n");
break;
case'd':
case'D':
printf("sunday\n");
break;
default:
printf("wrong input\n");
}
}
```
## Output of Program
```C
Enter 'm' for monday,                                                                                                         
t for tuesday,                                                                                                                
w for wednesday ,                                                                                                             
h for thursday,                                                                                                               
f for friday,                                                                                                                 
s for saturday,                                                                                                               
d for Sunday:h
thrusday
```
## 12. Program of calculator using switch case.
```C
#include<stdio.h>
int main()
{ int a,b,r;
int n;
printf("enter 1 for division,\n2 for multiplication,\n3 for addition,\n4 for subtraction \n");
scanf("%d",&n);
printf("enter the numbers:");
scanf("%d %d",&a,&b);
switch(n)
{
case 1:
r=a/b;
printf("after division answer is:%d\n",r);
break;
 case 2:
r=a*b;
printf("after multiplication answer is:%d\n",r);
break;
case 3:
r=a+b;
printf("after addition answer is:%d\n",r);
break;
case 4:
r=a-b;
printf("after subtraction answer is:%d\n",r);
break;
}
return 0;
}
```
## Output of Program
```C
enter 1 for division,                                                                                                           
2 for multiplication,                                                                                                           
3 for addition,                                                                                                                 
4 for subtraction                                                                                                           
 3                                                                                                                               
enter the numbers:
25                                                                                                            
23                                                                                                                              
after addition answer is:48 
```
## 13. Program to find if year is leap or not.
```C
#include<stdio.h>
int main()
{ 
int a;
printf("type year:");
scanf("%d",&a);
if(a%4=0)
printf("the year is leap");
else
printf("the year is not leap");
return 0;
}
```
## Output of Program
```C
type year:2016                                                                                                                
the year is leap 
```
## 14. Program check whether the number is prime or not.
```C
#include<stdio.h>
int main()
{ 
int a;
printf("type year:");
scanf("%d",&a);
if(a%4=0)
printf("the year is leap");
else
printf("the year is not leap");
return 0;
}
```
## Output of Program
```C
type year:2016                                                                                                                
the year is leap 
```






















