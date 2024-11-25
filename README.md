# Library Management System

This project is a simple **Library Management System** implemented in Java. It allows users to manage books and students within a library system, offering functionality such as adding books, registering students, checking in/out books, and more.

## Project Structure

The project consists of the following classes:

1. **`book`**:
   - Represents a single book in the library.
   - Allows adding details such as serial number, book name, author name, and quantity.
   - Handles book quantity management.

2. **`books`**:
   - Manages a collection of books in the library.
   - Provides features to add, search, display, check-in, and check-out books.

3. **`student`**:
   - Represents a single student.
   - Contains details such as name and registration number.
   - Keeps track of books borrowed by the student.

4. **`students`**:
   - Manages a collection of students.
   - Provides features to add students, display registered students, and handle borrowing/returning books.

5. **`library`**:
   - Acts as the entry point to the application.
   - Provides a menu-driven interface for managing library operations.

## Features

- **Books Management**:
  - Add new books to the library.
  - Search books by serial number or author name.
  - Display all available books.
  - Check-in and check-out books.
  
- **Students Management**:
  - Register new students.
  - Display all registered students.
  - Allow students to borrow up to 3 books.

## How to Run

1. Compile the `.java` files:
   ```bash
      javac Project/*.java
   ```
