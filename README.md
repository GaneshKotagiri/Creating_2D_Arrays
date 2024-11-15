# Creating_2D_Arrays
This Java program demonstrates how to create a 2D array (matrix) of integers, populate it with values, display the matrix, and search for a specific number within the matrix. The program prompts the user to enter values for the matrix, outputs the matrix, and then checks if a specified value exists in the matrix, displaying its position if found.
Features
Creates a 3x3 integer matrix.
Allows the user to enter values to populate the matrix.
Prints the matrix in a structured format.
Searches for a user-specified value within the matrix.
Displays the location (row, column) of the found value or a message if not found.
Prerequisites
Java Development Kit (JDK) 8 or higher installed.
A code editor or IDE that supports Java, such as IntelliJ IDEA, Eclipse, or Visual Studio Code.
How It Works
Matrix Initialization: A 3x3 matrix is created.
User Input for Matrix Elements: The program prompts the user to enter 9 integers, which fill the matrix in row-major order.
Matrix Display: The matrix is printed in a readable 3x3 format.
Search Operation: The program prompts the user to enter a key to search for within the matrix. If found, it displays the position (row, column) of the key; otherwise, it displays a "not found" message.
Code Walkthrough
search Method
The search method takes a 2D array (matrix) and an integer (key) as input. It iterates over each element in the matrix, checking if it matches the key. If a match is found, it prints the location and returns true. If no match is found, it prints "Key not found" and returns false.
main Method
The main method initializes a 3x3 matrix, populates it with user input, prints the matrix, and then performs the search operation.

Matrix Population: Asks the user to enter 9 integers to fill the matrix.
Matrix Display: Prints each element in a 3x3 format.
Search Prompt: Prompts the user for the key to search for and calls the search method.
