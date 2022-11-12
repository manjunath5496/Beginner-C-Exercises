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
return 0;  
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


# Question 56

### **Question:**

> ***Write a program that counts the even, odd, positive, and negative values among eighteen integer inputs.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main () {
int x, even = 0, odd = 0, positive = 0, negative = 0;
printf("\nPlease enter 18 numbers:\n");
for(int i = 0; i < 18; i++) {
scanf("%d", &x);
if (x > 0) {
    positive++;
}
if(x < 0) {
    negative++;
}
if(x % 2 == 0) {
    even++;
}
if(x % 2 != 0) {
    odd++;
}
}
printf("\nNumber of even values: %d", even);
printf("\nNumber of odd values: %d", odd);
printf("\nNumber of positive values: %d", positive);
printf("\nNumber of negative values: %d", negative);
return 0;
}
```
----------------------------------------


# Question 57

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int age;
printf("Enter age: ");
scanf("%d", &age);
if(age>=60) {
printf("Senior citizen");
}
else {
printf("Not a senior citizen");
}
return 0;
}
```
----------------------------------------


# Question 58

### **Question:**

> ***Write a program that reads a student's three subject scores (0-100) and computes the average of those scores.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
float score, total_score = 0;
int subject = 0;
printf("Enter three subject scores (0-100):\n");
while (subject != 3) {
scanf("%f", &score);
if(score < 0 || score > 100) {
printf("Please enter a valid score.\n");
}
else {
total_score += score;
subject++;
  }
}
printf("Average score = %.2f\n", total_score/3);
return 0;
} 
```
----------------------------------------


# Question 59

### **Question:**

> ***What results would the following programs produce?***

----------------------------------------

```C language
#include<stdio.h>
int main() {
for(int i=1; i<=5; i++) {
if(i==3) {
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
#include<stdio.h>
int main() {
for(int i=1;i<=5;i++) {
if(i==3) {
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
int main() {
for( ; ; ) {
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
int main() {
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

```C language
#include<stdio.h>
int main() {
for(int i=1; i<=5; i++) {
if(i==3) {
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


# Question 60

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main() {
int num [] = {11, 22, 33, 44, 55, 66};
int n = sizeof(num) / sizeof(num [0]);
printf("Size of the array is: %d\n", n);
return 0;
}
```
----------------------------------------

# Question 61

### **Question:**

> ***Write a program that prints a sequence from 1 to a given integer, inserts a plus sign between these numbers, and then removes the plus sign at the end of the sequence..***

----------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main () {
int x, i;
printf("\nEnter a integer: \n");
scanf("%d", &x);
if(x>0) {
printf("Sequence from 1 to %d:\n", x);
for(i=1; i<x; i++)  {
printf("%d+", i);
}
printf("%d\n", i);
}
return 0;
}
```
----------------------------------------


