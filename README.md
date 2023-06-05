# Class - 1 

### 1. What is Java
### 2. JDK Installation
### 3. My first Java Class	
### 4. JDK JRE JVM and Java API
### 5. Why Java is Popular
### 6. Java release history or Java Version History



<br />

# 1. What is Java

Java is a general-purpose programming language and is a Computing Platform to build   standalone, web, and Enterprise applications and services.
 
   
# 2. JDK Installation

### 1.	https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
### 2.	Choose Windows x64 Installer and click download link 
### 3.	Just click it and say yes to all wizards. 
### 4.	Installation is ready now.
### 5.	Go to  C:\Program Files\Java\jdk-17.0.4.13 (JDK_HOME)
### 6. Update the PATH in Environment variable with bin location. %JDK_HOME%\bin


<br/>

# 3. My first Java Class	

	 
##  Write helloworld Java program and start working. 

      class HelloWorld{
      public static void main(String args[]){
           System.out.println("Hello World"); 
         } 
      } 
  
 ## Note :
 ### The bin contains the tools to compile and execute your Java program.  
<br />

#  https://docs.oracle.com/javase/tutorial/getStarted/intro/definition.html

# 4. JDK JRE JVM and Java API

### JDK

Java Developer Kit contains tools needed to develop the Java programs, and JRE to run the programs. The tools include compiler (javac.exe), Java application launcher (java.exe), Appletviewer, etc… Compiler converts java code into byte code. Java application launcher opens a JRE, loads the class, and invokes its main method. The JDK is a development environment for building applications using the Java programming language.


### JRE

JRE = JVM + Class Libraries+ supporting files 

Java Runtime Environment contains JVM, class libraries, and other supporting files. It does not contain any development tools such as compiler, debugger, etc. Actually, JVM runs the program, and it uses the class libraries, and other supporting files provided in JRE. If you want to run any java program, you need to have JRE installed in the system.


### JVM

The JVM translates bytecode into native machine code.
The Java Virtual Machine provides a platform-independent way of executing code; programmers can concentrate on writing software, without having to be concerned with how or where it will run. 

### JAVA API 

API stands for Application Programming Interface. API contains all the classes and interfaces developed by Java people . If we develop any code this must be combined with API code to execute the programs.
<br />

### With most programming languages, you either compile or interpret a program so that you can run it on your computer. 

### The Java programming language is unusual in that a program is both compiled and interpreted. 
### With the compiler,first you translate a program into an intermediate language called Java bytecodes — the Platform-Independent codes interpreted by the interpreter on the Java platform. 
### The interpreter parses and runs each Java bytecode instruction on the computer. Compilation happens just once; interpretation occurs each time the program is executed.


# 5. Why Java is Popular

### Java is Popular because of its Design Goals .

The authors of JAVA have written an influential White Paper that explains their <b> design goals </b> and accomplishments.  

THE JAVA “WHITE PAPER” BUZZWORDS written by James Gosling and Henry McGilton.

### 1.	SIMPLE   
### 2.	OBJECT ORIETED
### 3.	DISTRIBUTED
### 4.	MULTIHREADED
### 5.	DYNAMIC
### 6.	ARCHITECTURAL NEUTRAL
### 7.	PORTABLE
### 8.	HIGH PERFORMANCE
### 9.	ROBUST
##  10. SECURE
<br />

##  SIMPLE
Java syntax is, indeed a cleaned-up version of the syntax for c++. Java omits many rarely used, poorly understood, confusing features of C++ that in our experience, bring more grief than benefit. There is no need for header files, pointer arithmetic, structures, unions, operator overloading, virtual base classes, and so on.EASY TO LEARN FOR PROFESSIONAL PROGRAMMERS AND AND EASY TO USE

## OBJECT ORIETED
The object-oriented design is a technique for programming that focuses on the data (=> objects) and on interfaces to that object. To make analogy with carpentry, an “objected –oriented” carpenter would be mostly concerned with the chair he has building and secondarily with the tools used to make it. A “non-object-oriented” carpenter would think primarily of his tools. The objected-oriented facilities of Java are essentially those of c++.
WE CAN FULLY UTILIZE THE OBJECT-ORIENTED PROPERTIES OR NOT.

##  DISTRIBUTED 
Java was designed for the distributed environment of the internet because it handles TCP/IP protocols. 
The client-server model is allowed the programs to talk each other form different systems.
Through RMI Package. 
WE CAN DISTRIBUTE JAVA APPLICATIONS ACROSS MULTIPLE JVMs. 

## MULTIHREADED
Java was designed to meet the real-world requirement of creating interactive and network-based programs. To accomplish this, Java supports multithreaded programming, which allows you to write programs that do many things simultaneously. The java runtime system comes with multi process synchronization that enables you to construct smoothly running interactive systems. Java’s easy-to-use approach to multithreading allows you to think about the specific behavior of your program, not the multitasking subsystem. BY RUNNING MULTIPLE THEREADS AT A TIJME WE CAN IMPROVE THE PERFORMANCE.

## DYNAMIC
Java programs carry with them substantial amounts of runtime type information that is used to provide and resolve access to objects at runtime. This makes it possible to dynamically link code in a safe and expedient manner this is crucial to the robustness of the Java environment, in which small fragments of byte codes may be dynamically updated on runtime system. LOAD ON DEMAND.

##  ARCHITECTURE NEUTRAL
A central issue for the Java designers was that of code longevity and portability. One of the main problems facing programmers is that no guarantee exists that if you write a program today, it will run tomorrow—even on the same machine. Operating system upgrades, processor upgrades, and changes in core system resources can all combine to make a program malfunction. The Java designers made several hard decisions in the Java language and the Java Virtual Machine in an attempt to alter this situation. Their goal was “write once; run anywhere, anytime, forever” To a great extent, this goal was accomplished.

