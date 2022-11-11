# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
printf("Hello,world!");
return 0;
}
```
----------------------------------------


# Question 2

### **Question:**

> ***Write a program to compute the perimeter and area of a rectangle.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h> 
int main() {
int height = 8;
int width = 5;
int perimeter = 2*(height + width);
printf("Perimeter of the rectangle is: %d cm\n", perimeter);
int area = height * width;
printf("Area of the rectangle is: %d square cm\n", area);
return 0;
}
```
----------------------------------------


# Question 3

### **Question:**

> ***Write a program to compute the perimeter and area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h> 
int main() {
int radius = 4;
float perimeter = 2*3.14*radius;
printf("Perimeter of the circle is: %f cm\n", perimeter);
float area = 3.14*radius*radius;
printf("Area of the circle is: %f square cm\n", area);
return 0;
}
```
----------------------------------------


# Question 4

### **Question:**

> ***Write a program that accepts two numbers from the user and calculate the sum of the two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b, sum;
printf("\nEnter the first number: "); 
scanf("%d", &a);
printf("\nEnter the second number: ");
scanf("%d", &b);
sum = a + b;
printf("\nSum of the above two numbers is: %d", sum);
return 0;
}
```
----------------------------------------


# Question 5

### **Question:**

> ***Write a program that accepts two numbers from the user and calculate the product of the two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b, mult;
printf("\nEnter the first number: "); 
scanf("%d", &a);
printf("\nEnter the second number: ");
scanf("%d", &b);
mult = a * b;
printf("\nProduct of the above two numbers is: %d", mult);
return 0;
}
```
----------------------------------------


# Question 6

### **Question:**

> ***Write a program that accepts three numbers and find the largest of three.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, y, z;
printf("\nEnter the first number: "); 
scanf("%d", &x);
printf("\nEnter the second number: ");
scanf("%d", &y);
printf("\nEnter the third number: ");
scanf("%d", &z);

// if x is greater than both y and z, x is the largest
if (x >= y && x >= z)
printf("\n%d is the largest number.", x);

// if y is greater than both x and z, y is the largest
if (y >= x && y >= z)
printf("\n%d is the largest number.", y);

// if z is greater than both x and y, z is the largest
if (z >= x && z >= y)
printf("\n%d is the largest number.", z);
    
return 0;
}
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program that reads three floating values and check if it is possible to make a triangle with them. Also calculate the perimeter of the triangle if the entered values are valid.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
float  x, y, z;
printf("\nEnter the first number: "); 
scanf("%f", &x);
printf("\nEnter the second number: ");
scanf("%f", &y);
printf("\nEnter the third number: ");
scanf("%f", &z);

if(x < (y+z) && y < (x+z) && z < (y+x)) {  
printf("\nPerimeter of the triangle is: %f\n", x+y+z);	 
}
else {
printf("\nIt is impossible to form a triangle.");
}
return 0;
}
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program that reads an integer between 1 and 7 and print the day of the week in English.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int day;
printf("\nEnter a number between 1 to 7 to get the day name: ");
scanf("%d", &day);
switch(day) {
case 1 : printf("Monday\n"); break;
case 2 : printf("Tuesday\n"); break;
case 3 : printf("Wednesday\n"); break;
case 4 : printf("Thursday\n"); break;
case 5 : printf("Friday\n"); break;
case 6 : printf("Saturday\n"); break;
case 7 : printf("Sunday\n"); break;
default : printf("Enter a number between 1 to 7.");
}
return 0;
}
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b, sum;
a=1;
b=2;
sum = a + b;
printf("The sum of a and b = %d", sum);
return 0;
}
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<math.h>
int main() {
int a, b;
a=2;
b = pow((a), 2);
printf("The square of a = %d", b);
return 0;
}
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b;
a = 2;
b = 3;
if(a>b) {
printf("a is greater than b");
}
else {
printf("b is greater than a");
}
return 0;
}
```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int i, avg, sum = 0;
int num [5] = {16, 18, 20, 25, 36};
for(i=0; i<5; i++) {
sum = sum + num [i];
avg = sum/5;
}
printf("Sum of the Elements in the array is: %d\n", sum);
printf("Average of the elements in the array is: %d\n", avg);
return 0;
}
```
----------------------------------------

# Question 13

### **Question:**

> ***Write a program that prints all even numbers between 1 and 25.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
printf("Even numbers between 1 to 25:\n");
for(int i = 1; i <= 25; i++) {
if(i%2 == 0) {
printf("%d ", i);
}
}
return 0;
}
```
----------------------------------------


# Question 14

### **Question:**

