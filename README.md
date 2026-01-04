# JAVA_CORE

<img width="948" height="622" alt="image" src="https://github.com/user-attachments/assets/91a06e3e-5763-4c62-8a31-dafde715af63" />

---

#  CORE JAVA – DAY 1

## Java Fundamentals 

## What is Java?

**Java** is a **high-level, object-oriented, platform-independent programming language** developed by **Sun Microsystems (1995)** and now maintained by **Oracle**.

### Why Java?

* Platform Independent
* Object-Oriented
* Secure
* Robust
* Scalable
* Used in:

  * Web Applications
  * Enterprise Applications
  * Android Development
  * Banking & Financial Systems

---

##  Features of Java

1. **Simple** – Easy syntax compared to C++
2. **Object-Oriented** – Everything revolves around objects
3. **Platform Independent** – Write Once, Run Anywhere
4. **Secure** – No pointers, bytecode verification
5. **Robust** – Strong memory management & exception handling
6. **Multithreaded** – Supports multiple tasks at once
7. **High Performance** – Uses JIT compiler
8. **Distributed** – Supports networking

---

##  Java Editions

| Edition | Description               |
| ------- | ------------------------- |
| Java SE | Core Java (Fundamentals)  |
| Java EE | Enterprise Applications   |
| Java ME | Mobile & Embedded Systems |

 **In JFS, we start with Java SE (Core Java)**

---

##  Java Architecture 

### JDK vs JRE vs JVM

####  JDK (Java Development Kit)

* Used by developers
* Contains:

  * JRE
  * Compiler (javac)
  * Development tools

#### JRE (Java Runtime Environment)

* Used to run Java programs
* Contains:

  * JVM
  * Core libraries

#### JVM (Java Virtual Machine)

* Executes bytecode
* Converts `.class` file into machine code
* Provides:

  * Memory management
  * Garbage Collection
  * Security



---

##  Environment Setup

### Steps:

1. Install JDK (8 or 17 recommended)
2. Set Environment Variables

   * `JAVA_HOME`
   * `PATH`
3. Verify:

```bash
java -version
javac -version
```

---

##  First Java Program

```java
class JSFDay1 {
    public static void main(String[] args) {
        System.out.println("Java Full Stack day 1 ");
    }
}
```

---

##  Java Program Execution Flow


1. Write code → `JSFDay1.java`
2. Compile → `javac JSFDay1.java`
3. Bytecode generated → `Hello.class`
4. JVM loads bytecode
5. JVM executes program

<img width="654" height="585" alt="image" src="https://github.com/user-attachments/assets/5bb2b22a-db15-4875-ac74-51a9beec6a97" />

 This is why Java is **platform independent**

### Explanation:

* `class` → Blueprint
* `JSFDay1` → Class name (same as file name)
* `main()` → Entry point of program
* `public` → Accessible everywhere
* `static` → No object required
* `void` → No return value
* `String[] args` → Command line arguments
* `System.out.println()` → Print output

---
