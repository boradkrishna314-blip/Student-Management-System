Student Management System
To develop a console-based Student Management System in C++ that efficiently manages student records using file handling and menu-driven operations.

Key Features:
Add, update, delete, and display student information.
Use file handling to store data persistently.
Implement menu-driven operations for smooth navigation.
Expected Outcome:
A functional application that allows users to add, update, delete, and display student information with persistent data storage for reliable record management.

# Student Management System (C++ File Handling)

A console-based **Student Management System** built in C++ using Object-Oriented Programming (OOP) and file handling (`fstream`). This application performs full CRUD (Create, Read, Update, Delete) operations and persists student records locally in a text file.

## Features

- **Enter New Record:** Add student details including Name, Roll Number, Course, Email ID, Contact Number, and Address. Supports adding multiple records in a single session.
- **Display Record:** View all saved student records formatted in a structured console view.
- **Modify Record:** Search for a student by Roll Number and update their existing information.
- **Search Record:** Quickly retrieve and display a specific student's record using their Roll Number.
- **Delete Record:** Remove a student's record permanently from storage by Roll Number.

## Project Structure

```text
Student-Management-System-CPP/
├── studentPS.cpp        # Main C++ source code
├── studentRecord.txt    # Auto-generated text file storing student records
├── README.md            # Project documentation
└── .gitignore           # Git ignore rules for compiled binaries and runtime data
