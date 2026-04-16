# Matrix Operations Library (Assignment p1)

A generic Java Matrix class that supports common matrix operations with proper exception handling.

**Author:** DN MBOYI  
**Student Number:** 222019179  
**Assignment:** p1  
**Course:** CSC03B3 (Java Programming)

---

## Project Description

This project implements a fully functional **generic Matrix<T>** class that adheres to the `IMatrix<T>` interface. It supports operations on matrices containing `Integer` or `Double` values.

### Key Features

- **Generic Matrix Class** (`Matrix<T>`) implementing `IMatrix<T>`
- Support for both `Integer` and `Double` element types
- Matrix addition (`addMatrix`)
- Scalar addition (`addScalar`)
- Scalar multiplication (`multiplyScalar`)
- Matrix multiplication (`multiplyMatrix`)
- Matrix transpose
- Row and column extraction (`getRow`, `getCol`)
- Element access (`getElement`)
- Proper bounds checking with custom `MatrixException`
- Clean `toString()` representation

---

## Files Included

- `Matrix.java` – Main implementation of the Matrix class
- `IMatrix.java` – Interface defining all matrix operations
- `MatrixException.java` – Custom checked exception
- `Main.java` – Test class (currently commented)
- `JAR File.jar` – Executable JAR with all compiled classes
- Generated Javadoc documentation (`doc/` folder)

---

## Technologies Used

- **Java** (Generics, Exception Handling)
- **Object-Oriented Programming**
- **Javadoc** documentation
- **Eclipse IDE** project structure

---

## How to Run

### Option 1: Using the JAR File (Easiest)
```bash
java -jar "JAR File.jar"
