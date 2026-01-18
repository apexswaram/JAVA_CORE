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


<img width="886" height="319" alt="image" src="https://github.com/user-attachments/assets/f67cb7d5-727b-48a0-9d2c-84e6fbc7ce8d" />
<img width="894" height="708" alt="image" src="https://github.com/user-attachments/assets/e8eb6935-5c30-4fe9-a316-cb8332f8130b" />

<img width="764" height="390" alt="image" src="https://github.com/user-attachments/assets/2061e4f0-84f2-40a8-a946-9b97d614cced" />

<img width="808" height="571" alt="image" src="https://github.com/user-attachments/assets/c3d4cd49-f693-409d-8aca-e662ed2bcab3" />

<img width="879" height="577" alt="image" src="https://github.com/user-attachments/assets/eeefff43-01a3-45fe-b12a-15aee5cb05c0" />

<img width="854" height="546" alt="image" src="https://github.com/user-attachments/assets/400f6502-7dc4-4cee-a1b7-ee4c12b6a811" />
<img width="928" height="601" alt="image" src="https://github.com/user-attachments/assets/8ba6b6e2-7f8e-4fb7-92bc-a4c7d6f3324d" />
<img width="872" height="560" alt="image" src="https://github.com/user-attachments/assets/f7fdc6c5-4d09-4f6b-9c3f-26e5cdd21bbd" />

<img width="360" height="389" alt="image" src="https://github.com/user-attachments/assets/d1559b78-d0ac-43c6-8826-b40149392a8b" />

<img width="912" height="419" alt="image" src="https://github.com/user-attachments/assets/39fc6db7-92ac-40ef-90e5-c18c227f9b5d" />