> ***Write a program that prints all odd numbers between 1 and 50.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
printf("Odd numbers between 1 to 50:\n");
for(int i = 1; i <= 50; i++) {
if(i%2 != 0) {
printf("%d ", i);
}
}
return 0;
}
```
----------------------------------------


# Question 15

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
for(int i=1; i<=10; i++) {
printf("Number = %d its square = %d its cube = %d\n", i , i*i, i*i*i);
}
return 0;
} 
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
char M;
printf("Enter any character: ");
scanf("%c", &M);
printf("ch = %c", M);
return 0;
} 
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to print the multiplication table of a number entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int n, i;
printf("Enter any number: ");
scanf("%d", &n);
for(i=1; i<=5; i++) {
printf("%d * %d = %d\n", n, i, n*i);
}
return 0;
}
```
----------------------------------------


# Question 18

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int i, product = 1;
for(i=1; i<=10; i++) {
product = product * i;
}
printf("The product of the first 10 digits is: %d", product);
return 0;
}
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to print whether the given number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a;
a = -35;
if(a>0) {
printf("Number is positive");
}
else {
printf("Number is negative");
}
return 0;
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to check the equivalence of two numbers entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, y;
printf("\nEnter the first number: ");
scanf ("%d", &x);
printf("\nEnter the second number: ");
scanf ("%d", &y);
if(x-y==0) {
printf("\nThe two numbers are equivalent");
}
else {
printf("\nThe two numbers are not equivalent");
}
return 0;
}
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to print the remainder of two numbers entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b, c;
printf("\nEnter the first number: ");
scanf ("%d", &a);
printf("\nEnter the second number: ");
scanf ("%d", &b);
c = a%b;
printf("\n The remainder of %d and %d is: %d", a, b, c);
return 0;
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
char i;
for(i='A'; i<='Z'; i++) {
printf("%c\n", i);
}
return 0;
}
```
----------------------------------------


# Question 23

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<string.h>
int main() {
char str[1000];
printf("Enter a string to calculate its length: ");
scanf("%s", str);
printf("The length of the entered string is: %ld", strlen(str));
return 0;
}
```
----------------------------------------


# Question 24

### **Question:**

> ***Write a program to check whether the given character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include <ctype.h>
int main() {
char ch = 'a';
if(islower(ch)) {
printf("The given character is a lower case letter");
}
else {
printf("The given character is a upper case letter");
}
return 0;
}
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to check whether the given character is a upper case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include <ctype.h>
int main() {
char ch = 'A';
if(isupper(ch)) {
printf("The given character is a upper case letter");
} 
else {
printf("The given character is a lower case letter");
}
return 0;
}

```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to convert the lower case letter to upper case letter.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include <ctype.h>
int main() {
char ch = 'a';
char b = toupper(ch);
printf("Lower case letter '%c' is converted to Upper case letter '%c'", ch, b);
return 0;
}
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program that takes a distance in centimeters and outputs the corresponding value in inches.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h> 
#define x 2.54
int main() {
double inch, cm;
printf("Enter the distance in cm: ");
scanf("%lf", &cm);
inch = cm / x;
printf("\nDistance of %0.2lf cms is equal to %0.2lf inches", cm, inch);
return 0;
}
```
----------------------------------------


# Question 28

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
char name [8] = {'E' , 'I', 'N', 'S', 'T', 'E', 'I', 'N'};
for(int i=0; i<8; i++) {
printf("\nEinstein [%d] = %c", i, name[i]);
}
return 0;
}
```
----------------------------------------


# Question 29

### **Question:**

> ***Write a program to print "Hello World" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
for(int i=1; i<=10; i++) {
printf("Hello World \n");
}
return 0;
}
```
----------------------------------------


# Question 30

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int i =1;
do {
printf("%d\n", i++);
} while(i<=5);
return 0;
}
```
----------------------------------------



# Question 31

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<ctype.h>
int main() {
int a =2;
if(isalpha(a)) {
printf("The character a is an alphabet");
}
else {
printf("The character a is not an alphabet");
}
return 0;
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to check whether a entered number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a;
printf("Enter any number: ");
scanf ("%d", &a);
if(a%2 == 0) {
printf("The entered number is even");
}
else {
printf("The entered number is odd");
}
return 0;
}
```
----------------------------------------


# Question 33

### **Question:**

> ***Write a program to print the ASCII value of the given character.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
char ch ='A';
printf("The ASCII value of %c is: %d", ch, ch);
return 0;
}
```
----------------------------------------


# Question 34

### **Question:**

> ***Write a program that will print all numbers between 1 to 50 which divided by a specified number and the remainder will be 2.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, i;
printf("Enter a number: ");
scanf("%d", &x);
for(i=1; i<=50; i++) {
   if((i%x)==2) {
    printf("%d\n", i);
	 }
}
return 0;
}
```
----------------------------------------


