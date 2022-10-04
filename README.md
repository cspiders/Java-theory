# Class-01
# Class-00-Basics-05-10-2022


# 

# 1. What is Java
### Java is a general-purpose programming language and is a Computing Platform to build standalone, web, and Enterprise applications and services.
### Java is a multi-platform, object-oriented, and network-centric language that can be used as a platform in itself.
### According to Oracle, the company that owns Java, Java runs on 3 billion devices worldwide, which makes Java one of the most popular programming languages.
<br />

# 2. Write first Java Class
## Program-1

## Class HelloWorld
### {
### Public static void main (String args[]){
### System.out.println(“Hello World”);
### }
### }
<br />

# 3. Naming convention
### Naming conventions make programs easy to read and understand. 
### They can also give information about the function of the identifier-for example, 
### whether it's a constant, package, or class-which can be helpful in understanding the code.
<br />

## Naming conventions to Write Class
### 1.	Class name should be Noun.
### 2.	Class name should start with capital letter 
### 3.	Use whole words and must avoid acronyms and abbreviations.
<br />


## Program-2

## Interface Inter1{
## // interface content goes here .
}
<br />


## Naming conventions to write interfaces 
### 1.	Interface name should be Adjective such as Runnable, Serializable, etc
<br />


## Program-3
## enum months{
## // enum constants are added here.
## }
<br />


## Naming conventions to write enums
### 1.	enum name should be in title case (same as class names).
### 2.	enum fields should be in all UPPER CASE (same as static final constants).
<br />

## Program-4
### package com.test;
### public class House {
### //camelCase
### // primitive datatypes
### int sandInTons;
### long bricksInNos;
### double cementInKgs;
### int labourInNos;
### public static void main(String[] args) {
### // derived datatypes
### House house1  = new House();
###	house1.sandInTons = 10000;
###	house1.bricksInNos = 50000;
###	house1.cementInKgs = 1000;
###	house1.labourInNos = 20;
### House house2 = new House();
###   house2.sandInTons = 5000;
### 	house2.bricksInNos = 33000;
###	  house2.cementInKgs = 500;
###	  house2.labourInNos = 10;
###   House house3 = new House();
###   house2.sandInTons = 500;
###   house2.bricksInNos = 3000;
###	  house2.cementInKgs = 50;
###	  house2.labourInNos = 5;
###  System.out.println(house1.costEstimation());
###  System.out.println(house2.costEstimation());
###   System.out.println(house3.costEstimation());
### 	}
### double costEstimation (){
### double cost = sandInTons+bricksInNos+cementInKgs+labourInNos;
### return cost;
###	}
### }
<br />

# 3. The Platform
### A platform is the hardware or software environment in which a program runs. 
### We have some of the most popular platforms like Microsoft Windows, Linux, Solaris OS, and Mac OS are available in the market. 
### Most platforms can be described as a combination of the operating system and underlying hardware. 
### The Java platform software-only platform that runs on top of other hardware-based platforms.
### The Java platform has two components
### 1.	The Java Virtual Machine
### 2.	The Java Application Programming Interface (API)
### Java Virtual Machine; it's the base for the Java platform and is ported onto various hardware-based platforms.
### The API is a large collection of ready-made classes and interfaces grouped into libraries and these libraries are known as packages.

<br />

# 4. JDK Installation
<br/>

# 5. PATH Setting
### Specify command’s location to the commands
### 1.	Command prompt wise
### 2.	User wise 
### 3.	Systemwise
### Give absolute path of bin to the command prompt to tell where the tools related to execution are stored.
### Command wise:
### D:test> set PATH=c:\\program files\jdk\bin

## User wise:
### Go to properties -> environment variable=>path 

## System wise:
### This is not the recommended way because the other user may edit or delete the variables. 
### Security problem arises so go to user variables only.
### Go to properties -> environment variable=>path 

## Development Setup:
### src> javac HelloWorld.java
### src>javac -d ../classes HelloWorld.java
### src>javac –help //which gives all the available options of javac.

<br />
  
