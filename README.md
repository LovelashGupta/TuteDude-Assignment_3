# TuteDude-Assignment_3
Assignment3 for my python course

This repository contains two Python scripts that perform basic mathematical operations. The scripts are designed to demonstrate simple Python programming concepts such as recursion, mathematical functions, and user input handling.

Task 1: Factorial Calculation
Description:
This script calculates the factorial of a given number using recursion. The factorial of a number n is the product of all positive integers less than or equal to n.

Code (Task 1 - Task 1.py):
def factorial(n):
    if n < 2:
        return 1
    else:
        return n * (factorial(n-1))

n = int(input("Enter a number: "))
result = factorial(n)
print("Factorial of", n, "is:", result)

Instructions:
The program prompts the user to enter a number.
It calculates the factorial of that number using a recursive function.
The result is printed on the screen.
Do Check the recursion limit in case factorial of large number is required (by default recuresion limit is 1000)

Example Output:
Enter a number: 5
Factorial of 5 is: 120

Task 2: Mathematical Functions
Description:
This script uses the math module to perform several mathematical operations on a given number. It computes the square root, logarithm, and sine of the input number.

Code (Task 2 - Task 2.py):
from math import *

n = int(input("Enter a number: "))
print("Square root:", sqrt(n))
print("Logarithm:", log(n))
print("Sine:", sin(n))

Instructions:
The program prompts the user to enter a number.
It calculates the square root, logarithm, and sine of the number using functions from the math library.
The results are displayed on the screen.

Example Output:
Enter a number: 16
Square root: 4.0
Logarithm: 2.772588722239781
Sine: -0.2879033166650653

🚀 How to Run
Make sure you have Python installed (version 3.x recommended).
Download the script file.
Open the cmd in the downloaded forder
Run the script using the command: python Task1.py python Task2.py

📁 Repository Structure 📁 TuteDude-Assignment_3/ ├── Task1.py # Factorial Calculation └── Task2.py # Mathematical Functions

💬 Feedback Feel free to open an issue or submit a pull request if you'd like to contribute or suggest improvement
