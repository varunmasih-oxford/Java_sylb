# Class 1: Introduction to Java & First Program

## Learning Objectives

- Understand what Java is.
- Understand JDK, JRE, and JVM.
- Install Java.
- Write and run their first Java program.
- Understand the structure of a Java program.
- Use `System.out.println()` to display output.

---

# 1. What is Java?

Java is a high-level, object-oriented programming language used to create:

- Desktop Applications
- Web Applications
- Mobile Apps (Android)
- Enterprise Software
- Banking Systems
- E-commerce Applications

---

# 2. Why Learn Java?

## Advantages of Java

- Easy to Learn
- Platform Independent
- Secure
- Object-Oriented
- Large Community Support
- High Demand in Industry

---

# 3. Java Architecture

## JDK
Java Development Kit

## JRE
Java Runtime Environment

## JVM
Java Virtual Machine

### Flow

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

```bash
java --version
javac --version
```

---

# 5. First Java Program

```java
public class Main {

    public static void main(String[] args) {

        System.out.println("Hello World");

    }

}
```

Output:

```text
Hello World
```

---

# 6. Understanding the Program

## Class

```java
public class Main
```

## Main Method

```java
public static void main(String[] args)
```

## Print Statement

```java
System.out.println("Hello World");
```

---

# 7. More Output Examples

```java
System.out.println("My Name is Varun");
```

```java
System.out.println("Welcome to Java");
System.out.println("This is Class 1");
```

---

# 8. Difference Between print() and println()

```java
System.out.print("Hello ");
System.out.print("World");
```

Output:

```text
Hello World
```

```java
System.out.println("Hello");
System.out.println("World");
```

Output:

```text
Hello
World
```

---

# 9. Common Errors

- File name must match class name.
- Missing semicolon.
- Incorrect capitalization.

---

# Practice Questions

1. Print your name.
2. Print your name and city on separate lines.
3. Print:
   Welcome
   To
   Java
   Programming
4. Use `print()` to display: I Love Java

---

# Assignment

## Program 1

Print:

```text
My Name is ______
I am Learning Java
```

## Program 2

Print:
- Name
- Age
- City
- Course Name

Each on a separate line.

---

# Key Points

- Java is an object-oriented programming language.
- Java uses JDK, JRE, and JVM.
- Every Java program starts from `main()`.
- `System.out.println()` is used to display output.
- Java is case-sensitive.
- File name and class name must match.

## Next Class

Variables, Data Types, and User Input in Java.
