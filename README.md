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

<img width="647" height="403" alt="image" src="https://github.com/user-attachments/assets/fd49de29-ecd2-4d56-bc5c-d5beadd95700" />

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
    
<img width="1254" height="522" alt="image" src="https://github.com/user-attachments/assets/86db0940-901c-4c33-aed5-571d4c0925cc" />


<img width="970" height="581" alt="image" src="https://github.com/user-attachments/assets/f0ea8969-9e06-49ac-8e8f-055e8a2565ad" />

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



---


<img width="789" height="585" alt="image" src="https://github.com/user-attachments/assets/c6776dc2-cdbe-497e-b6d8-2eb6af11fa4d" />

<img width="768" height="640" alt="image" src="https://github.com/user-attachments/assets/9c76d4a6-e878-445b-ad8f-dc1cd6e30fd8" />
