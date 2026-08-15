
זה כבר מציג את הפרויקט כמו שצריך, במקום שלוש שורות שלא מסבירות כמעט כלום.

תעשה **Commit changes**, ואז נעבור לניקוי של `.idea` וקבצים שלא כדאי להשאיר בריפו. # Java Library Management System


A Java-based library management application with a graphical user interface.


The project demonstrates object-oriented programming, layered architecture, service-based logic, lending workflows, Maven project structure, and GUI development with Java Swing.


## Features


- Add and manage books
- Add and manage library members
- Borrow books
- Return books
- Support for multiple book types
- Track active loans
- Display library information through a graphical interface
- Sample data for demonstration and testing


## Book Types


The system supports multiple book categories:


- Fiction
- Non-Fiction
- Reference


## Technologies


- Java
- Java Swing
- Maven
- Object-Oriented Programming
- Design Patterns
- JUnit
- UML


## Project Structure


```text
src/
├── main/java/library/
│   ├── gui/
│   ├── model/
│   ├── service/
│   ├── util/
│   └── LibrarySystem.java
│
└── test/java/library/
Architecture

The project separates responsibilities into several layers:

Model

Contains the core domain entities, including:

Book
Member
Loan
LibrarySummary
Service

Contains the application logic and library-management operations.

The LibraryManager is responsible for coordinating actions such as adding books and members, borrowing books, and managing library data.

GUI

The graphical interface is implemented using Java Swing.

The application launches the GUI from the main LibrarySystem entry point.

Design

The project uses object-oriented design principles and includes a Singleton-style LibraryManager used as the central service for managing application state.

Example Workflow

The application can:

Add books to the library
Add members
Borrow a book using a book ID and member ID
Return borrowed books
Display and manage data through the GUI
Running the Project

Make sure Java and Maven are installed.

Clone the repository:

git clone https://github.com/adisasportas/Java-Library-Management-System.git

Navigate to the project directory:

cd Java-Library-Management-System/Library

Build the project:

mvn clean install

Run the application from the LibrarySystem main class.

What This Project Demonstrates
Java OOP
Class inheritance and abstraction
Separation of concerns
Service-layer architecture
GUI development with Swing
Maven project management
Software modeling with UML
Unit testing
Library lending workflows
Author

Adi Sasportas

Practical Software Engineer focused on Java and Full-Stack Development.
