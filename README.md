1. What is difference between JDK,JRE and JVM?
JVM
JVM is an acronym for Java Virtual Machine, it is an abstract machine which provides the runtime environment in which java bytecode can be executed. It is a specification.
JVMs are available for many hardware and software platforms (so JVM is platform dependent).

JRE
JRE stands for Java Runtime Environment. It is the implementation of JVM.

JDK
JDK is an acronym for Java Development Kit. It physically exists. It contains JRE + development tools.

2.How many types of memory areas are allocated by JVM?

Many types:
Class(Method) Area
Heap
Stack
Program Counter Register
Native Method Stack

3.What is JIT compiler?
Just-In-Time(JIT) compiler:It is used to improve the performance. 
JIT compiles parts of the byte code that have similar functionality at the same time, and hence reduces the amount of time needed for compilation.
Here the term “compiler” refers to a translator from the instruction set of a Java virtual machine (JVM) to the instruction set of a specific CPU.

4. What is platform?
A platform is basically the hardware or software environment in which a program runs. There are two types of platforms software-based and hardware-based. Java provides software-based platform.

5. What is the main difference between Java platform and other platforms?
The Java platform differs from most other platforms in the sense that it’s a software-based platform that runs on top of other hardware-based platforms.It has two components:
Runtime Environment
API(Application Programming Interface)

6. How to create a daemon thread in Java?
We use the class setDaemon(true) to create this thread. We call this method before the start() method, and else we get IllegalThreadStateException.
