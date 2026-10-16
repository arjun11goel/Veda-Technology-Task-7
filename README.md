# Student Information Dictionary

## Description

This project is a Python-based Jupyter Notebook designed to practice using dictionaries and structured data representation. It implements a simple "Student Database" where student records are stored as nested dictionaries using unique Student IDs as keys.

## Features

* **Add:** Insert new student records (Name, Age, Major) while preventing duplicate IDs.
* **Update:** Modify existing student information (e.g., updating just the age or major).
* **Search:** Retrieve and display a student's full record using their unique Student ID.

## Example Output Results

Running the operations in the notebook yields the following results:

```text
--- Testing Add Operation ---
Success: Student 'Diana Prince' added with ID 'S104'.
Error: Student ID 'S101' already exists.

--- Testing Update Operation ---
Success: Student ID 'S102' has been updated.

--- Testing Search Operation ---
--- Student Record: S102 ---
Name:  Bob Jones
Age:   23
Major: Applied Mathematics
------------------------------
--- Student Record: S104 ---
Name:  Diana Prince
Age:   21
Major: History
------------------------------
Search Failed: Student ID 'S999' not found.
```

## Interview Questions & Answers

* **What is a dictionary in Python?**
  A dictionary is a built-in Python data structure that stores data in key-value pairs. It is mutable, unordered (though insertion order is preserved in modern Python versions), and indexed by keys.
  
* **Why are keys important in dictionaries?**
  Keys act as unique identifiers for the values stored in a dictionary. They allow for rapid, highly efficient data retrieval, updating, and deletion without needing to iterate through the entire structure.
  
* **How is a dictionary different from a list?**
  Lists are ordered collections of items accessed by their numerical index (e.g., `list[0]`). Dictionaries are collections of key-value pairs accessed by unique keys (e.g., `dict['student_id']`). Lists are ideal for ordered sequences, while dictionaries are ideal for structured associations and fast lookups.

## How to Run

1. Ensure you have Python and Jupyter Notebook installed.
2. Open `Student_Information_Dictionary.ipynb` in Jupyter Notebook.
3. Run the cells sequentially from top to bottom.

## Technologies Used

* Python 3
* Jupyter Notebook
