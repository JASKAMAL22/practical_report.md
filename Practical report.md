# **PROGRAMMING FOR PROGRAM SOLVING ESC-18105**
## NAME-*JASKAMAL SINGH*
## ROLL NO-*1915037*
## BRANCH-*COMPUTER SCIENCE*
## SECTION-**CS(A2)**

# 1.Program to print Hello World
```C
#include<stdio.h>
int main()
{
 puts("Hello World");
 return 0;
}
```
**Output of the program**
```C
Hello World
```
# 2. Program to find Sum
```C
#include<stdio.h>
int main()
{  
     float x,y,z;

     printf("Enter The First Number: ");
     scanf("%f", &x);
     printf("\nEnter The Second Number: ");
     scanf("%f", &y);
     z = x+y;
     printf("\nAnswer is: = %.3f", z);
     return 0;
}
```
**Output of the program**
```C
Enter The First Number: 45.26

Enter The Second Number: 78.2648

Answer is: = 123.525
```
# 3. Program to print a Table
```C
#include<stdio.h>
int main()
{
     float x;
     int n;

     printf("\nEnter The Table: ");
     scanf("%f",&x);

     printf("\nEnter No. Times: ");
     scanf("%d",&n);

     for(int y=1; y<=n; y++)
     {
     printf("\n%.1f x %d = %.2f",x,y,x*y);
     }
     return 0;
}
```
**Output of the program**
```C
73.0 x 1 = 73.00
73.0 x 2 = 146.00
73.0 x 3 = 219.00
73.0 x 4 = 292.00
73.0 x 5 = 365.00
73.0 x 6 = 438.00
73.0 x 7 = 511.00
```
# 4. Program to find Area, Perimeter of a Rectangle
```C
#include<stdio.h>
int main()
{
     float l,b,A,P;

     printf("Enter length\n: ");
     scanf("%f",&l);

     printf("Enter Bredth\n: ");
     scanf("%f",&b);

     A = l*b;
     P = 2*(l+b);

     printf("Area: = %.3f\n",A);
     printf("Perimeter: = %.3f\n",P);

     return 0;
}
```
**Output of the program**
```C
Enter length

Enter Breadth

Area: =

Perimeter: =

```
