#  Algorithm exercises

**Problem 1: Calculate the Sum of Natural Numbers**

Write an algorithm that calculates the sum of all natural numbers from 1 to a given number n

The user should input a value for n.
The algorithm should compute the sum using a loop and display the result.

def sum_natural_numbers(n):
    total = 0
    for i in range(1, n + 1):
        total += i
    return total

n = int(input("Enter a number: "))
print("Sum of natural numbers:", sum_natural_numbers(n))




**Problem 2: Check for Prime Number**

Write an algorithm that checks if a given number n is a prime number or not.
The user should input a value for n.
The algorithm should check whether the number is divisible by any number other than 1 and itself.
def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

n = int(input("Enter a number: "))
if is_prime(n):
    print(n, "is a prime number.")
else:
    print(n, "is not a prime number.")

**Problem 3: Find the Maximum of Three Numbers**

Write an algorithm that takes three numbers as input and finds the largest of them.
def find_max(a, b, c):
    return max(a, b, c)

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

print("The largest number is:", find_max(a, b, c))

**Problem 4: Factorial Calculation**

Write an algorithm that calculates the factorial of a number n.
```
The user should input a number n.
The algorithm should compute the factorial by multiplying all the integers from 1 to n.
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

n = int(input("Enter a number: "))
print("Factorial of", n, "is", factorial(n))
**Problem 5: Check if a Number is Even or Odd**

Write an algorithm that checks if a given number n is even or odd.
```
The user should input a value for n.
The algorithm should check whether n is divisible by 2 and display the result as either "Even" or "Odd".
def even_or_odd(n):
    return "Even" if n % 2 == 0 else "Odd"

n = int(input("Enter a number: "))
print(n, "is", even_or_odd(n))


