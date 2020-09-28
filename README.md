# coding-project-1
##All of the functions for addition, subtraction, multiplication, and division
def add(x, y):
  return x + y
def subtract(x, y):
  return x - y
def multiply(x, y):
  return x * y
def divide(x, y):
  return x / y
#provides instrucrions for the user, and strarting point for the loop
myVar = 1
while myVar > 0 :
  print("1=add")
  print("2=subtract")
  print("3=multiply")
  print("4=divide")
  #ask the user what opperation they desire
  user_input = input("choose an opperation (1,2,3, or 4): ")
  #ask the user what numbers they want to use
  num1 = float(input("enter first number: "))
  num2 = float(input("enter second number: "))
  #function and text for addition
  if user_input == '1':
    print(num1, "+", num2, "=", add(num1, num2))
  #function and text for subtraction
  if user_input == '2':
    print(num1, "-", num2, "=", subtract(num1, num2))
  #function and text for multiplication
  if user_input == '3':
    print(num1, "*", num2, "=", multiply(num1, num2))
  #function and text for division
  if user_input == '4':
    print(num1, "/", num2, "=", divide(num1, num2))
#For this project, I fiugred the best way to go about starting was by first defining the four main variables for the project (+,-,*,/). I first chose to define what add, subtract, multiply, and divide all meant, by stating the function that would need to be used when the user chose a task. Whatever the user picked, it would return the correct method for solving for the variables, which were x, and y. I continued by then asking the user what opperation they would like to calculate. By entering 1,2,3, or 4, the user would state whether they would like to add, subtract, multiply, or divide. Next, the user would just have to enter the two numbers they would like to calculate, and the code would solve for them. When it was asked to solve, the code would print the x variable, (+,-,*, or /) and the y variable to give an answer. By including Myvar=1, while myvar>0, this allows for the program to start over, and loop so the user can continue to enter their function, and the variables they want to solve for, creating a loop. This is how I was able to code a calculator for the functions add, subtract, multiply, or divide. 
