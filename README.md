# Campus Course & Records Manager (CCRM)

## Project Overview

The Campus Course & Records Manager (CCRM) is a console-based Java application designed to manage students, courses, enrollments, and grades for an educational institute. This project demonstrates core and advanced Java SE concepts, including Object-Oriented Programming (OOP), file I/O with NIO.2, the Stream API, and common design patterns.

---

## 1. Evolution of Java

Java has evolved significantly since its inception. Here are some key milestones:
- **1995**: Sun Microsystems releases Java 1.0, introducing the "Write Once, Run Anywhere" philosophy.
- **2004**: Java 5 (J2SE 5.0), codenamed "Tiger," is released, bringing major language additions like Generics, Enums, Annotations, and the `for-each` loop.
- **2014**: Java 8 is a revolutionary release, introducing Lambda Expressions, the Stream API for data processing, and a new Date and Time API.
- **2018**: Java 11 is released as the second Long-Term Support (LTS) version after Java 8, solidifying features from versions 9 and 10.
- **2021**: Java 17 becomes the next LTS release, bringing further enhancements like Sealed Classes and Pattern Matching for `instanceof`.

---

## 2. Java Platform Comparison: ME vs. SE vs. EE

Java is available in three main editions, each targeting different application domains.

| Feature           | Java ME (Micro Edition)             | Java SE (Standard Edition)          | Java EE (Enterprise Edition)       |
| ----------------- | ----------------------------------- | ----------------------------------- | ---------------------------------- |
| **Primary Use** | Mobile devices, embedded systems    | Desktop & server applications       | Large-scale, distributed web apps  |
| **Core API** | A subset of the Java SE API         | The core Java programming platform  | Extends Java SE with more APIs     |
| **Key Features** | Small memory footprint, low power   | JDK, JRE, JVM, core libraries       | Servlets, Web Services (JAX-RS)    |
| **Example App** | Older mobile games, smart cards     | This CCRM project, desktop apps     | Online banking, e-commerce sites   |

---

## 3. Java Architecture: JDK, JRE, and JVM

Understanding Java's architecture is key to understanding how it works.

-   **JVM (Java Virtual Machine)**: The JVM is an abstract computing machine that enables a computer to run a Java program. It interprets the compiled Java bytecode and executes it. The JVM is the component that makes Java platform-independent.

-   **JRE (Java Runtime Environment)**: The JRE is the software package that provides the Java class libraries, the JVM, and other components necessary to *run* Java applications. If you only want to run a Java program, you only need the JRE.

-   **JDK (Java Development Kit)**: The JDK is a full-featured software development kit for Java. It includes everything in the JRE, plus development tools like the compiler (`javac`) and debugger. You need the JDK to *write and compile* Java code.

**How they interact:** You use the **JDK** to write and compile your code into bytecode. That bytecode can then be run on any machine that has a **JRE** installed. The **JRE**'s **JVM** is what actually executes the code.
