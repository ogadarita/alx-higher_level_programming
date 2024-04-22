# Python

## Table of Contents

1. [What is Python?](#what-is-python)
2. [Python Basics](#python-basics)
   - [Syntax](#syntax)
   - [Variables and Data Types](#variables-and-data-types)
   - [Operators](#operators)
   - [Control Flow](#control-flow)
   - [Functions](#functions)
3. [Advanced Python](#advanced-python)
   - [Object-Oriented Programming](#object-oriented-programming)
   - [Modules and Packages](#modules-and-packages)
   - [Exceptions Handling](#exceptions-handling)
   - [File Handling](#file-handling)
4. [Python Libraries and Frameworks](#python-libraries-and-frameworks)
   - [NumPy](#numpy)
   - [Pandas](#pandas)
   - [Matplotlib](#matplotlib)
   - [Django](#django)
   - [Flask](#flask)

## What is Python?

Python is a high-level, interpreted programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991. Python emphasizes code readability, allowing developers to express concepts in fewer lines of code compared to other programming languages. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

## Python Basics

### Syntax

Python syntax is simple and easy to learn. Here's a basic "Hello, World!" program in Python:

```python
print("Hello, World!")
```

### Variables and Data Types

Python supports various data types, including integers, floats, strings, lists, tuples, dictionaries, and more. Variables are dynamically typed, meaning you don't need to declare the data type explicitly. Here's an example:

```python
x = 10
y = 3.14
name = "Python"
```

### Operators

Python supports a wide range of operators for arithmetic, comparison, logical operations, and more. Here are a few examples:

```python
# Arithmetic operators
x = 10
y = 5
sum = x + y
difference = x - y
product = x * y
quotient = x / y

# Comparison operators
x > y
x < y
x == y
x != y

# Logical operators
x and y
x or y
not x
```

### Control Flow

Python provides control flow statements such as if, elif, and else for decision making, and for and while loops for iteration.

```python
# Example of if-else statement
if condition:
    # do something
else:
    # do something else

# Example of for loop
for i in range(5):
    print(i)

# Example of while loop
while condition:
    # do something
```

### Functions

Functions are blocks of reusable code that perform a specific task. You can define functions using the `def` keyword.

```python
def greet(name):
    print("Hello, " + name + "!")
```

## Advanced Python

### Object-Oriented Programming

Python supports object-oriented programming (OOP) concepts such as classes, objects, inheritance, polymorphism, and encapsulation.

```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def drive(self):
        print("Driving", self.brand, self.model)
```

### Modules and Packages

Python modules are files containing Python code, and packages are directories of Python modules. You can import modules and packages to use their functionality in your code.

```python
import math
from datetime import datetime
```

### Exceptions Handling

Python provides built-in exception handling using try, except, finally, and raise statements to handle errors gracefully.

```python
try:
    # risky code
except Exception as e:
    # handle exception
finally:
    # cleanup code
```

### File Handling

Python allows you to read from and write to files using file handling operations like open(), read(), write(), close(), and more.

```python
file = open("example.txt", "r")
content = file.read()
file.close()
```

## Python Libraries and Frameworks

Python has a rich ecosystem of libraries and frameworks for various purposes. Here are some popular ones:

### NumPy

NumPy is a powerful library for numerical computing in Python, providing support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions.

### Pandas

Pandas is a library for data manipulation and analysis. It provides data structures like Series and DataFrame, making it easy to work with structured data.

### Matplotlib

Matplotlib is a plotting library for creating static, interactive, and animated visualizations in Python. It is widely used for data visualization tasks.

### Django

Django is a high-level web framework for building web applications in Python. It follows the "don't repeat yourself" (DRY) principle and emphasizes rapid development.

### Flask

Flask is a lightweight web framework for building web applications in Python. It is simple, flexible, and easy to learn, making it ideal for small to medium-sized projects.
