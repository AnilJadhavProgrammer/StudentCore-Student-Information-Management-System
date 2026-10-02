# StudentCore — Student Information Management System

StudentCore is a desktop-based **Student Information Management System** developed using Python and SQLite. The application provides a simple graphical interface for managing student records and performing common database operations.

The system allows users to add, search, update, delete, display, and clear student information through an easy-to-use Tkinter interface.

## Features

* Add new student records
* Search existing student records
* Update student information
* Delete student records
* Display stored student records
* Clear input fields
* Exit confirmation dialog
* SQLite-based data storage
* Student ID used as the primary key

## Student Information

The system stores the following information:

| Field         | Description                       |
| ------------- | --------------------------------- |
| Student ID    | Unique identifier and Primary Key |
| Student Name  | Name of the student               |
| Age           | Student's age                     |
| Gender        | Student's gender                  |
| Address       | Student's address                 |
| Mobile Number | Student's contact number          |

## Application Workflow

```text
                StudentCore
                    │
                    ▼
          Tkinter Graphical Interface
                    │
        ┌───────────┼───────────┐
        ▼           ▼           ▼
       Add        Search       Display
        │           │           │
        └───────────┼───────────┘
                    ▼
              SQLite Database
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
       Update     Delete     Clear
                    │
                    ▼
                   Exit
```

## Technologies Used

* **Programming Language:** Python 3
* **Database:** SQLite 3
* **GUI Library:** Tkinter
* **Programming Concepts:** Object-Oriented Programming (OOP)
* **Database Operations:** CRUD Operations

## CRUD Operations

The application implements the basic CRUD operations:

* **Create** — Add new student records
* **Read** — Display and search student records
* **Update** — Modify existing student information
* **Delete** — Remove student records

## Database Design

The **Student ID** is used as the **Primary Key**, ensuring that each student record has a unique identifier.

```text
Student
│
├── Student ID       → Primary Key
├── Student Name
├── Age
├── Gender
├── Address
└── Mobile Number
```

## User Interface

The application provides buttons for performing different operations:

| Operation | Description                              |
| --------- | ---------------------------------------- |
| Add New   | Adds a new student record                |
| Clear     | Clears the input fields                  |
| Search    | Searches for relevant student records    |
| Update    | Updates an existing student record       |
| Delete    | Deletes the selected student record      |
| Display   | Displays stored student records          |
| Exit      | Closes the application with confirmation |

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/AnilJadhavProgrammer/Student-Database-Management-System.git
```

### 2. Navigate to the project directory

```bash
cd Student-Database-Management-System
```

### 3. Run the Python application

```bash
python main.py
```

> Replace `main.py` with the actual Python entry-point filename if your project uses a different file name.

## Project Structure

```text
Student-Database-Management-System/
│
├── Student-Database-Management-System-master/
│   └── Student-Database-Management-System-master/
│       ├── Python source files
│       ├── SQLite database
│       └── Other project files
│
└── README.md
```

## Key Concepts Demonstrated

* Python Programming
* SQLite Database Management
* CRUD Operations
* Object-Oriented Programming
* GUI Development
* Database Connectivity
* Primary Keys
* SQL Queries
* Event-driven Programming

## Learning Outcomes

Through this project, I gained practical experience in developing a database-driven desktop application using Python. The project helped me understand how a graphical user interface interacts with a relational database to perform CRUD operations.

## Future Enhancements

* User authentication and login
* Input validation
* Improved search and filtering
* Student record export
* Database backup and restore
* Improved UI design
* Additional student fields and reporting features

## Author

**Anil Jadhav**

GitHub: [AnilJadhavProgrammer](https://github.com/AnilJadhavProgrammer)

## License

This project is developed for educational and learning purposes.
