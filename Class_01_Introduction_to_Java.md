# Class 1: Introduction to Java & First Program

## Learning Objectives

By the end of this class, students will be able to:

* Understand what Java is.
* Understand JDK, JRE, and JVM.
* Install Java.
* Write and run their first Java program.
* Understand the structure of a Java program.
* Use `System.out.println()` to display output.

---

# 1. What is Java?

Java is a **high-level, object-oriented programming language** used to create:

* Desktop Applications
* Web Applications
* Mobile Apps (Android)
* Enterprise Software
* Banking Systems
* E-commerce Applications

## Popular Applications Built Using Java

* Amazon
* Netflix
* LinkedIn

---

# 2. Why Learn Java?

## Advantages of Java

 Easy to Learn

 Platform Independent

 Secure

 Object-Oriented

 Large Community Support

 High Demand in Industry

---

# 3. Java Architecture

## JDK

**Java Development Kit**

Used by developers to create Java applications.

Contains:

* JRE
* Compiler (`javac`)
* Development Tools

### JRE

**Java Runtime Environment**

Used to run Java programs.

Contains:

* JVM
* Libraries

### JVM

**Java Virtual Machine**

Responsible for executing Java programs.

## Simple Flow

```text
Java Code
    ↓
Compiler (javac)
    ↓
Bytecode
    ↓
JVM
    ↓
Output
```

---

# 4. Install Java

## Check Installation

```bash
java --version
javac --version
```

### Example Output

```text
java 21
javac 21
```

---

# 5. First Java Program

Create a file named:

```text
Main.java
```

Write the following code:

```java
public class Main {

    public static void main(String[] args) {

        System.out.println("Hello World");

    }

}
```

### Output

```text
Hello World
```

---

# 6. Understanding the Program

## Class

```java
public class Main
```

A class is a blueprint for creating objects.

Here:

* `public` → Accessible from anywhere
* `class` → Keyword to create a class
* `Main` → Class Name

## Main Method

```java
public static void main(String[] args)
```

This is the starting point of every Java program.

Java starts execution from the `main()` method.

## Print Statement

```java
System.out.println("Hello World");
```

Used to display output on the screen.

---

# 7. More Output Examples

## Example 1

```java
public class Main {

    public static void main(String[] args) {

        System.out.println("My Name is Varun");

    }

}
```

### Output

```text
My Name is Varun
```

## Example 2

```java
public class Main {

    public static void main(String[] args) {

        System.out.println("Welcome to Java");
        System.out.println("This is Class 1");

    }

}
```

### Output

```text
Welcome to Java
This is Class 1
```

---

# 8. Difference Between print() and println()

## print()

```java
System.out.print("Hello ");
System.out.print("World");
```

### Output

```text
Hello World
```

## println()

```java
System.out.println("Hello");
System.out.println("World");
```

### Output

```text
Hello
World
```

---

# 9. Common Errors

## File Name Must Match Class Name

### Correct

```java
public class Main
```

File Name:

```text
Main.java
```

---

## Missing Semicolon

### Wrong

```java
System.out.println("Hello")
```

### Correct

```java
System.out.println("Hello");
```

---

## Incorrect Capitalization

### Wrong

```java
system.out.println("Hello");
```

### Correct

```java
System.out.println("Hello");
```

Java is **case-sensitive**.

---

# Class Practice Questions

## Q1

Print your name.

### Expected Output

```text
Varun
```

---

## Q2

Print your name and city on separate lines.

### Example Output

```text
Varun
Delhi
```

---

## Q3

Print the following:

```text
Welcome
To
Java
Programming
```

---

## Q4

Use `print()` to display:

```text
I Love Java
```

---

# Assignment

## Program 1

Print:

```text
My Name is ______
I am Learning Java
```

## Program 2

Print your:

* Name
* Age
* City
* Course Name

Each on a separate line.

---

# Key Points to Remember

* Java is an object-oriented programming language.
* Java uses JDK, JRE, and JVM.
* Every Java program starts from `main()`.
* `System.out.println()` is used to display output.
* Java is case-sensitive.
* File name and class name must match.

---

# Next Class

## Variables, Data Types, and User Input in Java
