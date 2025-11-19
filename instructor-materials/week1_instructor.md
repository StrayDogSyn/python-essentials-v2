# Week 1 Instructor Guide: Introduction to Python

## 🎯 Weekly Learning Objectives

By the end of this week, students will be able to:

*   Understand and use basic Python data types: strings, integers, floats, and booleans.
*   Perform arithmetic operations.
*   Use variables to store and manipulate data.
*   Write basic Python functions.
*   Understand the importance of indentation in Python.
*   Use conditional statements (`if`, `elif`, `else`) to control the flow of their code.
*   Use `for` loops to iterate over sequences.
*   Understand how to use the `range()` function.

## Session 1: Introduction to Python (One-on-One)

### 🐍 What is Python?

*   **Talking Point:** Start by asking the student about their background and what they hope to learn in the course. This is a good opportunity to build rapport and tailor the session to their needs.
*   **Key Concepts:**
    *   Python is a high-level, interpreted language.
    *   It's known for its readability and simplicity.
    *   It's used in a wide variety of fields, including web development, data science, and AI.

### 🔢 Data Types and Arithmetic Operations

*   **Key Concepts:**
    *   **Strings:** Sequences of characters (e.g., `"Hello, world!"`).
    *   **Integers:** Whole numbers (e.g., `10`, `-5`).
    *   **Floats:** Numbers with decimal points (e.g., `3.14`, `-0.5`).
    *   **Booleans:** `True` or `False`.
*   **Activity:** Have the student create a variable for each data type and print it.
*   **Discussion Point:** When discussing division, point out that it always returns a float.

### 📦 Variables

*   **Key Concepts:**
    *   Variables are used to store data.
    *   Python is dynamically typed, so you don't need to declare a variable's type.
*   **Activity:** Have the student create two variables and perform an arithmetic operation with them.
*   **Discussion Point:** Discuss good variable naming conventions (e.g., descriptive names, using snake_case).

### 🧱 Functions

*   **Key Concepts:**
    *   Functions are reusable blocks of code.
    *   They can take input (parameters) and return output.
*   **Activity:** Have the student write a simple function, first without parameters and then with parameters.
*   **Challenge:** Ask the student to write a function that calculates the area of a rectangle.

### 📏 Indentation

*   **Key Concepts:**
    *   Indentation is a fundamental part of Python's syntax.
    *   It's used to define code blocks.
*   **Discussion Point:** Intentionally show an `IndentationError` and explain why it happens. This is a common stumbling block for beginners.

## Session 2: Introduction to Python (Group)

### 🤔 Review

*   **Discussion Point:** Start by reviewing the concepts from the one-on-one session. Ask students to define the basic data types and explain what variables are used for.

### 🚦 Control Flow: Conditional Statements

*   **Key Concepts:**
    *   `if`, `elif`, and `else` are used to make decisions in code.
*   **Activity:** Have students write a program that checks if a number is positive, negative, or zero.
*   **Group Activity:** Work together to write the `categorize_numbers` function.

### 🔄 Control Flow: `for` Loops

*   **Key Concepts:**
    *   `for` loops are used to iterate over sequences.
    *   The `range()` function is a common way to create a sequence of numbers to loop over.
*   **Discussion Point:** When using `range()`, make sure students understand that the sequence starts at 0 and ends one number before the specified value.
*   **Activity:** Have students write a `for` loop to print the numbers from 1 to 10.

### 🚀 Putting It All Together

*   **Activity:** Have students write a function that uses both a `for` loop and an `if` statement to print the even numbers in a list.

### 🐞 Group Debugging Challenge

*   **Activity:** Present the buggy `calculate_average` function and have students work together to find and fix the errors.
    *   **Bug 1:** The function doesn't handle the case where the input list is empty. This will cause a `ZeroDivisionError`.
    *   **Bug 2:** The variable `my_numbers` is defined inside the function, so it's not accessible outside of it.

### 🚀 Code Challenge: FizzBuzz

*   **Activity:** This is a classic programming problem that's great for practicing loops and conditionals. Encourage students to work together and share their solutions.

## 📚 Additional Resources

*   [Python for Beginners](https://www.python.org/about/gettingstarted/)
*   [Codecademy: Learn Python 3](https://www.codecademy.com/learn/learn-python-3)
*   [Real Python](https://realpython.com/)
