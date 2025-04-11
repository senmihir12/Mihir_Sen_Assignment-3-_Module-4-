Task 1 - Calculate Factorial using a function
Declaring variable 'a' to get an integer input - a = int(input('Enter a number: '))
Defining a function as factorial - def factorial(n):
Using if-else statement within function factorial - if n < 2:
        return 1
    else:
        return n * factorial(n-1)

result would be factorial of 'a' - result = factorial(a)
printing the result - print(f"Factorial of {a} is: {result}")



Task 2 - Using math module for calculations
Import all functions from math library - from math import *
Declaring variable 'a' to get a decimal input - a = float(input('Enter a number: '))
Use functions for square root, natural logarithm and sine in radians to be applied to decimal input 'a'
square_root = sqrt(a)
natural_log = log(a,e) - where e is the base
sine_number = sin(a)
printing the results - 
print('Square root: ',square_root)
print('Logarithm: ',natural_log)
print('Sine: ',sine_number)
