# Week 3 Instructor Guide: More Python Skills

## 🎯 Weekly Learning Objectives

By the end of this week, students will be able to:

*   Practice list comprehensions and lambdas.
*   Handle exceptions and use context managers.
*   Write and import simple modules.
*   Use generators and iterators.

## Session 1: More Python Skills (One-on-One)

### 🚀 List Comprehensions

*   **Key Concepts:** A concise and readable way to create lists.
*   **Activity:** Have the student write a list comprehension to filter and transform a list of strings.

### 🛡️ Exceptions and Context Managers

*   **Key Concepts:** Using `try...except` to handle errors and the `with` statement to manage resources.
*   **Activity:** Have the student wrap a file reading operation in a `try...except` block to handle a potential `FileNotFoundError`.

### ⚙️ Generators

*   **Key Concepts:** A memory-efficient way to create iterators.
*   **Activity:** Have the student write a generator function that yields values from a list based on a condition.

### 📦 Modules

*   **Key Concepts:** How to create and import your own modules.
*   **Activity:** Simulate creating and importing a module within the Jupyter notebook.

## Session 2: More Python Skills (Group)

### 🤔 Review

*   **Discussion Point:** Start with a quick review of the concepts from the one-on-one session.

### 📝 Activities

*   **Refactor to Comprehensions:**
    *   **Goal:** Refactor a `for` loop into a list comprehension.
    *   **Collaboration:** Discuss the readability and performance benefits of list comprehensions.
*   **Resilient Exception Handling:**
    *   **Goal:** Write a `try...except` block that handles different types of exceptions.
    *   **Collaboration:** Discuss how to make the error handling more specific and informative.
*   **Generators and Modules:**
    *   **Goal:** Simulate importing a generator function from another cell.
    *   **Collaboration:** Discuss the benefits of organizing code into modules.

### 🚀 Code Challenge: Log File Parser

*   **Goal:** Write a generator function to parse a log file.
*   **Collaboration:** Encourage students to work together to break down the problem. They'll need to think about how to handle different log formats and potential errors.

## 📚 Additional Resources

*   [Python List Comprehensions](https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions)
*   [Python Errors and Exceptions](https://docs.python.org/3/tutorial/errors.html)
*   [Python Generators](https://wiki.python.org/moin/Generators)
