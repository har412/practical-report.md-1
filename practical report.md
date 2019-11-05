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
#include <stdio.h>
int main()
{
int i, num, p = 0;
printf("Please enter a number: \n");
scanf("%d", &num);
for(i=1; i<=num; i++)
{
if(num%i==0)
{
p++;
}
}
if(p==2)
{
printf("Entered number is %d "\
"and it is a prime number.",num);
}
else
{
printf("Entered number is %d "\
"and it is not a prime number.",num);
}
}
```
## Output of Program
```C
Please enter a number: 4                                                                                                 
Entered number is 4 and it is not a prime number.  
```
## 15. Program to find number is palindrome or not.
```C
#include <stdio.h>
int main ()
{
    int n, reverse=0,t;
    printf("Enter a number to check if it is a palindrome or not\n");
    scanf("%d",&n);
    t=n;
    while (t!=0)
    {
     reverse = reverse*10;
     reverse = reverse + t % 10;
     t = t/10;
     }
if (n==reverse)
printf ("%d is a palindrome number.\n",n);
else 
printf ("%d is not a palindrome number.\n",n);
return 0;
}
```
## Output of Program
```C
Enter a number to check if it is a palindrome or not 2546452                                                     
2546452 is a palindrome number.
```
## 16. Program to display Fibonacci Series up to n number of terms.
```C
#include <stdio.h>
int main()
{
    int i, n, t1 = 0, t2 = 1, nextTerm;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");
    for (i = 1; i <= n; ++i)
    {
        printf("%d, ", t1);
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }
    return 0;
}
```
## Output of Program
```C
Enter the number of terms: 10                                                                                                 
Fibonacci Series: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34
```
## 17. Program to enter and print elements of array (1d)
```C

#include <stdio.h>
int main()
{
    int i[5],a;
    printf("enter the elements of array:");
    for(a=0;a<5;a++)
    {
    scanf("%d",&i[a]);
    }
    for(a=0;a<5;a++)
    {
    printf("array i[%d]=%d\n",a,i[a]);
    }
    return 0;
}
```
## Output of Program
```C
enter the elements of array:25                                                                                              
26                                                                                                                          
27                                                                                                                           
28                                                                                                                           
29                                                                                                                           
array i[0]=25                                                                                                                
array i[1]=26                                                                                                                
array i[2]=27                                                                                                                
array i[3]=28                                                                                                                
array i[4]=29
```
## 18. Program to enter and print elements of array (2d)
```C

#include <stdio.h>
int main()
{
    int i[5][2],a,b;
    printf("enter the elements of array:");
    for(a=0;a<5;a++)
    {
    for(b=0;b<2;b++)
    scanf("%d",&i[a][b]);
    }
    for(a=0;a<5;a++)
    {
    for(b=0;b<2;b++)
    printf("array i[%d][%d]=%d\n",a,b,i[a][b]);
    }
    return 0;
}
```
## Output of Program
```C
enter the elements of array:1                                                                                                
2                                                                                                                             
3                                                                                                                             
4                                                                                                                             
5
6
7
8
9
10
array i[0][0]=1
array i[0][1]=2
array i[1][0]=3
array i[1][1]=4
array i[2][0]=5
array i[2][1]=6
array i[3][0]=7
array i[3][1]=8
array i[4][0]=9
array i[4][1]=10 
```
## 19. Program to print matrix.
```C
#include <stdio.h>
int main()
{
   int a[3][3],b,c;
   for(b=0;b<3;b++)
   {
   for(c=0;c<3;c++)
   {
   printf("the value of array[%d][%d]:",b,c);
   scanf("%d",&a[b][c]);
   }
   }
   for(b=0;b<3;b++)
   {
   for(c=0;c<3;c++)
   {
   printf("%d\t",a[b][c]);
   }
   printf("\n");
   }
    return 0;
}
```
## Output of Program
```C
the value of array[0][0]:1                                                                                                  
the value of array[0][1]:22
the value of array[0][2]:333
the value of array[1][0]:11
the value of array[1][1]:222
the value of array[1][2]:3333
the value of array[2][0]:111
the value of array[2][1]:2222
the value of array[2][2]:33333
1       22      333
11      222     3333
111     2222    33333 
```
## 20. Program to add two matrices.
```C
#include<stdio.h>
int main()
{
int a[5][4],b[4][5],c[5][5],i,j;
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("enter value of 1st [%d] [%d]: \n",i,j);
scanf("%d",&a[i][j]);
 }
}
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("enter value of 2nd [%d] [%d]: \n",i,j);
scanf("%d",&b[i][j]);
 }
}
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
c[i][j]=a[i][j]+b[i][j];
 }
}
printf("addition of two matrices is:\n");
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("%d\t",c[i][j]);
}
printf("\n");
}
printf("\n");
return 0;
}
```
## Output of Program
```C
enter value of 1st [0] [0]: 1
enter value of 1st [0] [1]: 2
enter value of 1st [1] [0]: 3
enter value of 1st [1] [1]: 4
enter value of 1st [2] [0]: 5
enter value of 1st [2] [1]: 6

enter value of 2nd [0] [0]: 7
enter value of 2nd [0] [1]: 8
enter value of 2nd [1] [0]: 9
enter value of 2nd [1] [1]: 10
enter value of 2nd [2] [0]: 11
enter value of 2nd [2] [1]: 12

addition of two matrices is:                                                                                                  
8       10                                                                                                                      
12      14                                                                                                                      
16      18  
```
## 21. Program to subtraction of matrices.
```C
#include<stdio.h>
int main()
{
int a[5][4],b[4][5],c[5][5],i,j;
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("enter value of 1st [%d] [%d]: \n",i,j);
scanf("%d",&a[i][j]);
 }
}
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("enter value of 2nd [%d] [%d]: \n",i,j);
scanf("%d",&b[i][j]);
 }
}
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
c[i][j]=a[i][j]-b[i][j];
 }
}
printf("subtraction of two matrices is:\n");
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("%d\t",c[i][j]);
}
printf("\n");
}
printf("\n");
return 0;
}
```
## Output of Program
```C
enter value of 1st [0] [0]: 1
enter value of 1st [0] [1]: 2
enter value of 1st [1] [0]: 3
enter value of 1st [1] [1]: 4
enter value of 1st [2] [0]: 5
enter value of 1st [2] [1]: 6

enter value of 2nd [0] [0]: 7
enter value of 2nd [0] [1]: 8
enter value of 2nd [1] [0]: 9
enter value of 2nd [1] [1]: 10
enter value of 2nd [2] [0]: 11
enter value of 2nd [2] [1]: 12

addition of two matrices is:                                                                                                  
6       6                                                                                                                      
6       6                                                                                                                      
6       6  
```

