# Question 35

### **Question:**

> ***Write a program to determine whether two numbers in a pair are in ascending or descending order.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b;
printf("\nEnter a pair of numbers (for example 22,12 | 12,22): ");
printf("\nEnter the first number: ");
scanf("%d", &a);
printf("\nEnter the second number: ");
scanf("%d", &b);
if (a>b) {
printf("\nThe two numbers in a pair are in descending order.");
}
else {
printf("\nThe two numbers in a pair are in ascending order.");
}
return 0;
} 
```
----------------------------------------



# Question 36

### **Question:**

> ***Write a program that reads two numbers and divides one by the other. Specify "Division not possible" if that is not possible.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b;
float c;
printf("\nEnter the first number: ");
scanf("%d", &a);
printf("\nEnter the second number: ");
scanf("%d", &b);
if(b != 0) {
   	c = (float)a/(float)b;
	printf("\n%d/%d = %.1f", a, b, c);
} 
else {
	 printf("\nDivision not possible.\n");
}
return 0;
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program that will print all numbers between 1 to 50 which divided by a specified number and the remainder is equal to 2 or 3.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, i;
printf("Enter a number: ");
scanf("%d", &x);
for(i=1; i<=50; i++) {
   if((i%x)==2 || (i%x) == 3) {
    printf("%d\n", i);
	 }
}
return 0;
}
```
----------------------------------------



# Question 38

### **Question:**

> ***Write a program that adds up all numbers between 1 and 100 that are not divisible by 12.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x =12, i, sum = 0;
for(i=1; i<=100; i++) {
   if((i%x)!= 0) {
    sum += i;
	 }
}
printf("\nSum: %d\n", sum);
return 0;
}
```
----------------------------------------


# Question 39

### **Question:**

> ***Write a program to calculate the value of x where x = 1 + 1/2 + 1/3 + … + 1/50.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
float x = 0;
for(int i=1; i<=50; i++) {
   x += (float)1/i;
}
printf("Value of x: %.2f\n", x);
return 0;
}
```
----------------------------------------


# Question 40

### **Question:**

> ***Write a program that reads a number and find all its divisor.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, i;
printf("\nEnter a number: ");
scanf("%d", &x);
printf("All the divisor of %d are: ", x);
for(i = 1; i <= x; i++) {
    if((x%i) == 0) {
	printf("\n%d", i);
    }
}	
return 0;
}
```
----------------------------------------


# Question 41

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b, c, d, e, f;
a = 10;
b=12;
c=a+1;
d=b+1;
e=a-1;
f=b-1;
printf("The incremented value of a =%d", c);
printf("The incremented value of b =%d", d);
printf("The decremented value of a =%d", e);
printf("The decremented value of b =%d", f);
return 0;
}
```
----------------------------------------


# Question 42

### **Question:**

> ***Write a program to find square of a entered number using functions.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int square();
int main() {
int answer;
answer = square();
printf("The square of the entered number is: %d", answer);
return(0);
}
int square() {
int x;
printf("Enter any number: ");
scanf("%d", &x);
return x*x;
}
```
----------------------------------------


# Question 43

### **Question:**

> ***Write a program that accepts principal amount, rate of interest, time and compute the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int p,r,t,SI;
printf("\nEnter the principal amount: ");
scanf("%d",&p);
printf("\nEnter the rate of interest: ");
scanf("%d",&r);
printf("\nEnter the time: ");
scanf("%d",&t);
SI=(p*r*t)/100;
printf("\nSimple interest is: %d", SI);
return 0;
}
```
----------------------------------------


# Question 44

### **Question:**

> ***Write a program that swaps two numbers without using third variable.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int a, b;
printf("\nEnter the value for a: ");
scanf("%d",&a);
printf("\nEnter the value for b: ");
scanf("%d",&b);
printf("\nBefore swapping: %d %d",a,b);
a=a+b;
b=a-b;
a=a-b;
printf("\nAfter swapping: %d %d",a,b);
return 0;
}
```
----------------------------------------

# Question 45

### **Question:**

> ***Write a program to find the greatest of two entered numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, y, *p, *q;
printf("Enter the value for x: ");
scanf("%d", &x);
printf("Enter the value for y: ");
scanf("%d", &y);
p = &x;
q = &y;
if(*p>*q) {
printf("x is greater than y");
}
if(*q>*p) {
printf("y is greater than x");
}
return 0;
}
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
char i;
char body [4] = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
printf("\n body[%c] = %c", body[i] , body[i]);
return 0;
}
```
----------------------------------------

