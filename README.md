# 🐍 Python Basics Projects

> **Data Technician Bootcamp | Python | Programming Fundamentals | Logic & Problem Solving**

![Python](https://img.shields.io/badge/Python-Programming-blue?style=flat-square&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?style=flat-square&logo=googlecolab&logoColor=white)
![Programming](https://img.shields.io/badge/Programming-Fundamentals-green?style=flat-square)

---

## 🔎 Overview

This repository contains a collection of **Python programming exercises and projects** completed during my Data Technician Bootcamp.

The work focuses on core Python fundamentals, including variables, user input, type casting, conditional logic, loops and calculations. These concepts were applied to small programs and logic-based challenges using **Google Colab**.

---

## 📂 Projects & Exercises Included

| Project | Focus |
|---|---|
| 👋 **Basic Python Exercises** | Variables, `print()`, `input()` and calculations |
| 🔢 **FizzBuzz** | Conditional statements, loops and divisibility logic |
| 🏧 **ATM Simulation** | User interaction, calculations and repeated program flow |
| 🧮 **Calculation Exercises** | Temperature conversion, area, interest and numerical problems |
| 🔍 **Logic Challenges** | Even/odd checks, prime numbers, palindromes and list analysis |

---

## 🛠️ Python Fundamentals

### 📦 Variables & Data Types

Variables were used to store values such as names, ages, numbers and account balances.

```python
name = "Stefan"
age = 25
balance = 1000
```

The exercises also introduced common Python data types:

- `str`
- `int`
- `float`
- `bool`

---

### 🖨️ Output & User Input

`print()` was used to display results and messages, while `input()` allowed programs to interact with users.

```python
name = input("Enter your name: ")
print("Hello,", name)
```

Type casting was used when user input needed to be converted for calculations:

```python
age = int(input("Enter your age: "))
price = float(input("Enter the price: "))
```

---

### 🧮 Calculations

Python arithmetic operators were used for tasks such as:

- Adding numbers
- Temperature conversion
- Rectangle area calculations
- Compound interest
- Converting days into years, weeks and days
- Updating account balances

```python
length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print("Area:", area)
```

---

## 🔀 Conditional Logic

`if`, `elif` and `else` statements were used to make decisions based on user input or calculated values.

```python
number = int(input("Enter a number: "))

if number > 0:
    print("Positive")
elif number < 0:
    print("Negative")
else:
    print("Zero")
```

Conditional logic was applied to tasks such as:

- Positive, negative or zero checks
- Even and odd numbers
- User menu selections
- Transaction validation
- Divisibility checks

---

## 🔁 Loops

### `for` Loops

`for` loops were used to repeat actions across sequences and numerical ranges.

```python
for number in range(1, 11):
    print(number)
```

### `while` Loops

`while` loops were used for programs that needed to continue running until a condition was met.

```python
running = True

while running:
    option = input("Select an option: ")

    if option == "exit":
        running = False
```

---

# 🔢 FizzBuzz

FizzBuzz combined loops, conditional statements and mathematical operators.

The program loops through numbers from 1 to 100 and applies the following rules:

- Divisible by `3` → **Fizz**
- Divisible by `5` → **Buzz**
- Divisible by both → **FizzBuzz**
- Otherwise → print the number

```python
for number in range(1, 101):

    if number % 3 == 0 and number % 5 == 0:
        print("FizzBuzz")
    elif number % 3 == 0:
        print("Fizz")
    elif number % 5 == 0:
        print("Buzz")
    else:
        print(number)
```

This exercise demonstrated how multiple programming concepts can be combined to solve a structured logic problem.

---

# 🏧 ATM Simulation

A larger exercise involved creating an **ATM-style program** using user input, conditional logic and repeated program flow.

The program included options to:

- 💰 View the current balance
- ➕ Deposit money
- ➖ Withdraw money
- 🔢 Enter custom withdrawal amounts
- ✅ Validate transactions
- 🔐 Apply PIN validation logic
- 🚪 Exit the program

The project demonstrated how Python fundamentals can be combined into a simple interactive application.

---

## 🧠 Logic & Problem-Solving Exercises

Additional exercises included:

✅ Checking whether numbers are even or odd  
✅ Finding minimum and maximum values  
✅ Checking whether strings are palindromes  
✅ Calculating compound interest  
✅ Checking whether numbers are prime  
✅ Finding the sum of positive numbers  
✅ Counting words in a sentence  
✅ Checking leap years  
✅ Calculating the sum of digits  

---

## 💻 Development Environment

The exercises were primarily completed using **Google Colab**, allowing Python code to be written, executed, tested and documented within interactive notebooks.

---

## 💡 What I Practised

Through these projects, I developed practical experience in:

✅ Python syntax and variables  
✅ `print()` and `input()`  
✅ Type casting  
✅ Arithmetic operations  
✅ `if`, `elif` and `else`  
✅ `for` and `while` loops  
✅ User input validation  
✅ Building interactive programs  
✅ Programming logic and problem solving  
✅ Testing and debugging code  

---

## 🎯 Key Skills

`Python` • `Variables` • `print()` • `input()` • `Type Casting` • `Conditional Statements` • `For Loops` • `While Loops` • `Arithmetic` • `User Input` • `Programming Logic` • `Problem Solving` • `Google Colab`

---

## 📚 Project Context

These projects were completed as part of my **Data Technician Bootcamp** and form part of my developing data analytics and programming portfolio.

They provide the foundation for progressing into **data analysis with pandas, data manipulation and Python-based analytics**.
