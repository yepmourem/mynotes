# chapter 1: An Introduction to Java
## 1.2 The Java "White Paper" Buzzwords

There are 11 buzzwords in Java, here is a overview

1. Simple
2. Object-Oriented
3. Distributed
4. Robust(健壮性)
5. Secure
6. Architecture-Neutral
7. Portable
8. Interpreted
9. High-Performance
10. Multithreaded
11. Dynamic

### 1.2.1 Simple

The language is simple means:

1. It can be programed easily without a lot of esoteric training and which leveraged today's standard practice.
2. It can be small.

The syntax for Java is a cleaned-up version of C++ syntax.

### 1.2.2 Object-Oriented

Object-Oriented is a technique that focuses on **date**, **objects** and the **interfaces** to those objects.

### 1.2.3 Distributed
Java applications can open and access objects across the Net via URL 
because it has an extensive library of routines for copying with TCP/IP protocols like HTTP and FTP.

### 1.2.4 Robust

One of the biggest difference between Java and C/C++ is that Java has a pointer model that eliminates the possibility of overwriting memory and corrupting data.

The Java compiler can detects many problems that in other languages would show up only at runtime.

### 1.2.5 Secure
Untrusted code was executed in a sandbox environment. From the beginning, Java was designed to make certain kind of attacks impossible.

* Overrunning the runtime stack
* corrupting  memory outside its own process space
* Reading or writing files without permission

### 1.2.6 Architecture-Neutral

There is a "Virtual Machine" below Java so that the **bytecode** could run on many OS.

Of course, it is slower than running real machine, but Java has a option that can translate the bytecode sequences into machine code.

Java’s virtual machine has another advantage. It increases security because it
can check the behavior of instruction sequences.

### 1.2.7 Portable
Java is no "implementation-dependent" aspects of the specification.

For example, `int` in Java js always 32-bit. But in C/C++, it is a implementation-dependent type.

The libraries that are a part of the system define portable interfaces.
And not only are your programs portable, but the Java APIs are often of higher quality than the native ones

### 1.2.8 Interpreted
The Java interpreter can execute Java bytecode directly on any machine to which the interpreter has been ported.

The tool called ***jshell*** supported rapied and exploratory.

### 1.2.9 High-Performance
The bytecode can be translated into machine code on the fly.

### 1.2.10 Multithreaded
Multithreaded can bring a better interactive responsiveness(交互响应) and real-time behavior.

Because of the end of "**Moore's law**", we have to consider this buzzword.

### 1.2.11 Dynamic

Libraries can freely%0D%0Aadd new methods and instance variables without any effect on their clients.

