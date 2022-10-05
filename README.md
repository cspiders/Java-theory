# Class-01 - Notes

# 1. What is Java
# 2. JDK Installation
# 3. The Platform
# 4. Write first Java Class
# 5. Naming conventions for Class, Interface, enums
# 6. PATH Setting
<br/>
<br/>

# 1. What is Java
 Java is a general-purpose programming language and is a Computing Platform to build standalone, web, and Enterprise applications and services.
 According to Oracle, the company that owns Java, Java runs on 3 billion devices worldwide, which makes Java one of the most popular programming languages.
<br />
   
# 2. JDK Installation
<br/> 

## Here few questions arises in mind immediatly

1. which version of Java need to install
2. From where it needs to be downloaded.
3. How to install it. 
<br />

## OpenJDK or Oracle JDK

A key difference going forward is the release schedule and support policy.

## OpenJDK
OpenJDK will have a feature release every 6 months which is only supported until the next feature release. It's essentially a continuous stream of releases targeted to developers.

## Oracle JDK

The Oracle JDK is targeted more towards an enterprise audience which values stability. It's based on one of the OpenJDK releases but is then given long term support (LTS). The Oracle JDK has releases planned every 3 years.

Both <b> OpenJDK </b> and <b> Oracle JDK </b> are created and maintained currently by Oracle only.<br/>
Almost every existing JDK is derived from OpenJDK. <br/>
As suggested by many, licensing is a change between JDKs. <br/>
Starting with JDK 11 accessing the long-time support Oracle JDK/Java SE will now require a commercial license. <br/>
You should now pay attention to which JDK you're installing as Oracle JDK without subscription could stop working.<br/>

## Installation Steps:

### 1.	https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
### 2.	Choose Windows x64 Installer and click download link 
### 3.	Just click it and say yes to all wizards. 
### 4.	Installation is ready now.
### 5.	Go to  C:\Program Files\Java\jdk-17.0.4.13 (JDK_HOME)
### 6.	Here the bin contains the tools to compile and execute your Java program. 
### 7.	Write helloworld Java program and start working.
<br/>

## Development Setup:
### src> javac HelloWorld.java
### src>javac -d ../classes HelloWorld.java
### classes> java HelloWorld
### src>javac –help //which gives all the available options of javac.

<br />
  


# 3. The Platform
<br> The meaning of platform is the hardware or software environment in which a program runs. 
<br> We have some of the most popular platforms like Microsoft Windows, Linux, Solaris OS, and Mac OS are available in the market. 
<br> Most platforms can be described as a combination of the operating system and underlying hardware. 

<br> The Java platform software-only platform that runs on top of other hardware-based platforms.
<br> The Java platform has two components

###     1.	The Java Virtual Machine
###     2.	The Java Application Programming Interface (API)

<br> <b> Java Virtual Machine</b>. it's the base for the Java platform and it can be installed on various hardware-based platforms.
<br> <b> The API </b> is a large collection of ready-made classes and interfaces grouped into libraries and these libraries are grouped into packages.

<br />

# 4. Write first Java Class
## Program-1

 Class HelloWorld <br>
{ <br>
 Public static void main (String args[]){ <br>
 System.out.println(“Hello World”); <br>
} <br>
 } <br>
<br />


## Program-2

 Interface Inter1{ <br>
   // interface content goes here .<br>
 } <br>
<br />


## Program-3
 enum months{ <br>
 // enum constants are added here.<br>
 }<br>
<br />

# 5. Naming conventions
 Naming conventions make programs easy to read and understand. They can also give information about the function of the identifier-for example, 
 whether it's a constant, package, or class-which can be helpful in understanding the code.
<br />
## Naming conventions to Write Class
 1.	Class name should be Noun. <br>
 2.	Class name should start with capital letter and follow camel-case <br>
 3.	Use whole words and must avoid acronyms and abbreviations. <br>
<br />

## Naming conventions to write interfaces <br>
 1.	Interface name should be Adjective such as Runnable, Serializable, etc <br>
<br />

## Naming conventions to write enums
 1.	enum name should be in title case (same as class names).<br>
 2.	enum fields should be in all UPPER CASE (same as static final constants).<br>
<br />


# 6. PATH Setting
<br> Specify command’s location to the commands
<br> 1.	Command prompt wise
<br> 2.	User wise 
<br> 3.	Systemwise
<br> Give absolute path of bin to the command prompt to tell where the tools related to execution are stored.

## Command wise:
 D:test> set PATH=c:\\program files\jdk\bin

## User wise:
Go to properties -> environment variable=>path 

## System wise:
<br> This is not the recommended way because the other user may edit or delete the variables. 
<br> Security problem arises so go to user variables only. If another user logs in he can easily see the environmnt variable set by previous user.
<br> Go to properties -> environment variable=>path 


