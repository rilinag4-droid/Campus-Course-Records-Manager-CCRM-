# Campus Course & Records Manager (CCRM)

## Project Overview

This project, the Campus Course & Records Manager (CCRM), is a console-based application built with Java. It's designed to handle essential academic records for a small institute, covering everything from student and course management to enrollment and grading. The goal is to build a robust application that showcases a strong understanding of Java's core principles and advanced features.

***

## 1. Evolution of Java

Java wasn't built in a day. It has a rich history of updates that have kept it modern and powerful.

* **1995**: Java 1.0 was released by Sun Microsystems. Its big promise was "Write Once, Run Anywhere."
* **2004**: Java 5 was a massive update. It gave us key features we use all the time, like Generics, Enums, and the enhanced `for-each` loop.
* **2014**: Java 8 changed the game again by introducing Lambda Expressions and the Stream API, making code much cleaner and more functional.
* **2018**: Java 11 became the next Long-Term Support (LTS) version, providing stability for enterprise users.
* **2021**: Java 17 arrived as the latest LTS, adding modern features like Sealed Classes and improved Pattern Matching.

***

## 2. Java Platform Comparison: ME vs. SE vs. EE

Java comes in three main flavors, each for a different purpose.

| Aspect        | Java ME (Micro Edition)          | Java SE (Standard Edition)              | Java EE (Enterprise Edition)       |
| ------------- | -------------------------------- | --------------------------------------- | ---------------------------------- |
| **Target** | Small, resource-limited devices  | General desktop and server applications | Large-scale, distributed web systems |
| **Core API** | A small subset of Java SE's API  | The fundamental Java platform (core API)  | Builds on top of Java SE with more APIs |
| **Typical Use** | Old mobile phones, embedded systems | This project, desktop apps like IntelliJ | Online banking sites, e-commerce platforms |

***

## 3. Java Architecture: JDK, JRE, and JVM

These three acronyms are the foundation of the Java platform. Here’s how they fit together.

* **JVM (Java Virtual Machine)**
    This is the engine that actually runs Java code. It takes the compiled Java bytecode and translates it for the underlying operating system. The JVM is what makes Java platform-independent.

* **JRE (Java Runtime Environment)**
    The JRE is the package you need to *run* Java applications. It includes the JVM and the core Java libraries, but not the development tools.

* **JDK (Java Development Kit)**
    The JDK is the full package for developers. It contains everything in the JRE, plus the tools needed to *write* and *compile* Java code, like the compiler (`javac`).

**In short:** You use the **JDK** to build your application. To run it, your users only need the **JRE**, which uses its **JVM** to execute the program.