# Question 47

### **Question:**

> ***Write a program to calculate the discounted price and the total price after discount</br>
Given:</br>
If purchase value is greater than 1000, 10% discount</br>
If purchase value is greater than 5000, 20% discount</br>
If purchase value is greater than 10000, 30% discount.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
double PV;
printf("Enter purchased value: ");
scanf("%lf", &PV);
if(PV>1000) {
printf("\n Discount = %lf", PV* 0.1);
printf("\n Total = %lf", PV - PV* 0.1);
}
else if(PV>5000) {
printf("\n Discount = %lf", PV* 0.2);
printf("\n Total = %lf", PV - PV* 0.2);
}
else {
printf("\n Discount = %lf", PV* 0.3);
printf("\n Total = %lf", PV - PV* 0.3);
}
return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int i = 1;
while (i<=10) {
printf("%d\n", i++);
}
return 0;
}
```
----------------------------------------


# Question 49

### **Question:**

> ***Write a program to shift inputted data by two bits to the left.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x;
printf("Enter the integer from keyboard: ");
scanf("%d",&x);
printf("\nEntered value: %d ",x);
printf("\nThe left shifted data is: %d ", x<<=2);
return 0;
}
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to shift inputted data by two bits to the Right.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x;
printf("Enter the integer from keyboard: ");
scanf("%d",&x);
printf("\nEntered value: %d ",x);
printf("\nThe right shifted data is: %d ", x>>=2);
return 0;
}
```
----------------------------------------



# Question 51

### **Question:**

> ***Write a program to calculate the exact difference between x and 21. Return three times the absolute difference if x is greater than 21.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdlib.h>
#include<stdio.h>
int main() {
int x;
printf("Enter the value for x: ");
scanf("%d",&x);
if(x<=21){
    printf("%d",abs(x-21));
 }
else if(x>=21) {
    printf("%d",abs(x-21)*3);
}
return 0;
}
```
----------------------------------------


# Question 52

### **Question:**

> ***Write a program that reads in two numbers and determine whether the first number is a multiple of the second number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, y;
printf("\nEnter the first number: ");
scanf("%d", &x);
printf("\nEnter the second number: ");
scanf("%d", &y);
if(x % y == 0) {
printf("\n%d is a multiple of %d.\n", x, y);
}
else {
printf("\n%d is not a multiple of %d.\n", x, y);
}
return 0;
}
```
----------------------------------------


# Question 53

### **Question:**

> ***Write a program to print the output:</br>
Name of the book = B</br>
Price of the book = 135.00</br>
Number of pages = 300</br>
Edition of the book = 8</br>
using structures.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
struct book {
char name;
float price;
int pages;
int edition;
};
struct book b1;
b1.name = 'B';
b1.price = 135.00;
b1.pages = 300;
b1.edition = 8;
printf("\n Name of the book = %c", b1.name);
printf("\n Price of the book = %f", b1.price);
printf("\n Number of pages = %d", b1.pages);
printf("\n Edition of the book = %d", b1.edition);
return 0;
}
```
----------------------------------------


# Question 54

### **Question:**

> ***Write a program to convert Celsius into Fahrenheit.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>  
int main() {   
float fahrenheit, celsius;  
celsius = 36;  
fahrenheit = ((celsius*9)/5)+32;  
printf("\nTemperature in fahrenheit is:  %f",fahrenheit);  
return (0);  
}  
```
----------------------------------------


# Question 55

### **Question:**

> ***Write a program that will examine two inputted integers and return true if either of them is 50 or if their sum is 50.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int x, y; 
printf("\nEnter the value for x: ");
scanf("%d", &x);
printf("\nEnter the value for y: ");
scanf("%d", &y);
if(x == 50 || y == 50 || (x + y == 50)) {
    printf("\nTrue");
} 
else {
    printf("\nFalse");
}    
return 0;
}
```
----------------------------------------




















# Question 9

### **Question:**

> ***Write a program to print the address of x and the value assigned to x.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
int x, *p;
x = 1;
p = &x;
printf("The address of the variable x =%d", p);
printf("The value of the variable x =%d", *p);
return 0;
} 
```
----------------------------------------









