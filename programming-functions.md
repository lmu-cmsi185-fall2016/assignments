**CMSI 185** Computer Programming, Fall 2016

# Assignment 1122
This assignment practices your use of functions, which are essentially mini-programs that you can use again and again. You have your own repository for this one and may not share work with others.

## Background Reading
- Read Chapter 5 of the textbook for additional and in-depth coverage of the material covered by this assignment.
- Go through the Codecademy [Review of Functions in JavaScript](https://www.codecademy.com/courses/functions_in_javascript/0/1). This gives you a look at the same material but given through another medium—a useful way to reinforce what you know.

## Automated Feedback Setup
In order to connect your repository to our automated code review and feedback system, once you are up and running please send your repository’s URL to Ed Seim. You can either find him in person in the lab, tweet him at [https://twitter.com/SirSeim](https://twitter.com/SirSeim), or mention him in a GitHub comment (`SirSeim`). Once he has you hooked up, the system will provide feedback on code formatting and quality whenever you commit a new version to GitHub. _Points will be deducted if issues here linger in the final submission._

For this assignment, the feedback system also includes a rudimentary _unit test suite_ that checks the _correctness_ of the functions in your exercises. Not all results are checked; they are chosen just to ensure that your code is not insanely off-course. Grading will include additional test cases that are not checked by the automated system.

## For Submission

### Exercises

1. Refactor any previous Khan Academy program so that it uses functions and functions as objects. Choose your functions so that they (a) reduce the total amount of code in your program and (b) improve the readability of your program.
1. More to be written.

### Programs

1. Write a Khan Academy “drawing selector” program that draws one of five (5) different pictures, which the user selects by pressing a key. Encapsulate each “picture” within its own self-contained function, and do _not_ choose among the functions with conditional statements.
2. Write a JSFiddle program that implements a binary calculator: it has two `input` elements to represent operands, with a `select` dropdown in between them listing at least ten (10) possible operations (addition, subtraction, multiplication, exponentiation, etc.), with at least one of these operations being a random number in between the two operands. Provide _Compute_ button that performs the calculation and displays the result. Represent each operation internally as a function that accepts two parameters and returns the result, and do _not_ choose among the functions with conditional statements.
