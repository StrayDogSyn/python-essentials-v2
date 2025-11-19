# Week 4 Instructor Guide: Intro to Data Engineering

## 🎯 Weekly Learning Objectives

By the end of this week, students will be able to:

*   Use the filesystem via `pathlib` and `os`.
*   Read and write CSV and JSON using the standard library.
*   Build small data pipelines with pure Python.

## Session 1: Intro to Data Engineering (One-on-One)

### 📂 Filesystem Basics

*   **Key Concepts:** The `pathlib` module for object-oriented filesystem paths.
*   **Activity:** Have the student create a directory and list its contents.

### 📝 CSV Read/Write (stdlib)

*   **Key Concepts:** The `csv` module for reading and writing CSV files.
*   **Activity:** Have the student read a CSV file and filter the data based on a condition.

### 📄 JSON Read/Write (stdlib)

*   **Key Concepts:** The `json` module for working with JSON data.
*   **Activity:** Have the student load a JSON file, modify it, and write it back.

### 🛠️ Mini Pipeline

*   **Key Concepts:** The concept of a data pipeline (extract, transform, load).
*   **Activity:** Have the student build a simple pipeline that reads, cleans, and writes data.

## Session 2: Intro to Data Engineering (Group)

### 🤔 Review

*   **Discussion Point:** Start with a quick review of the concepts from the one-on-one session.

### 📝 Activities

*   **JSON Lines to CSV:**
    *   **Goal:** Convert a JSON Lines file to a CSV file, filtering the data in the process.
    *   **Collaboration:** Discuss the pros and cons of JSON Lines as a file format.
*   **Directory Processing:**
    *   **Goal:** Process all the files in a directory and aggregate the results.
    *   **Collaboration:** Discuss how to handle different file formats and potential errors.

### 🚀 Code Challenge: JSON to CSV Pipeline

*   **Goal:** Build a pipeline that reads multiple JSON files, combines the data, and writes it to a single CSV file.
*   **Collaboration:** Encourage students to work together to design the pipeline and divide up the work.

## 📚 Additional Resources

*   [pathlib — Object-oriented filesystem paths](https://docs.python.org/3/library/pathlib.html)
*   [csv — CSV File Reading and Writing](https://docs.python.org/3/library/csv.html)
*   [json — JSON encoder and decoder](https://docs.python.org/3/library/json.html)
