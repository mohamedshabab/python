# 🐍 Python Fundamentals Project

This project documents my practical learning of **Python programming**, based on a collection of hands-on exercises completed across several Python notebooks and script files.  
It covers core Python concepts such as variables, input/output, operators, conditionals, loops, functions, data structures, and beginner-friendly problem-solving tasks.

The goal of this repository is to present clear, organized notes and working code that demonstrate my understanding of foundational Python programming through real practice exercises.

----

## 🛠️ Python Skills Practiced

Throughout this project, I strengthened my Python programming fundamentals by completing a wide range of small exercises and challenges.

### 📌 Core Programming Skills
- Writing basic Python syntax  
- Using variables and different data types  
- Performing arithmetic and comparison operations  
- Working with user input and formatted output  

### 🔁 Control Flow & Logic
- Using `if`, `elif`, `else` for decision-making  
- Writing `for` and `while` loops  
- Combining conditions with logical operators  

### 📦 Data Structures
- Creating and using **lists**  
- Iterating through collections  
- Building simple patterns using loops  

### 🧩 Functions & Reusable Code
- Defining custom functions  
- Passing parameters and returning values  
- Keeping code modular and reusable  

### 🛡️ Error Handling
- Using `try` and `except` to avoid crashes  
- Handling invalid user input safely  

### 🧠 Problem-Solving Practice
- Number checking  
- Unit conversions  
- Simple calculators  
- Sequence generation (factorials, FizzBuzz, patterns)

All of these skills were practiced using the actual notebooks and exercise files in this repository.

----

## 🔍 Example Exercises (with Real Code)

Below are some of the key Python exercises from this project, taken directly from my own code.
---

### 🧓 1. “100 Years Old” Age Calculator

Asks for a name and age, then calculates the year when the person will turn 100.

```python
name = input("WHAT IS YOUR NAME? (write only first name) ")
age = int(input("How old are you? "))
year = 2024 - age + 100

print(f"Hello {name}, you will turn 100 years in {year}.")

```
### 🧱 2. Kitchen Floor Area & Tile Cost Calculator

Calculates the area of a kitchen and estimates the tiling cost.

```python
length = float(input("Enter the length of your ]kitchen in metres: "))
width = float(input("Enter the width of your kitchen in meters: "))
area = length * width

print(f"Your kitchen is {area} square meters.")

tileCost = 20
tilePrice = area * tileCost

print(f"It will cost {tilePrice} pounds to re-tile your kitchen.")

```
### 🌡️ 3. Temperature Conversion & Secret Code

Converts Celsius to Fahrenheit and also reverses a four-digit “secret code”.

```python
t_c = float(input("please, enter today's temperature in Celsius: "))
t_f = t_c * (9/5) + 32

print("Todays tempture in Fahrenheit is: ")
print(t_f)

secret = input("Please enter the 4 -digit code: ")
secret = int(secret)

first_digit = secret // 1000
fourth_digit = secret % 10
second_digit = (secret // 100) % 10
third_digit = (secret // 10) % 10

rever = (fourth_digit * 1000) + (third_digit * 100) + (second_digit * 10) + (first_digit)
print(rever)

```
### 🔢 4. Simple Number Checking (Divisible by 3 and 7)

Checks whether a number is divisible by both 3 and 7.

```python
print("simple number-checking tool.")

number = int(input("Please enter a number: "))

if number % 3 == 0 and number % 7 == 0:
    print("The number is divisible by both 3 and 7")
else:
    print("sorry, the number is  not divisible by both 3 and 7")

```
### 🧮 5. Factorial Calculator

Calculates the factorial of a positive integer using a loop.
```python
print("Simple Factorially Calculator")
n = int(input("Please enter a positive interger: "))
factorily = 1

if n < 0:
    print("The number is negative & has no factorial")
elif n == 0:
    print("the factorial of 0 is 1")
else:
    for i in range(1, n + 1):
        factorily *= i
        print(i)

print(f"The factorial of {n} is {factorily}")

```
### 🔁 6. Simple Multiplication Pattern

Prints a small numeric pattern using nested loops.

```python
num = 5
for i in range(1, num + 1):
    for j in range(1, i + 1):
        print(j, end=" ")
    print()

```
### 🎮 7. FizzBuzz (1 to 99)

Implements the classic FizzBuzz problem using a for loop and conditional logic.

```python
mohamed = range(1, 100)

for shabab in mohamed:
    if shabab % 3 == 0 and shabab % 5 == 0:
        print("FIZZBUZZ")
    elif shabab % 3 == 0:
        print("FIZZ")
    elif shabab % 5 == 0:
        print("BUZZ")
    else:
        print(shabab)


```
These examples are taken directly from the exercise notebooks and represent the kind of problems I solved while learning Python.

---

# 🎓 Learning Outcomes

Working through these exercises helped me build a strong foundation in Python programming.

## 🔹 Python Fundamentals
- Gained confidence with Python syntax, variables, and data types  
- Practiced reading input and printing clear, formatted output  
- Learned how to structure small scripts from start to finish  

## 🔹 Control Flow & Logic
- Used `if` / `elif` / `else` to implement decision-making  
- Combined conditions using logical operators  
- Applied loops (`for`, `while`) to repetition and patterns  

## 🔹 Data Handling & Problem-Solving
- Performed calculations such as factorials, temperature conversion, and cost estimation  
- Worked with user input validation using basic checks  
- Solved logical challenges such as number checking and FizzBuzz  

## 🔹 Code Quality & Reusability
- Broke problems into smaller, manageable steps  
- Wrote readable code with clear intent  
- Practiced using functions (in other exercises) to keep logic modular and reusable  

These outcomes reflect the real skills I practiced while working through the Python exercise files in this repository.

----

# 📌 Conclusion

This Python project gave me a solid, practical introduction to programming through real exercises.  
By working through each task, I learned how to think like a programmer, solve problems step-by-step, and write clear, structured Python code.

I practiced essential concepts such as variables, conditions, loops, lists, and simple functions—building confidence in how Python works and how to apply logic to real problems.  
These exercises strengthened my problem-solving skills, improved my code readability, and helped me understand how to break tasks into manageable pieces.

Overall, this project prepared me for more advanced Python topics such as file handling, modules, APIs, data analysis, and object-oriented programming.

---

## 🖥️ How to Use This Project

This repository contains the Python exercises I completed while learning core programming concepts.

### 📄 What’s Inside
- Basic Python scripts (variables, strings, operators)  
- Control flow exercises (conditions, loops)  
- Data structure tasks (lists, dictionaries)  
- Beginner problem-solving programs (even/odd, calculations, FizzBuzz)  

### ▶️ How to Use
1. Open any `.py` file.  
2. Run it in VS Code, Jupyter, or any Python interpreter.  
3. Read the code and comments to understand each solution.

This project is a simple reference for reviewing essential Python fundamentals.

