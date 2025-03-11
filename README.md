#  Algorithm exercises

**Problem 1: Calculate the Sum of Natural Numbers**

Write an algorithm that calculates the sum of all natural numbers from 1 to a given number n.



 Input: A positive integer n
 If n is less than 1, return an error or handle the invalid input.
Initialize a variable sum to 0.
Initialize a loop counter i to 1.
 While i is less than or equal to n:
 Add i to sum.
 Increment i by 1.
Return the value of sum.



The user should input a value for n.
The algorithm should compute the sum using a loop and display the result.





**Problem 2: Check for Prime Number**

Write an algorithm that checks if a given number n is a prime number or not.
Input: A positive integer n
 If n is less than or equal to 1, return "Not Prime" (or handle the invalid input).
If n is 2, return "Prime".
 If n is even (n % 2 == 0), return "Not Prime".
 Iterate from 3 up to the square root of n (inclusive), incrementing by 2 (checking only odd divisors):
 If n is divisible by the current number, return "Not Prime".
If the loop completes without finding a divisor, return "Prime".

The user should input a value for n.
The algorithm should check whether the number is divisible by any number other than 1 and itself.
```

**Problem 3: Find the Maximum of Three Numbers**

Write an algorithm that takes three numbers as input and finds the largest of them.
```
The user should input three values: a, b, and c.
The algorithm should compare the numbers and print the maximum value.
Input: Three numbers a, b, and c
 If a is greater than or equal to b and a is greater than or equal to c:
 Return a as the maximum.
Else if b is greater than or equal to a and b is greater than or equal to c:
Return b as the maximum.
 Else:
 Return c as the maximum.

**Problem 4: Factorial Calculation**

Write an algorithm that calculates the factorial of a number n.
```
The user should input a number n.
The algorithm should compute the factorial by multiplying all the integers from 1 to n.

Input: A non-negative integer n
If n is less than 0, return an error or handle the invalid input.
If n is 0 or 1, return 1 (factorial of 0 and 1 is 1).
Initialize a variable factorial to 1.
 Iterate from 2 up to n (inclusive):
 Multiply factorial by the current number.
 Return the value of factorial.

**Problem 5: Check if a Number is Even or Odd**

Write an algorithm that checks if a given number n is even or odd.
```
The user should input a value for n.
The algorithm should check whether n is divisible by 2 and display the result as either "Even" or "Odd".

Input: An integer n
If n is divisible by 2 (n % 2 == 0):
 Return "Even".
 Else:
 Return "Odd".


