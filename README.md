# Assignment2.py
Here a two program. The first one is to calculate the factorial of a number. 
The second one to find the square root, natural loarithm and sine valuse of the number using math module. 

# PROGRAM 1

def factorial(n):
    if n < 0:
        return "factorial is not defined for negative numbers."
    elif n == 0:
         return 1
    else:
        result = 1
        for i in range(1, n + 1):
            result *= i
        return result
number = int(input("Enter a non-negative integer: "))
print(f"The factorial of (number is {factorial(number)}") 

# PROGRAM 2

import math
number = float(input("Enter a number: "))
square_root = math.sqrt(number)
natural_log = math.log(number)
sine_value = math.sin(number)
print(f"The square root of {number} is: {square_root}")
print(f"The natural logarithm of {number} is: {natural_log}")
print(f"The sine value of {number} is: {sin_value}")

