# factorial-calculator
Factorial Calculator

The factorial of a non-negative integer 𝑛 ( denoted as n! ) is the product of all positive integers less than or equal to 𝑛.


1) For Factorial Calculation:

We define a function factorial(int n) that calculates the factorial using a simple for loop. It multiplies all integers from 1 to 𝑛, storing the result in the variable fact, which is initialized to 1.
The return type is unsigned long long to handle larger factorials, as factorials grow very fast and can quickly exceed the range of standard integer types.

2) Main Function:

In the main() function, we prompt the user to input a number. The input is checked to ensure it's not negative, as factorials are not defined for negative integers.
The factorial of the number is calculated by calling the factorial() function, and the result is printed.

3) Input/Output:
The program prompts the user to input a number and then outputs the factorial of that number.

4) Edge Cases:
A) The factorial of 0 is defined as 1 (i.e., 0!=1).
B) The program handles negative inputs by printing an error message.
