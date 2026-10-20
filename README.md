# Oops

# Task 4: C++ OOP and STL Mini Project

## Project Title
Library Management System



## Objective
The objective of this project is to develop a small C++ application using object-oriented programming, STL containers, and file handling.

The Library Management System manages book records and demonstrates how C++ classes and file persistence can be used in a practical application.

## Features
- Add new books
- Display all books
- Search for books
- Issue books
- Return books
- Save book records to a file
- Load saved records when the program starts

## Concepts Used
- Classes and Objects
- Encapsulation
- Object-Oriented Programming (OOP)
- STL containers, such as `vector`
- File input/output using `fstream`
- Conditional statements and loops
- Functions and modular programming

## Technologies Used
- Programming Language: C++
- Compiler: GCC/G++
- Standard: C++17
- Version Control: Git and GitHub

## Project Structure

```text
task-4-library-management/
├── library_management.cpp
├── books.txt
├── README.md
├── Makefile
└── Task_4_CPP_Project_Report_Sohail_Khan.pdf
```

## How to Compile and Run

Compile the program:

```bash
g++ -std=c++17 -Wall -Wextra -pedantic library_management.cpp -o library_app
```

Run on Linux/macOS:

```bash
./library_app
```

On Windows:

```bash
library_app.exe
```

## Data Storage
The application uses a text file named `books.txt` to store book information.

Example data format:

```text
101|C++ Basics|A. Student|0
102|Data Structures|B. Student|1
```

In this example:
- `0` represents an available book.
- `1` represents an issued book.

The exact file format depends on the implementation.

## Testing
The following cases should be tested:
1. Add and display a new book.
2. Search for an existing book.
3. Search for a book that does not exist.
4. Attempt to add a duplicate book ID.
5. Issue and return a book.
6. Restart the application and verify saved records.
7. Handle missing or invalid data files.

## Files Included
- `library_management.cpp` - Main source code
- `books.txt` - Sample book data, if included
- `README.md` - Project documentation
- `Makefile` - Build instructions, if included
- `Task_4_CPP_Project_Report_Sohail_Khan.pdf` - Detailed task report

## Conclusion
This project demonstrates the practical use of classes, encapsulation, STL containers, and file handling in C++. It provides a foundation for developing small, organized, and maintainable application
