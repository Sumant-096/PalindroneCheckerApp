🧩 Palindrome Checker Management System
📌 Project Description

The Palindrome Checker Management System is a Java console-based application designed to check whether a given string or number is a palindrome.

A palindrome is a word, phrase, or number that reads the same forward and backward (e.g., madam, 121, racecar).

This project follows a Use Case–driven development approach, ensuring structured implementation, clear documentation, and modular application flow.

🎯 Project Objective

To understand Java application structure.

To implement the main() method as the program entry point.

To practice string manipulation and logical problem solving.

To follow clean coding and documentation standards.

To design the application using structured Use Cases.

🛠️ Development Approach

The project is divided into multiple use cases for better clarity and maintainability.

📚 Use Cases
✅ UC1 – Application Entry & Welcome Message

JVM invokes the main() method.

Displays application name and version.

Establishes startup flow.

No palindrome logic implemented at this stage.

✅ UC2 – Accept User Input

Uses Scanner class.

Prompts user to enter a word or number.

Stores input for processing.

✅ UC3 – Palindrome Processing

Reverses the entered input.

Compares reversed string with original string.

Determines whether it is a palindrome.

✅ UC4 – Display Result

Displays:

"It is a Palindrome"

OR

"It is Not a Palindrome"

Ensures formatted console output.

🔄 Application Flow
Program Starts
      ↓
main() method invoked by JVM
      ↓
Display Welcome Message (UC1)
      ↓
Accept User Input (UC2)
      ↓
Process Palindrome Logic (UC3)
      ↓
Display Result (UC4)
      ↓
Program Ends
💻 Technologies Used

Java (JDK 8 or above)

Console-based execution

Object-Oriented Programming Concepts

🧠 Key Concepts Implemented

Class Structure

public static void main(String[] args)

Static Keyword

Scanner Class

String Manipulation

Conditional Statements

Console Output (System.out.println)

Application Flow Control

▶️ How to Run the Project

Install Java (JDK 8+).

Compile the program:

javac UseCase1PalindromeCheckerApp.java

Run the program:

java UseCase1PalindromeCheckerApp
📌 Sample Output
PALINDROME CHECKER MANAGEMENT SYSTEM
Version: 1.0

Enter a word:
madam

Result: It is a Palindrome# PalindroneCheckerApp
