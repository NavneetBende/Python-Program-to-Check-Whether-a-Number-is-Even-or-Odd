# Python-Program-to-Check-Whether-a-Number-is-Even-or-Odd


Check Whether a Number is Even or Odd in Python
Check Whether a Number is Even or Odd in Python
Given an integer input num, the objective is to write a code to Check Whether a Number is Even or Odd in Python. To do so we check if the number is divisible by 2 or not, it’s Even if it’s divisible otherwise Odd.

Example 
Input : num = 3
Output : Odd 
Check Whether a Number is Even or Odd in Python
Given an integer input the objective is to write a Python code to Check Whether a Number is Even or Odd. To do so the main idea is to divide the number by 2 and check if it’s divisible or not. It’s an Even number is it’s perfectly divisible by 2 or an Odd number otherwise.

Here are the Methods to solve the above mentioned problem,

Method 1 : Using Brute Force
Method 2 : Using Ternary Operator
Method 3 : Using Bitwise Operators
We’ll discuss the above mentioned methods in detail in the next section.

Related Pages
Sum of First N Natural numbers

Sum of N natural numbers

Sum of numbers in a given range

Greatest of two numbers

Greatest of the Three numbers

Method 1 : Using Brute Force
This method simply checks if the given input integer is divisible by 2 or not. If it’s divisible then print Even or Odd otherwise.

Python Code
Run
num = int(input("Enter a Number:")) 
if num % 2 == 0: 
  print("Given number is Even") 
else: 
  print("Given number is Odd")
Output
Enter a Number: 5 
Given number is Odd
Working
The working of the above mentioned code is as follows,

Start
Insert a number.
If the given number is divisible by 2, then print,” Given number is even”.
If the given number is not divisible by 2, then print ,”Given number is odd”.
Stop
Explanation
Given an integer as input, the objective is check whether the number is even or odd in Python. To do so we check if it’s divisible by 2 or not. If true, it’s even or it’s odd otherwise.

The algorithm for the above code is as given below,

Import the required modules using import keyword.
Initialize the required variables.
Check if the number is divisible by 2, if true print even or odd otherwise using print() function.
The output for the above code is wither even or odd based on whether or not it’s divisible by 2.

Method 2 : Using Ternary Operator
This Method uses the ternary operator to check if the integer input is divisible by 2, If true print Even or Odd otherwise.

Ternary Operator Syntax Python
( True : Action ) if ( Condition ) else ( False : Action )
Python Code
Run
num = 17
print("Even") if num%2 == 0 else print("Odd")
Output
Odd
Working
The working of the above code is as follows,

Input an integer input num.
Check whether the number is divisible by 2 using the ternary operator
Ternary Operation, print(“Even”) if (num%2 == 0) else (print(“Odd”))
Explanation
Given an integer as input, the objective is check whether the number is even or odd in Python. To do so we check if it’s divisible by 2 or not using a Ternary Operator in Python. If true, it’s even or it’s odd otherwise.

The algorithm for the above code is as given below,

import the required modules using import keyword.
Initialize the required variables.
Check if the number is divisible by 2 using a Ternary Operator, if true print even or odd otherwise using print() function.
The output for the above code is wither even or odd based on whether or not it’s divisible by 2.


Method 3 : Using Bitwise Operator
This Method uses bitwise operators to check if a given number is Even or Odd.

Bitwise Operators
In computer programming, a bitwise operation operates on a bit string, a bit array or a binary numeral at the level of its individual bits. It is a fast and simple action, basic to the higher-level arithmetic operations and directly supported by the processor.
Python Code
Run
def isEven(num):
  return not num&1

if __name__ == "__main__":
  num = 13
  if isEven(num):
    print('Even')
  else:
    print('Odd')
Output
Odd
Working
The working of the above code is as follows,

If we have any number num doing bitwise ‘&‘ operation will give resultant as
1: If n is odd
0: if n is even
Explanation
Given an integer as input, the objective is check whether the number is even or odd in Python. To do so we check if it’s divisible by 2 or not using Bitwise Operator. If true, it’s even or it’s odd otherwise.

The algorithm for the above code is as given below,

Import the required modules using import keyword.
Define a function isEven() which returns a boolean variable to check if the number is even or odd.
Initialize the required variables.
Check if the function after calling returns True or False, if true print even or odd otherwise using print() function.
The output for the above code is wither even or odd based on whether or not it’s divisible by 2.
