 
<center><img src="https://i.imgur.com/EZtECRw.png"></center>

---

<h3><b>Guru Nanak Dev Engineering College
    ESC-18104/18105 Programming for Problem Solving</b>
  
  
     
    Name-Himani Sharma
    Branch-InformationTechnology
    Section - A2 
    University Roll Number - 1905340
    Submitted to - Prof.Ranjodh Kaur
    # pps assignment

## 1:Write a program to find sum and average of five numbers

``` 
//to find sum and average
#include<stdio.h>
int main()
{                     
 inta,b,c,d,e,sum,avg;
 printf("Enter the five numbers:");
 scanf("%d%d%d%d%d",&a&b&c&d&e);
 sum=a+b+c+d+e;
 printf("The sum is:%d\n",sum);
 avg=sum/5;
 printf("The average is:%d\n",avg);
}
```
**OUTPUT:**
``` 
 Enter the five numbers:1 2 3 4 5 
 The sum is:15
 The average is:3
```
## 2:Write a program to calculate experience of employees

```
  // To calculate experience
#include<stdio.h>
  int main()
  {
     int n,yr,sum=0;
  printf("\n Enter the number of employees");
  scanf("%d",&n);
  for(int i=1;i<=n;i++)
  {
  printf("\nEnter the number of years of experience of %d employee:\n",i);
  scanf("%d",&yr);
  sum=sum+yr;
  }
  printf("Total experience is: %d\n",sum);
  return 0;
  }
  
```
**OUTPUT:**
```
Enter number of employees2
Enter the number of years of experience of 1 employee:
6
Enter the number of years of experience of 2 employee:
3
Total experience is:9

 ```

