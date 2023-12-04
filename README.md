# 10th Homework of Java Test Automation Course - Solvd Laba
This repository stores the 10th homework given by our mentor in the Java Test 
Automation Course at Solvd Laba. It consists of using the Stream API in 
different cases to get different results, and using Java reflection to get
information about methods, fields, constructors and modifiers from classes.

## Explanation

To accomplish the requirements of the homework, I've used the Stream API
in the Lists that I had created in previous homeworks in the Main class,
applying both terminal and non-terminal methods in them in order to get the 
desired result. Then, I've used Java reflection to get the fields, constructors,
methods, modifiers, return types and parameters types from the class Person. 
Finally, I've instantiated an object from the class Bird and invoked a method
using purely reflection.

## What did I learn?

In this homework I've realized how many lines of code I can save using the
Stream API instead of regular loops or classic Java tools. It was pretty 
interesting to learn about some non-terminal methods like map(), flatMap(), 
peek() or filter(), and terminal methods like count(), collect(), anyMatch()
or allMatch(). These last ones are called terminal because they don't return
a Stream, but they return other datatype that doesn't allow us to keep working
with streams. Finally, regarding Java reflection, I was astonished about the
amount of things that we can do with this tool, and it is quite interesting
to know in order to learn deeply this great programming language.

## Technologies

- Java
- Maven

## Set-Up

To run this project you will need an updated version of Java.
First, clone this repository in a folder of your PC.
You have to put the following command in a terminal:

```bash
  git clone this-repo-url
```
You will need an IDE to open the project folder and, finally, run the 
Main.java file to see the program output.

## Author

- [@Nazareno Bucciarelli](https://github.com/nazabucciarelli)
