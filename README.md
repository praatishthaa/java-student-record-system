This project is a **Command Line Interface (CLI)-based Student Record Management System** developed in **Java**. It is designed to demonstrate practical application of **Object-Oriented Programming (OOP)** principles and the **ArrayList** data structure to perform basic **CRUD** (Create, Read, Update, Delete) operations on student records.

The core of the system revolves around a `Student` class that encapsulates the properties of a student, including a unique `ID`, `name`, and `marks`. The class includes a constructor for initialization, getter and setter methods for accessing and modifying the data, and a `toString()` method to provide a readable representation of the student object.

In the main class (`StudentRecordSystem`), an `ArrayList<Student>` is used to store and manage the list of student records. The use of ArrayList allows dynamic resizing of the student database as entries are added or removed.

The program presents a user-friendly menu in the terminal with five options:

1. **Add Student** – Allows the user to input and add a new student record to the list.
2. **View Students** – Displays all student records currently in the system.
3. **Update Student** – Lets the user modify the name and marks of an existing student by providing their ID.
4. **Delete Student** – Removes a student record from the list based on the given ID.
5. **Exit** – Terminates the application.

User interaction is managed through the `Scanner` class for input collection. The program uses `loops` and `conditional statements` to navigate through the menu and perform the selected operations.

This project was created with the goal of gaining hands-on experience in:

* Structuring code using classes and objects
* Using Java collections for real-world data storage and manipulation
* Implementing basic input validation and control flow
* Building text-based interactive applications

It can be compiled and executed using any Java IDE such as **VS Code** or **IntelliJ IDEA Community Edition**. This project serves as a foundational exercise for students and beginners aiming to understand how backend logic and data handling works in Java-based applications.