## 3:Write a program to reverse a number i.e 1234 output will be 4321
```
//to reverse a number
#include<stdio.h>
int main()
{                                                                                    
 int rem,n;
 printf("Enter the number:");
 scanf("%d",&n);
 while(n>0)
 {
 rem=n%10
 printf("%d",rem);
 n=n/10;
 }
 return 0;
 }
```
**OUTPUT**:
```
Enter the number:1234
4321
```
## 4:Write a program to check whether the number is positive or negative
```
//to check number is positive or negative
#include<stdio.h>
  int main()
 {                                 
     int a;
                                                               
   printf("Enter a number:");
   scanf("%d",&a);
    if(a>0)
   printf("Number is positive");
   else
   printf("Number is negative");
  }
``` 
**OUTPUT**:
```
Enter a number:4

  Number is positive
```
  ## 5:Write a program  to find whether the given number is even or odd
  ```
  //to check even or odd 
 #include<stdio.h>
int main()
 {                                
    int a;   
   printf("Enter a number:");
   scanf("%d",&a);
 if(a%2==0)
  printf("The  number is even\n");
 else
   printf("The number is odd\n");
 }
```
**OUTPUT**:
```
Enter a number:4
The  number is even
```
***OR***
```
Enter a number:7
The number is odd
```
## 6:Write a program to fill your information
```
// to fill your information
#include<stdio.h>
void info();
int main()
{                                   
 info();
 }
 void info()
 {
 char a[20];
 int roll ,age;
 long int ph;
 printf("Enter your information:\n");
 printf("Name =");
 scanf("%s",&a);
 printf(\n Roll no. =");
 scanf("%d",&roll);
 printf("\nPhone no.=");
 scanf("%d",&ph);
 
 printf(\n My name is %s. My roll no is %d. My phone number is %ld .My age is %d.",a,roll,ph,age);
 }
```
**OUTPUT**:
```Enter your information:
Name= simar

Roll no=445

Age=25

Phone no.=9922113355

My name is simar. My roll no is 445.My phone number is 9922113355.My age is 25
```
## 7:Write a program to find area,perimeter,volume of square
```
   
 //Area,premiter,volume of square
  #include<stdio.h>
void square();
int main()
{     
 square();
 return 0;
}                                    
void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);

 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}
```
**OUTPUT**:
```
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64
```
## 8:Write a program to show puts value upto n number using loop
```
// to show punishment using loop
 #include<stdio.h>
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&a);
  for(i=1;i<=a;i++)
puts("DO GOOD HAVE GOOD");
return 0;
}
```
**OUTPUT**:
```
Enter the number upto punishment is shown:10
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
DO GOOD HAVE GOOD
```
## 9:Write a program to find area,diameter,circumference of circle 
```
//To find area diameter and circumference of circle
   #include<stdio.h>
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
```
**OUTPUT**:
```
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
```
## 10:Write a program which takes two intergers operands and one operator from user,perform the operation then print the result(+,-,*,/,%)
```
//use of operators using switch case
#include<stdio.h>
int main()
{
 int a,b,c;
 char op;
 printf("Enter two values:\n");
 scanf("%d%d",&a,&b);
 printf("\nEnter the operator\n:");
 scanf(" %c",&op);
 switch(op)
 {
 case'+':printf("%d",a+b);
 break;
 case'-':printf("%d",a-b);
 break;
 case'*':printf("%d",a*b);
 break;
 case'/':printf("%d",a/b);
 break;
 case'%':c=a%b;
         printf("%d",c);
         break;
  default:printf("Error");
 }
 ```
 **OUTPUT**:
 ```
 Enter two values
 3 5
 Enter the operator
 *
 15

```
 
 ##  11:Write a program to display the table of a number from user choice
 
 ```
  // To represent a table of user input  number
 #include<stdio.h>
 int main()
 {
    int i,a;
  printf("Table of:");
  scanf("%d",&a);
   for(i=0;i<=10;i++)
  {
  printf("%d x %d = %d\n",a,i,a*i);
  }

return 0;
}
```
**OUTPUT**:
```Table of:15
15 x 0 = 0
15 x 1 = 15
15 x 2 = 30
15 x 3 = 45
15 x 4 = 60
15 x 5 = 75
15 x 6 = 90
15 x 7 = 105
15 x 8 = 120
15 x 9 = 135
15 x 10 = 150
```
## 12:Write a program to convert temperature from Fahrehnite to Centigrade
```
//to convert fahrehnite to celcius
#include<stdio.h>
int main()
{
float fah,c;
printf("Enter temp in fahrehnite :");
scanf("%f",&fah);
c=((f-32)*5)/9;
printf("The centigrade value is:%f\n",c);

return 0;
}
```
**OUTPUT**:
```
Enter temp in fahrehnite :450
The centigrade value is:232.222229
```
## 13: Write a program to display the table between the range
```
//To show a range of table upto user input
#include<stdio.h>
int main()
{
 int a,b,i,x;
 printf("Enter the starting number and the ending number:");
 scanf("%d%d",&a,&b);
 {
 for(i=a;i<=b;i++)
 {
 for(x=1:x<=10;x++)
 {
 printf("\n %d X %d = %d",i,x,i*x);
 }
 }
 return 0;
 }
 
```
**OUTPUT**:
```


 Enter the starting number and ending number:2 3
 2 X 1 = 2
 2 X 2 = 4
 2 X 3 = 6
 2 X 4 = 8
 2 X 5 = 10
 2 X 6 = 12
 2 X 7 = 14 
 2 X 8 = 16
 2 X 9 = 18
 2 X 10 = 20
 3 X 1 = 3 
 3 X 2 = 6 
 3 X 3 = 9
 3 X 4 = 12
 3 X 5 = 15
 3 X 6 = 18
 3 X 7 = 21
 3 X 8 = 24
 3 X 9 = 27
 3 X 10 = 30
 
```
## 14: Write a program to display the table of even number 
```
//To show only even table
#include<stdio.h>
int main()
{
int a,b,i,x;
printf("Enter the starting and ending number:");
scanf("%d%d",&a,&b);
for(i=a;i<=b;i++)
{
if(i%2==0)
{
for(x=1;x<=10;x++)
{
printf("%d X %d = %d\n",i,x,i*x);
}
}
}

return 0;}
```
**OUTPUT**:
```
Enter the starting and ending number:2 5
2 X 1 = 2
2 X 2 = 4
2 X 3 = 6
2 X 4 = 8
2 X 5 = 10
2 X 6 = 12 
2 X 7 = 14
2 X 8 = 16
2 X 9 = 18
2 X 10 = 20
4 X 1 = 4
4 X 2 = 8
4 X 3 = 12
4 X 4 = 16
4 X 5 = 20
4 X 6 = 24
4 X 7 = 28
4 X 8 = 32
4 X 9 = 36
4 X 10 = 40
```
## 15: Write a program to find the factorial using recursion
```
//To find factorial using recursion
#include<stdio.h>
int main()
{
int n,i;
long int mult(int n);
printf("Enter the number");
scanf("%d",&n);
printf("\nfactorial of %d is %d\n",n,mult(n));
}
long int mult(int n )
{
if(n>=1)
return n*mult(n-1);
else
return 1;
}

```

