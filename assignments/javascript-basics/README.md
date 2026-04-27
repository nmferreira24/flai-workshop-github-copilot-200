# 📘 Assignment: JavaScript Basics

## 🎯 Objective

Learn the fundamentals of JavaScript by writing programs that use variables, conditionals, loops, and functions to solve simple problems and interact with the browser console.

## 📝 Tasks

### 🛠️ Variables and Data Types

#### Description
Declare variables using `let` and `const` to store different types of data, then print information about a student to the console.

#### Requirements
Completed program should:

- Declare a `const` variable for the student's name (a string)
- Declare a `let` variable for the student's age (a number)
- Declare a `let` variable for whether the student is enrolled (a boolean)
- Print a sentence to the console using all three variables, e.g.:
  ```
  Alice is 16 years old. Enrolled: true
  ```

### 🛠️ Conditionals and Loops

#### Description
Use `if/else` conditionals and a `for` loop to categorize a list of grades and count how many are passing.

#### Requirements
Completed program should:

- Define an array of at least 5 numeric grades (0–100)
- Loop through the array using a `for` loop
- Print each grade with a label: `"Pass"` if the grade is 60 or above, `"Fail"` otherwise, e.g.:
  ```
  85 → Pass
  42 → Fail
  ```
- After the loop, print the total number of passing grades, e.g.:
  ```
  Passing grades: 3 out of 5
  ```

### 🛠️ Functions

#### Description
Write a reusable function that calculates the average of an array of numbers.

#### Requirements
Completed program should:

- Define a function named `calculateAverage` that accepts an array of numbers as a parameter
- The function should return the average (sum divided by count)
- Call the function with your grades array from the previous task
- Print the result rounded to one decimal place, e.g.:
  ```
  Class average: 74.2
  ```
