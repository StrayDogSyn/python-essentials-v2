# Week 5 Instructor Guide: Data Cleaning and Validation

## 🎯 Weekly Learning Objectives

By the end of this week, students will be able to:

*   Validate data types and ranges.
*   Clean strings and handle missing values.
*   Use `re` and `datetime` from the standard library.

## Session 1: Data Cleaning and Validation (One-on-One)

### 🧹 Data Cleaning and Validation

*   **Talking Point:** Start by explaining that data cleaning and validation are essential steps in any data analysis or machine learning project. Use the analogy of a chef preparing ingredients before cooking a meal.

### ✔️ Type and Range Validation

*   **Key Concepts:** Writing functions to validate data types and ensure that values are within an acceptable range.
*   **Activity:** Have the student write a function to validate a score, ensuring that it is an integer between 0 and 100.

### 🧼 String Cleaning

*   **Key Concepts:** Using string methods and regular expressions to clean up messy text data.
*   **Activity:** Have the student write a function to clean up a sentence with extra whitespace.

### 📅 Datetime Parsing

*   **Key Concepts:** Using the `datetime` module to parse and format dates and times.
*   **Activity:** Have the student write a function to parse dates in a specific format, with error handling for invalid formats.

### ❓ Missing Values Handling

*   **Key Concepts:** Strategies for dealing with missing data, such as imputation and removal.
*   **Activity:** Have the student write a function to convert a list of strings to integers, with a default value for missing or invalid data.

## Session 2: Data Cleaning and Validation (Group)

### 🤔 Review

*   **Discussion Point:** Start with a quick review of the concepts from the one-on-one session.

### 📝 Activities

*   **Field Validators:**
    *   **Goal:** Write functions to validate different fields in a dataset.
    *   **Collaboration:** Discuss how to combine multiple validation functions into a single pipeline.
*   **Validation Report:**
    *   **Goal:** Generate a report of validation errors.
    *   **Collaboration:** Discuss how to make the report more informative and user-friendly.

### 🚀 Code Challenge: Messy CSV Cleaner

*   **Goal:** Build a pipeline to clean and validate a "messy" CSV file.
*   **Collaboration:** Encourage students to work together to design the pipeline and divide up the work.

## 📚 Additional Resources

*   [An Introduction to Data Cleaning with Python](https://realpython.com/python-data-cleaning-numpy-pandas/)
*   [Python `re` module for regular expressions](https://docs.python.org/3/library/re.html)
*   [Python `datetime` module](https://docs.python.org/3/library/datetime.html)