## PORTABLE
A central issue for the Java designers was that of the code longevity and portability. One of the main problems facing programmers is that no guarantee exists that if you write today, it will run tomorrow – even on the same machine. Operating system upgrades, processor upgrades, and changes in core system resources can all combine to make a program malfunction. The Java designers made several hard decisions in the Java Language and the Java Virtual Machine in an attempt to alter this situation. Their goal was to ‘write once; run anyware, anytime, forever ‘. To greater extent, this goal was accomplished.  MIGRATING ONE MACHINE TO ANDOTHER MACHINE WITHOUT ANY CHANGES TO THE PROGRAM.


# 6. Java release timeline

##  https://en.wikipedia.org/wiki/Java_version_history

## Java 00 fearures => Java beta version 1995
<br />

## Java 1.0 features => Jan 23, 1996 first stable version released 

<br />

## Java 1.1 features => Feb 19, 1997 
    AWT
    Inner classes
    Java beans 
    JDBC
    RMI and Serialization
    Reflection API
    JIT Compiler 
    Internalization
    
    Java 1.1 divided into 3 parts J2SE + J2EE + J2ME 

## J2SE 1.2 features  => Dec 08, 1998 
    Swing API
    stritfp (removed from java17)
    Collection Framework
    JAVA size is tripled with 1500+ classes + 59 packages. 
      
## J2SE 1.3 => May 08, 2000
    JNDI    - Java Naming and Directory Interface 
    HotSpot JVM 
  
## J2SE 1.4  => Feb 06, 2002
    assert keyword 
    Regular expressions
    Non-blocking I/O (NIO)


## Java SE5 or 1.5 => Sep30, 2004
    Generics, 
    Annotations, 
    Autoboxing/unboxing, 
    Wrapper classes, 
    Enumerations, 
    var-args, 
    Enhanced for loop, 
    static imports. 
    java.util.concurrency

## JavaSE6 features => Nov11, 2006

    JDBC4.0
    Performance improvements
    Navigable map


# Oracle purchased Sun Microsystems in January 27, 2010

## JavaSE7 features => July 28, 2011
   
    strings in switch
    try-with-resources
    the diamond operator <> (aka type inference)
    binary integer literals
    allow underscore in numeric literals 
    catching multiple exceptions ,rethroewing exceptions with improved type checking
    java.nio.file,java.nio.file.spi,java.nio.file.attribute

## JavaSE8 features => March 18, 2014

    lambda expressions
    default and static methods in interfaces
    functional Interface
    forEach() in Iterable interface 
    Java stream api 
    Java time API
    Collection api improvemetns 
    Concurrency api improvements
    Java IO improvements
    Predefined Functional interfaces
      Predicate
      Function
      Consumer 
      Supplier
    Two argument functional interfaces
      BiPredicate
      BiFunction
      BiConsumer
    Primitive functional interface
      IntPredicate
      IntFunction
      IntConsumer
<br />

## JavaSE9 features 

    JShell
    Jlink - Java linker
    HTTP/2 client
    Process API updates
    private method inside interface
    try with resources enhancements
    factory method to creae unmodifiable collection
    Stream API enhancemets
    <> operator enhancements 
    safe varargs annotations 
    GIGC
   
 <br/ > 
## Java 10 features  => March20, 2018
    - Local- variable type inference

<br />

## Java 11 features  => March20, 2018

     1. String Utility methods 
     2. Local variable systax for Lambda expressions
     3. Running Java file with single command
     4. HttpClient 
     5. Nested based access control
     6. Reading/Writing Strigs to and from files (NIO)
      // up to here enough  remaining are platform level changes which is not much needed to developers.

## Java 12 & 13 dont have much language level changes
## Java12 features  => March 19, 2019
## Java13 features  => Sep 17, 2019

    [Preview]
    1. Switch Expressions 
    2. Text Blocks

## Java14 features  => March 17 , 2020

    1. Switch Expressions 
    2. NullPointerExpression (Meaningful / Helpful message)

    [Preview]
    1. Records 
    2. text blocks
    3. Pattern matching for instanceOf operator


## Java 15 features

    1. Sealed classes
    2. Hidden classes
    3. Text blocks 
    4. Records

## Java 16 features

   1. Sealed classes
   2. Records

## Java 17 features

   1. Sealed classes

# Difference between OpenJDK and OracleJDK


# A key difference going forward is the ReleaseSchedule and SupportPolicy.

## OpenJDK

 OpenJDK will have a feature release every 6 months which is only supported until the next feature release. It's essentially a continuous stream of releases   targeted to developers.

## Oracle JDK

The Oracle JDK is targeted more towards an enterprise audience which values stability. It's based on one of the OpenJDK releases but is then given long term support (LTS). The Oracle JDK has releases planned every 3 years.

Both OpenJDK and Oracle JDK are created and maintained currently by Oracle only.

OpenJDK and Oracle JDK are implementations of the same Java specification passed the TCK (Java Technology Certification Kit).

Most of the vendors of JDK are written on top of OpenJDK by doing a few tweaks to [mostly to replace licensed proprietary parts / replace with more high-performance items that only work on specific OS] components without breaking the TCK compatibility.


Many vendors implemented the Java specification and got TCK passed. For example, IBM J9, Azul Zulu, Azul Zing, and Oracle JDK.
Almost every existing JDK is derived from OpenJDK.

As suggested by many, licensing is a change between JDKs.

Starting with JDK 11 accessing the long-time support Oracle JDK/Java SE will now require a commercial license. 

You should now pay attention to which JDK you're installing as Oracle JDK without subscription could stop working.

