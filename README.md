SortedStack

A simple Java program that reads a series of integers from the console, stores them in a stack, sorts the stack in ascending order using Java's built-in sorting mechanism, and then prints the sorted result.

Features

Input Parsing: Uses java.util.Scanner to read integer inputs from the console until a non-integer is encountered.
Stack Usage: Leverages java.util.Stack (a LIFO data structure) to store the integers.
Sorting: Utilizes Collections.sort() to sort the stack in ascending order.
Output: Displays the sorted integers on the console.
How It Works

Input Collection:
The program prompts the user to enter integers separated by spaces. Input collection stops when a non-integer is entered.
Data Storage:
All valid integers are pushed onto a Stack<Integer>.
Sorting:
Since Stack is a subclass of Vector (which implements List), the program sorts it using Collections.sort().
Output:
The sorted stack is printed to the console.
Prerequisites

Java Development Kit (JDK): Ensure you have JDK installed (version 8 or above is recommended).
Compilation and Execution

Generate Javadoc (Optional)
To generate the documentation, run:

javadoc -d docs SortedStack.java
Compile
Compile the Java program using:

javac SortedStack.java
Run
Execute the compiled program with:

java SortedStack
Sample Usage

Input:

5 3 8 1 2 a
Output:

Enter integer numbers separated by spaces. To finish, enter any non-integer input:
Sorted stack:
1 2 3 5 8 
Code Overview

The SortedStack.java program demonstrates how to reuse several pre-built Java API components:

Stack: Utilizes java.util.Stack to maintain a collection of integers.
Scanner: Uses java.util.Scanner for efficient console input.
Collections.sort(): Leverages the built-in sorting mechanism to sort the elements.
