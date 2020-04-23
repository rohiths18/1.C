# 1.C
Create a small calculator which performs operations such as Addition, Subtraction,Multiplication and Division.  Calculator

Inputs:‘a’,‘b’and ‘type of operation’  Datatypes: ‘a’ = double, ‘b’= double, ‘type of operation’ = string

#include <stdio.h> - Header file for standard input and output

int main() - entry into the program

{ - begining of function main

   double a,b; -declaring of variable a and b ( datatype -double)
   
   int add, subtract, multiply; - declaring the operatioins ( datatype - integer)
   
   float divide; ( datatype - float)
 
   printf("Enter two integers\n"); - command used for displaying constant message 
   
   scanf("%lf,%lf", &a, &b); - used to accept values during runtime
   
   
   add =a + b; - addition operation
   
   subtract = a - b; - subtraction operation
   
   multiply = a * b; - multiplication operation 
   
   divide = a / (float)b;  - division operation
   
   printf("Sum = %d\n", add); - displays the sum of 2 numbers
   
   printf("Difference = %d\n", subtract); - displays the difference of 2 numbers
   
   printf("Multiplication = %d\n", multiply); - displays product of 2 numbers
   
   printf("Division = %.2f\n", divide); - displays remainder 
 
   return 0; - to return an integer value ( as described in main() )
   
}- end of main function