# Question 21

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b, c;
printf("Enter any number:");
scanf("%d", &a);
printf("Enter any number:");
scanf("%d", &b);
printf("Enter any number:");
scanf("%d", &c);
if(a>b&&a>c)
{
printf("%d is greater than %d and %d", a, b, c);
}
else if (b>a&&b>c)
{
printf("%d is greater than %d and %d", b, a, c);
}
else
{
printf("%d is greater than %d and %d", c, b, a);
}
return 0;
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the factorial of the entered number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i, n, fact=1 ;
printf("Enter any number:");
scanf("%d", &n);
for(i=1; i<=n; i++)
fact = fact *i;
printf("\n Entered number is: %d", n);
printf("\n The factorial of the entered number %d is: %d", n, fact);
return 0;
}
```
----------------------------------------














# Question 34

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```C language
#include<stdio.h>
#include<stdlib.h>
int main () {
printf("linux\n");
exit (0);
printf("php\n");
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
linux
```
----------------------------------------





# Question 38

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```C language
#include <stdio.h>
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
continue;
}
printf("%d\n ", i);
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
4
5
```
----------------------------------------

# Question 39

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
   int num [] = {11, 22, 33, 44, 55, 66};
    int n;

    /* Calculating the size of the array with this formula.
     * n = sizeof(array_name) / sizeof(array_name[0])
     * This is a universal formula to find number of elements in
     * an array, which means it will work for arrays of all data
     * types such as int, char, float etc.
     */
    n = sizeof(num) / sizeof(num [0]);
    printf("Size of the array is: %d\n", n);
    return 0;
}
```
----------------------------------------

# Question 40

### **Question:**

> ***What would be the output of the following programs:***

----------------------------------------

```C language
#include <stdio.h>
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
break;
}
printf("%d\n", i);
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
```
----------------------------------------

```C language
#include <stdio.h>
int main()
{
int i;
for(i=1;i<=5;i++)
{
if(i==3)
{
goto HAI;
}
printf("\n %d ",i);
}
HAI : printf("\n Linux");
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
Linux
```
----------------------------------------

```C language
#include<stdio.h>
int main()
{
int i = 54;
int y = i<<1;
printf("The value of y = %d", y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
The value of y = 108
```
----------------------------------------

```C language
#include<stdio.h>
int main()
{
int i = 54;
int y = i>>1;
printf("The value of y = %d", y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
The value of y = 27
```
----------------------------------------

```C language
#include<stdio.h>
#include <stdlib.h>
int main()
{
int a, b;
a= - 2;
b= abs(a);
printf("Absolute value = %d", b);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
Absolute value = 2
 ```
----------------------------------------

```C language
#include <stdio.h>
int main()
{
for( ; ; ) 
{
printf("This loop will run forever.\n");
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever. ......... 
```
----------------------------------------


```C language
#include<stdio.h>
int main()
{
printf("Hello,world!");
return 0;
printf("Hello,world!");
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
Hello,world! 
```
----------------------------------------

# Question 41

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int age;
printf("Enter age:");
scanf("%d", &age);
if(age>=60)
{
printf("senior citizen");
}
else
{
printf("not a senior citizen");
}
return 0;
}
```
----------------------------------------

# Question 42

### **Question:**

> ***Write a program to Display Fibonacci Sequence.***

---------------------------------------

<strong>Solution: </strong>

```c

#include <stdio.h>
int main() {
    int i, n, t1 = 0, t2 = 1, nextTerm;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");

    for (i = 1; i <= n; ++i) {
        printf("%d, ", t1);
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }

    return 0;
}
```
----------------------------------------

# Question 43

### **Question:**

> ***Write a program to Find GCD of two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
int main()
{
    int n1, n2, i, gcd;

    printf("Enter two integers: ");
    scanf("%d %d", &n1, &n2);

    for(i=1; i <= n1 && i <= n2; ++i)
    {
        // Checks if i is factor of both integers
        if(n1%i==0 && n2%i==0)
            gcd = i;
    }

    printf("G.C.D of %d and %d is %d", n1, n2, gcd);

    return 0;
}
```
----------------------------------------

# Question 44

### **Question:**

