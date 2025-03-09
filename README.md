# ASSIGNMENT-3
# Module 4: Functions &amp; Modules in Python 
# Task 1: Calculate Factorial Using a Function
n = int(input("Enter a number: "))
def factorial(n):
    if n < 2:
        return 1
    else:
        return n * (factorial(n-1))
result = factorial(n)
print("Factorial of" ,n, "is:" ,result)

# Task 2: Using the Math Module for Calculations
import math
n = int(input("Enter a number: "))
print("Square root: " ,math.sqrt(n))
print("Logarithm: " ,math.log(n))
print("Sine: " ,math.sin(n))