**OUTPUT**:
```
Enter the number5

factorial of 5 is 120
```
## 16:Write a program to display a face pattern
```
#include<stdio.h>
int main() 
{
puts("___________________");
puts("|   XXXXXXXXXXX   |");
puts("|   ( ^     ^ )   |");
puts("|   ( 0     0 )   |");
puts("|    \\   |   /    |");
puts("|     \\     /     |");
puts("|      \\ = /      |");
puts("|       \\_/       |");
puts("|        |        |");
puts("|________|________|");
}
```
**OUTPUT**
```
___________________
|   XXXXXXXXXXX   |
|   ( ^     ^ )   |
|   ( 0     0 )   |
|    \   |   /    |
|     \     /     |
|      \ = /      |
|       \_/       |
|        |        |
|________|________|
```
## 17:Write a program to check the number is prime or not 
```
 #include<stdio.h>
 int main()
 {
 int a,i,p=0;
  printf("Enter the number:");
  scanf("%d",&a);
  for(i=1;i<=a;i++)
  {
  if(a%i==0)
  {
  p++;
  }
  }
  if(p==2)
  {
  printf("%d is prime number",a);
  }
  else
  {
  printf("%d is not prime",a);
  }
  return 0;
  } 
```
**OUTPUT**:
```
Enter the number:7
7 is prime number

```

## 18:Write a program to show stars pattern
```
 // TO show stars using loop 
#include<stdio.h>
int main()
{ int i,j,k;
 printf("Enter the no. to show pattern:");
 scanf("%d",&k);
 
  for(i=k;i>=1;i--)
 {
  for(j=i;j>=1;j--)
 {
  printf("* ");
 }
 printf("\n");
 }
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter the no. to show pattern:8
* * * * * * * * 
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
*
```
 
 ## 19:Write a program to find factorial of a number
 ```
 //To show factorial of user input
#include<stdio.h>
int main()
{
 int a,result=1;
 printf("Enter the number:");
 scanf("%d",&a);
 for(int i=a;i>=1;i--)
{
result=result*i;
}
printf("Result of factorial is %d\n",result);

}
```
**OUTPUT**:
```
Enter the number:5
Result of factorial is 120
```
 ## 20: Write a program to check the numbers are prime or not between the given range
 ```
#include<stdio.h>
int main()
{
 int a,b,i,n,p=0;
 printf("Enter the starting number and ending number");
 scanf("%d%d",&a,&b);
 for(i=a;i<=b;i++)
 {
 p=1;
 for(n=2;n<i;n++)
 {
 p=0;
 break;
 }
 }
 if(p==1)
 {
 printf("%d is a prime number\n",i);
 }
 }
 return 0;
 }

```
**OUTPUT**:
```
Enter the starting number and the ending number:2 11
2 is a prime number
3 is a prime number
5 is a prime number
7 is a prime number
11 is a prime number
```

## 21:Write a program to show matrix addition
 ```
#include<stdio.h>
int main()
{
int row,col,row1,col1,i,j ;
int arr[10][10],arr1[10][10],sum[10][10];
printf("Enter the rows of 1 matrix");
scanf("%d",&row);
printf("Enter the columns of 1 matrix");
scanf("%d",&col);
printf("Enter the elements of 1 matrix");
for(i=0;i<row;i++)
{
  for(j=0;j<col;j++)
   {
    scanf("%d",&arr[i][j]);
   } 
} 
printf("Enter the elements of 2 matrix");
for(i=0;i<row;i++)
{
  for(j=0;j<col;j++)
   {
    scanf("%d",&arr1[i][j]);
   } 
} 
for(i=0;i<row;i++)
{
  for(j=0;j<col;j++)
   {
    sum[i][j]=arr[i][j]+arr1[i][j]);
   } 
} 
for(i=0;i<row;i++)
{
  for(j=0;j<col;j++)
   {
    printf("%d",sum[i][j]);
    if(j==col-1)
       printf("\n\n");
   } 
} 
return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter the rows of 1 matrix:2
Enter the columns of 1 matrix:2
Enter the elements of 1 matrix:3 1 4 2
Enter the elements of 2 matrix:5 3 5 1
 8  4
 
 9  3
  
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk0Njc2OTc1MiwxNjU2OTAxNTI4LC03Mj
g2NzQ5NjUsLTc4ODExMDUzMywxNDAxMzg0NjY0LDE2MTgwMjUy
ODAsNDg3NDA0MzAxLDIwOTY4MjEwMzQsLTIxMjg5MTIwOTIsLT
I2MDQ0OTE2NywtMjc3NjA5ODExLDExMzUyMDA5NjEsLTY0MzA4
ODI1NiwzOTMzOTkyMzgsNzc0OTQ3NzEzLC0xOTM0OTcwMDY2LC
0xNTMzMjE1ODU2LDQwNzQ1NzQyMiwtMjMyMDc4MTA4LDEzMTEw
NDM5MzddfQ==
-->

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MzA1MDQxMjksMTk4NTg2OTYzMSwxOT
UwNjM2OTVdfQ==
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTU5Mjc0MTQ2LC0yMDg4NzQ2NjEyXX0=
-->