> ***Write a program to Find LCM of two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
int main() {
    int n1, n2, max;
    printf("Enter two positive integers: ");
    scanf("%d %d", &n1, &n2);

    // maximum number between n1 and n2 is stored in min
    max = (n1 > n2) ? n1 : n2;

    while (1) {
        if (max % n1 == 0 && max % n2 == 0) {
            printf("The LCM of %d and %d is %d.", n1, n2, max);
            break;
        }
        ++max;
    }
    return 0;
}
```
----------------------------------------


# Question 45

### **Question:**

> ***Write a program to Reverse a Sentence Using Recursion.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
void reverseSentence();
int main() {
    printf("Enter a sentence: ");
    reverseSentence();
    return 0;
}

void reverseSentence() {
    char c;
    scanf("%c", &c);
    if (c != '\n') {
        reverseSentence();
        printf("%c", c);
    }
}
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to Swap Numbers in Cyclic Order Using Call by Reference.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
void cyclicSwap(int *a, int *b, int *c);
int main() {
    int a, b, c;

    printf("Enter a, b and c respectively: ");
    scanf("%d %d %d", &a, &b, &c);

    printf("Value before swapping:\n");
    printf("a = %d \nb = %d \nc = %d\n", a, b, c);

    cyclicSwap(&a, &b, &c);

    printf("Value after swapping:\n");
    printf("a = %d \nb = %d \nc = %d", a, b, c);

    return 0;
}

void cyclicSwap(int *n1, int *n2, int *n3) {
    int temp;
    // swapping in cyclic order
    temp = *n2;
    *n2 = *n1;
    *n1 = *n3;
    *n3 = temp;
}
```
----------------------------------------

# Question 47

### **Question:**

> ***Write a program to Find Largest Number Using Dynamic Memory Allocation.***

---------------------------------------

<strong>Solution: </strong>

```c

#include <stdio.h>
#include <stdlib.h>
int main() {
    int num;
    float *data;
    printf("Enter the total number of elements: ");
    scanf("%d", &num);

    // Allocating memory for num elements
    data = (float *)calloc(num, sizeof(float));
    if (data == NULL) {
        printf("Error!!! memory not allocated.");
        exit(0);
    }

    // Storing numbers entered by the user.
    for (int i = 0; i < num; ++i) {
        printf("Enter Number %d: ", i + 1);
        scanf("%f", data + i);
    }

    // Finding the largest number
    for (int i = 1; i < num; ++i) {
        if (*data < *(data + i))
            *data = *(data + i);
    }
    printf("Largest number = %.2f", *data);

    return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to Sort Elements in Lexicographical Order.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
#include <string.h>

int main() {
   char str[5][50], temp[50];
   printf("Enter 5 words: ");

   // Getting strings input
   for (int i = 0; i < 5; ++i) {
      fgets(str[i], sizeof(str[i]), stdin);
   }

   // storing strings in the lexicographical order
   for (int i = 0; i < 5; ++i) {
      for (int j = i + 1; j < 5; ++j) {

         // swapping strings if they are not in the lexicographical order
         if (strcmp(str[i], str[j]) > 0) {
            strcpy(temp, str[i]);
            strcpy(str[i], str[j]);
            strcpy(str[j], temp);
         }
      }
   }

   printf("\nIn the lexicographical order: \n");
   for (int i = 0; i < 5; ++i) {
      fputs(str[i], stdout);
   }
   return 0;
}
```
----------------------------------------



# Question 49

### **Question:**

> ***Write a program to Add Two Complex Numbers by Passing Structure to a Function.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
typedef struct complex {
    float real;
    float imag;
} complex;

complex add(complex n1, complex n2);

int main() {
    complex n1, n2, result;

    printf("For 1st complex number \n");
    printf("Enter the real and imaginary parts: ");
    scanf("%f %f", &n1.real, &n1.imag);
    printf("\nFor 2nd complex number \n");
    printf("Enter the real and imaginary parts: ");
    scanf("%f %f", &n2.real, &n2.imag);

    result = add(n1, n2);

    printf("Sum = %.1f + %.1fi", result.real, result.imag);
    return 0;
}

complex add(complex n1, complex n2) {
    complex temp;
    temp.real = n1.real + n2.real;
    temp.imag = n1.imag + n2.imag;
    return (temp);
}
```
----------------------------------------


# Question 50

### **Question:**

> ***Write a program to Write a Sentence to a File.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    char sentence[1000];

    // creating file pointer to work with files
    FILE *fptr;

    // opening file in writing mode
    fptr = fopen("program.txt", "w");

    // exiting program 
    if (fptr == NULL) {
        printf("Error!");
        exit(1);
    }
    printf("Enter a sentence:\n");
    fgets(sentence, sizeof(sentence), stdin);
    fprintf(fptr, "%s", sentence);
    fclose(fptr);
    return 0;
}
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to Read a Line From a File and Display it.***

---------------------------------------

<strong>Solution: </strong>

```c

#include <stdio.h>
#include <stdlib.h> // For exit() function
int main() {
    char c[1000];
    FILE *fptr;
    if ((fptr = fopen("program.txt", "r")) == NULL) {
        printf("Error! opening file");
        // Program exits if file pointer returns NULL.
        exit(1);
    }

    // reads text until newline is encountered
    fscanf(fptr, "%[^\n]", c);
    printf("Data from the file:\n%s", c);
    fclose(fptr);

    return 0;
}
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to Store Data in Structures Dynamically.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
#include <stdlib.h>
struct course {
    int marks;
    char subject[30];
};

