# To-Do Manager with Deadlines (Java Console Application)

The "To-Do Manager with Deadlines" is a Java-based console application designed to help users efficiently organize and track their daily tasks. The system allows users to create tasks with a title, description, and deadline, while maintaining each task's status as either pending or completed. Built using object-oriented programming principles, the application separates functionality into clearly defined packages for better modularity and maintainability. The TaskService component handles all core logic such as adding, listing, sorting, updating, and deleting tasks, while the Task class represents the task data model. To ensure persistence, all tasks are stored in a simple text file and automatically loaded at startup. The program uses an ASCII-only menu interface to ensure compatibility across all terminal environments. This project demonstrates core Java concepts, including classes, objects, packages, file handling, exception handling, and collection manipulation, making it a practical and beginner-friendly task management solution.
------------------------------------------------------------

## Requirements

- Java Development Kit (JDK 8 or above)
- Any terminal (CMD, PowerShell, etc.)

------------------------------------------------------------

## How to Compile
javac -d out src/objects/.java src/manager/.java src/app/TodoApp.java

## How to Run
java -cp out app.TodoApp

------------------------------------------------------------

## Concepts Used

- Classes and Objects
- Packages
- ArrayList
- File Handling (Java IO)
- Exception Handling
- Comparator Sorting
- Basic Layered Architecture

------------------------------------------------------------

## Future Enhancements

- Task priority levels
- Overdue task detection
- Edit existing tasks
- Search tasks
- CSV export
- GUI version using JavaFX

------------------------------------------------------------

## Author

Name: Nivedit Awasthi  (22BME10012)
Project: To-Do Manager with Deadlines  

