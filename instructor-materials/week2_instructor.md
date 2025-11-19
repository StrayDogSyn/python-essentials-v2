# Week 2 Instructor Guide: Data Structures and File Handling

## 🎯 Weekly Learning Objectives

By the end of this week, students will be able to:

*   Work with lists, tuples, dictionaries, and sets.
*   Read from and write to files.
*   Import and use modules.
*   Use simple OS operations and keyboard input.

## Session 1: Data Structures (One-on-One)

### 📊 Data Structures

*   **Talking Point:** Start by explaining that data structures are used to organize and store data. Give a real-world analogy, like a to-do list (a list) or a phone book (a dictionary).

### Lists

*   **Key Concepts:** Ordered, mutable, and versatile.
*   **Activity:** Have the student create a list, add and remove items, and iterate through it.

### Tuples

*   **Key Concepts:** Ordered and immutable.
*   **Activity:** Demonstrate that tuples cannot be changed after they are created. Discuss when to use tuples over lists (e.g., for data that should not be modified).

### Dictionaries

*   **Key Concepts:** Key-value pairs, mutable, and unordered (in older Python versions).
*   **Activity:** Have the student create a dictionary, add a new key-value pair, and access data using keys.

### Sets

*   **Key Concepts:** Unordered, mutable, and do not allow duplicates.
*   **Activity:** Show how to use a set to remove duplicates from a list.

### 📂 File Handling

*   **Key Concepts:** The `open()` function, file modes (`'r'`, `'w'`, `'a'`), and the `with` statement.
*   **Activity:** Have the student write to a file and then read from it.

### 📦 Modules

*   **Key Concepts:** The `import` statement and how to use functions from modules.
*   **Activity:** Have the student import the `random` module and use it to make a random choice from a list.

### ⌨️ Keyboard Input and OS Operations

*   **Key Concepts:** The `input()` function for getting user input and the `os` module for interacting with the operating system.
*   **Activity:** Have the student write a program that asks for their name and then prints a greeting. Show them how to list the files in the current directory.

## Session 2: Data Structures (Group)

### 🤔 Review

*   **Discussion Point:** Start with a quick review of the data structures covered in the one-on-one session.

### 📝 Activities

*   **Deduplicate with Sets:**
    *   **Goal:** Write a function to remove duplicates from a list while preserving order.
    *   **Collaboration:** Discuss why `dict.fromkeys()` is a good way to do this.
*   **Merge Dictionaries:**
    *   **Goal:** Write a function to merge two dictionaries.
    *   **Collaboration:** Discuss different ways to merge dictionaries and the pros and cons of each.
*   **List Slicing and Mapping:**
    *   **Goal:** Create a new list containing the squares of the last five numbers in a given list.
    *   **Collaboration:** Discuss alternative ways to achieve the same result (e.g., list comprehensions).
*   **Quick File Handling:**
    *   **Goal:** Write a function to read a file and return only the long lines.
    *   **Collaboration:** Discuss how to handle potential errors, like the file not existing.

### 🚀 Code Challenge: Word Count

*   **Goal:** Write a function to count the frequency of words in a text file.
*   **Collaboration:** Encourage students to work together to break down the problem. They'll need to think about how to handle punctuation and capitalization.

## 📚 Additional Resources

*   [Python Data Structures](https://docs.python.org/3/tutorial/datastructures.html)
*   [Python File I/O](https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files)
*   [Python Modules](https://docs.python.org/3/tutorial/modules.html)