int main() {
    struct course *ptr;
    int i, noOfRecords;
    printf("Enter the number of records: ");
    scanf("%d", &noOfRecords);

    // Memory allocation for noOfRecords structures
    ptr = (struct course *)malloc(noOfRecords * sizeof(struct course));
    for (i = 0; i < noOfRecords; ++i) {
        printf("Enter the name of the subject and marks respectively:\n");
        scanf("%s %d", (ptr + i)->subject, &(ptr + i)->marks);
    }

    printf("Displaying Information:\n");
    for (i = 0; i < noOfRecords; ++i)
        printf("%s\t%d\n", (ptr + i)->subject, (ptr + i)->marks);

    return 0;
}

```
----------------------------------------




# Question 53
### **Question:**

> ***Write a program to Check if a Matrix is Invertible.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
 int main(){
 
  int a[3][3], i, j;
 
  long determinant;
  printf("Enter the 9 elements of matrix: ");
  for(i = 0 ;i < 3;i++)
      for(j = 0;j < 3;j++)
           scanf("%d", &a[i][j]);
 
  printf("\nThe matrix is\n");
  for(i = 0;i < 3; i++){
      printf("\n");
      for(j = 0;j < 3; j++)
           printf("%d\t", a[i][j]);
  }
  determinant = a[0][0] * ((a[1][1]*a[2][2]) - (a[2][1]*a[1][2])) -a[0][1] * (a[1][0]
   * a[2][2] - a[2][0] * a[1][2]) + a[0][2] * (a[1][0] * a[2][1] - a[2][0] * a[1][1]);
   if ( determinant == 0)
       printf("\nMatrix is NOT invertible");
   else
       printf("\nThe given matrix has an inverse!!!");
   return 0;
}
```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to Compute Determinant of a Matrix.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
 
int main(){
 
  int a[3][3], i, j;
 
  long determinant;
  printf("Enter the 9 elements of matrix: ");
  for(i = 0 ;i < 3;i++)
      for(j = 0;j < 3;j++)
           scanf("%d", &a[i][j]);
 
  printf("\nThe matrix is\n");
  for(i = 0;i < 3; i++){
      printf("\n");
      for(j = 0;j < 3; j++)
           printf("%d\t", a[i][j]);
  }
 
  determinant = a[0][0] * ((a[1][1]*a[2][2]) - (a[2][1]*a[1][2])) -a[0][1] * (a[1][0]
   * a[2][2] - a[2][0] * a[1][2]) + a[0][2] * (a[1][0] * a[2][1] - a[2][0] * a[1][1]);
 
  printf("\nDeterminant of 3X3 matrix: %ld", determinant);
 
   return 0;
}
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to Implement Hash Tables.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
#include<stdlib.h>
 
struct data 
{
	int key;
	int value;
};
 
struct data *array;
int capacity = 10;
int size = 0;
 
/* this function gives a unique hash code to the given key */
int hashcode(int key)
{
	return (key % capacity);
}
 
/* it returns prime number just greater than array capacity */
int get_prime(int n)
{
	if (n % 2 == 0) 
        {
		n++;
	}
	for (; !if_prime(n); n += 2);
 
	return n;
}
 
/* to check if given input (i.e n) is prime or not */
int if_prime(int n)
{
	int i;
	if ( n == 1  ||  n == 0) 
        {
		return 0;
	}
	for (i = 2; i < n; i++) 
        {
		if (n % i == 0) 
                {
			return 0;
		}
	}
	return 1;
}
 
void init_array()
{
	int i;
	capacity = get_prime(capacity);
	array = (struct data*) malloc(capacity * sizeof(struct data));
	for (i = 0; i < capacity; i++) 
        {
		array[i].key = 0;
		array[i].value = 0;
	}
}
 
/* to insert a key in the hash table */
void insert(int key)
{
	int index = hashcode(key);
	if (array[index].value == 0) 
        {
		/*  key not present, insert it  */
		array[index].key = key;
		array[index].value = 1;
		size++;
		printf("\n Key (%d) has been inserted \n", key);
	}
	else if(array[index].key == key) 
        {
		/*  updating already existing key  */
		printf("\n Key (%d) already present, hence updating its value \n", key);
		array[index].value += 1;
	}
	else
        {
		/*  key cannot be insert as the index is already containing some other key  */
		printf("\n ELEMENT CANNOT BE INSERTED \n");
	}
}
 
