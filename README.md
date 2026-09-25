# StudentDatabaseApplication

A simple Java-based Student Database Application for managing student information. This project was created as a beginner-level Java application to practice object-oriented programming, classes, objects, methods, and basic application structure.

## Purpose

The purpose of this application is to provide a simple way to manage student records.

The project demonstrates fundamental Java programming concepts such as:

* Creating and working with classes and objects
* Encapsulation
* Constructors
* Methods
* Managing student information
* Basic application flow
* Maven project structure

## Technologies Used

* **Java** — Programming language
* **Maven** — Build and dependency management
* **Git** — Version control
* **GitHub** — Source code hosting
* **IntelliJ IDEA** — Development environment

## Project Structure

```text
StudentDatabaseApplication/
│
├── src/
│   └── main/
│       └── java/
│           ├── org/
│           │   └── example/
│           │       └── Main.java
│           │
│           └── studentdatabaseapp/
│               ├── Student.java
│               └── StudentDatabaseApp.java
│
├── pom.xml
├── .gitignore
└── README.md
```

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/Nuel145/StudentDatabaseApplication.git
```

### 2. Navigate into the project

```bash
cd StudentDatabaseApplication
```

### 3. Verify Java installation

Make sure Java is installed:

```bash
java -version
```

You should see your installed Java version.

### 4. Verify Maven installation

Run:

```bash
mvn -version
```

If Maven is installed correctly, it will display the Maven and Java versions.

## How to Run

### Using Maven

From the project directory, run:

```bash
mvn clean compile
```

This compiles the project and checks that the source code builds successfully.

You can then run the application from your IDE.

### Using IntelliJ IDEA

1. Open IntelliJ IDEA.
2. Select **Open**.
3. Choose the `StudentDatabaseApplication` folder.
4. Allow IntelliJ IDEA to load the Maven project.
5. Navigate to:

```text
src/main/java/studentdatabaseapp/StudentDatabaseApp.java
```

6. Right-click `StudentDatabaseApp.java`.
7. Select **Run 'StudentDatabaseApp.main()'**.

## Features

The application currently focuses on basic student database functionality, including:

* Creating student records
* Storing student information
* Displaying student information
* Working with multiple student objects

## Learning Objectives

This project was developed to strengthen my understanding of Java fundamentals and object-oriented programming.

Key concepts practiced include:

* Classes and Objects
* Constructors
* Encapsulation
* Instance variables
* Methods
* Object creation
* Java project organization
* Maven
* Git and GitHub

## Future Improvements

Possible future improvements include:

* Adding a graphical user interface (GUI)
* Adding a database such as MySQL or PostgreSQL
* Adding student search functionality
* Adding update and delete operations
* Adding input validation
* Adding unit tests
* Adding REST API functionality
* Connecting the application to a frontend

## Author

**Nuel145**

GitHub:
https://github.com/Nuel145

## License

This project is currently intended for learning and educational purposes.
