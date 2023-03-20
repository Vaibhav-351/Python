# Python_Assignement01_solution
Q1.### 1. Write a Python program to print \"Hello Python\"?"

print("Hello Python")

Q2.### 2. Write a Python program to do arithmetical operations addition and division.?\n"

num1 = int(input("Enter number 1: \n"))
num2 = int(input("Enter number 2: \n"))

addition = num1+num2
print("Addition of",num1,'and',num2,"is :",addition)

division_quotint = num1/num2
print("Division quotient of",num1,'and',num2,"is :",division_quotint)

division_remainder = num1%num2
print("Division remainder of",num1,'and',num2,"is :",division_remainder)



Q3.### 3. Write a Python program to find the area of a triangle?\n"

height = int(input("Enter height of triangle: \n"))
base = int(input("Enter base of triangle: \n"))

area_of_traingle = (0.5*height*base)
print("Area of triangle is :",area_of_traingle,"meter square")



Q4.### 4. Write a Python program to swap two variables?\n"

num1 = int(input("Enter number 1 : \n"))
num2 = int(input("Enter number 2 : \n"))

num3 = 0
print("\n")
print("Before swapping")
print("First number is:",num1)
print("Second number is:",num2)

num3 = num1
num1 = num2
num2 = num3

print("\n")
print("After swapping")
print("First number is:",num1)
print("Second number is:",num2)



Q5.### 5. Write a Python program to generate a random number?\n"

import random #random module having radom function

num = random.random() #function random(), which generates a random float number between 0.0 and 1.0
print(num)