/* to remove a key from hash table */
void remove_element(int key)
{
	int index  = hashcode(key);
	if(array[index].value == 0)
        {
		printf("\n This key does not exist \n");
	}
	else {
		array[index].key = 0;
		array[index].value = 0;
		size--;
		printf("\n Key (%d) has been removed \n", key);
	}
}
 
/* to display all the elements of a hash table */
void display()
{
	int i;
	for (i = 0; i < capacity; i++)
        {
		if (array[i].value == 0)
                {
			printf("\n Array[%d] has no elements \n");
		}
		else 
                {
			printf("\n array[%d] has elements -:\n key(%d) and value(%d) \t", i, array[i].key, array[i].value);
		}
	}
}
 
int size_of_hashtable()
{
	return size;
}
 
void main()
{
	int choice, key, value, n, c;
	clrscr();
 
	init_array();
 
	do {
		printf("\n Implementation of Hash Table in C \n\n");
		printf("MENU-:  \n1.Inserting item in the Hash Table" 
                               "\n2.Removing item from the Hash Table"
		               "\n3.Check the size of Hash Table" 
                               "\n4.Display a Hash Table"
		       "\n\n Please enter your choice -:");
 
		scanf("%d", &choice);
 
		switch(choice) 
                {
 
		case 1:
 
		      printf("Inserting element in Hash Table\n");
		      printf("Enter key -:\t");
		      scanf("%d", &key);
		      insert(key);
 
		      break;
 
		case 2:
 
		      printf("Deleting in Hash Table \n Enter the key to delete-:");
		      scanf("%d", &key);
		      remove_element(key);
 
		      break;
 
		case 3:
 
		      n = size_of_hashtable();
		      printf("Size of Hash Table is-:%d\n", n);
 
		      break;
 
		case 4:
 
		      display();
 
		      break;
 
		default:
 
		       printf("Wrong Input\n");
 
		}
 
		printf("\n Do you want to continue-:(press 1 for yes)\t");
		scanf("%d", &c);
 
	}while(c == 1);
 
	getch();
 
}

```
----------------------------------------

 
# Question 56

### **Question:**

> ***Write a program to Check if a Matrix is a Sparse Matrix.***

----------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
 
void main ()
{
    int matrix[10][10];
    int i, j, m, n;
    int sparse_counter = 0;
 
    printf("Enter the order of the matrix \n");
    scanf("%d %d", &m, &n);
    printf("Enter the elements of the matrix \n");
    for (i = 0; i < m; ++i)
    {
        for (j = 0; j < n; ++j)
        {
            scanf("%d", &matrix[i][j]);
            if (matrix[i][j] == 0)
            {
                ++sparse_counter;
            }
        }
    }
    if (sparse_counter > ((m * n) / 2))
    {
        printf("The given matrix is Sparse Matrix !!! \n");
    }
    else
        printf("The given matrix is not a Sparse Matrix \n");
    printf("There are %d number of Zeros.", sparse_counter);
}
```
----------------------------------------

 
# Question 57

### **Question:**

> ***Write a program to Perform Complex Number Multiplication.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
typedef struct COMPLEX{
    int a;
    int b;
}Complex;
Complex multiply(Complex, Complex);
int main(){
    int a1, b1, a2, b2;
    Complex x, y, z;
    printf("Enter first complex number : ");
    scanf("%d+%di", &a1, &b1);
    printf("\nEnter second complex number : ");
    scanf("%d+%di", &a2, &b2);
    x.a = a1;
    x.b = b1;
    y.a = a2; 
    y.b = b2;
    z = multiply(x, y);
    printf("\nAfter multiplication: %d+%di", z.a, z.b);
    return 0;
}
Complex multiply(Complex x, Complex y){
    Complex z;
    z.a = x.a * y.a - x.b * y.b;
    z.b = x.a * y.b + x.b * y.a;
    return z;
}
```
----------------------------------------
# Question 58

### **Question:**

> ***Write a program to Generate Random Hexadecimal Bytes.***

----------------------------------------

<strong>Solution: </strong>

```c
#include <time.h>
#include <stdio.h>
#include <stdlib.h>
 
int main(void)
{
    int length;
    char str[] = "0123456789ABCDEF";
    /* Seed number for rand() */
    srand((unsigned int) time(0) + getpid());
    length = rand() % 15 + 8;
 
    while(length--) {
        putchar(str[rand() % 16]);
        srand(rand());
    }
    printf("\n");
 
    return EXIT_SUCCESS;
}
```
----------------------------------------


