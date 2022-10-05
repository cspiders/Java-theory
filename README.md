# Class-01 - Notes

# 1. What is Java
# 2. JDK Installation
# 3. The Platform
# 4. Write first Java Class
# 5. Naming conventions for Class, Interface, enums
# 6. PATH Setting


# 1. What is Java
 Java is a general-purpose programming language and is a Computing Platform to build standalone, web, and Enterprise applications and services.
 According to Oracle, the company that owns Java, Java runs on 3 billion devices worldwide, which makes Java one of the most popular programming languages.
<br />
   
# 2. JDK Installation
<br/> 
# 3. The Platform
<br> The meaning of platform is the hardware or software environment in which a program runs. 
<br> We have some of the most popular platforms like Microsoft Windows, Linux, Solaris OS, and Mac OS are available in the market. 
<br> Most platforms can be described as a combination of the operating system and underlying hardware. 

<br> The Java platform software-only platform that runs on top of other hardware-based platforms.
<br> The Java platform has two components

<br>      1.	The Java Virtual Machine
<br>      2.	The Java Application Programming Interface (API)

<br> Java Virtual Machine; it's the base for the Java platform and it can be installed on various hardware-based platforms.
<br> The API is a large collection of ready-made classes and interfaces grouped into libraries and these libraries are grouped into packages.

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

## Program-4
package com.test; <br>
public class House { <br>
//camelCase<br>
// primitive datatypes<br>
int sandInTons;<br>
long bricksInNos;<br>
double cementInKgs;<br>
 int labourInNos;<br>
 public static void main(String[] args) {<br>
 // derived datatypes<br>
 House house1  = new House();<br>
	house1.sandInTons = 10000;<br>
	house1.bricksInNos = 50000;<br>
	house1.cementInKgs = 1000;<br>
	house1.labourInNos = 20;<br>
 House house2 = new House();<br>
   house2.sandInTons = 5000;<br>
 	house2.bricksInNos = 33000;<br>
	  house2.cementInKgs = 500;<br>
	  house2.labourInNos = 10;<br>
   House house3 = new House();<br>
   house2.sandInTons = 500;<br>
   house2.bricksInNos = 3000;<br>
	  house2.cementInKgs = 50;<br>
	  house2.labourInNos = 5;<br>
  System.out.println(house1.costEstimation());<br>
  System.out.println(house2.costEstimation());<br>
  System.out.println(house3.costEstimation());<br>
 	}<br>
 double costEstimation (){<br>
 double cost = sandInTons+bricksInNos+cementInKgs+labourInNos;<br>
 return cost;<br>
	}<br>
 }<br>
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

## Development Setup:
<br> src> javac HelloWorld.java
<br> src>javac -d ../classes HelloWorld.java
<br> classes> java HelloWorld
<br> src>javac –help //which gives all the available options of javac.

<br />
  
