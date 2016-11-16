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

_10 points each for the first and last exercises, 5 points each for the rest, 60 points total_

For all but the first exercise, copy the included _functions-template.js_ file into a new file called _functions.js_ and add your final work to that file. There are (empty) `var`...`function` declarations for each of the exercises; simply fill in the code. The template is provided to facilitated better automated checking of your answers-in-progress.

1. Refactor any previous Khan Academy program so that it uses functions and functions as objects. Choose your functions so that they (a) reduce the total amount of code in your program and (b) improve the readability of your program. Save your code using the same filename as you did in the original assignment.
1. (textbook Chapter 5 Exercise 1) Write a function called `larger` that returns the larger of its two arguments. For example, the call `larger(-2, 10)` should return `10`.
1. (textbook Chapter 5 Exercise 3) Write a function called `average` that returns the average of all of the items in an array. For example, `average([4, 5, 7, 2])` should return `4.5`.
1. (textbook Chapter 5 Exercise 6) Write a function called `median` that accepts three numbers and returns the median. The median of three values is the value that is greater than or equal to one of the other values and less than or equal to the remaining value. For example, `median(9, 1, 2)` should return `2`.
1. (textbook Chapter 5 Exercise 8) Write a function called `numberOfOccurrences` that returns the number of occurrences of a given character in a string. For example, given the string `"Rat-a-tat-tat"` and the character `t`, `numberOfOccurrences("Rat-a-tat-tat", "t")` should return `5`.
1. Write a function called `squaresOf` that accepts an array of numbers as a parameter and returns an array of the squares of those numbers. For example, `squaresOf([-1, 11, 5, -3])` should return `[1, 121, 25, 9]`. Do _not_ use a loop; instead, use some combination of `map`, `filter`, and/or `reduce`.
1. Write a function called `squareRootsOf` that accepts an array of numbers as a parameter and returns an array of the square roots of _just the positive numbers_ in that array. For example, `squareRootsOf([-1, 9, 4, -3])` should return `[3, 2]`. Do _not_ use a loop; instead, use some combination of `map`, `filter`, and/or `reduce`.
1. Write a function called `acronym` that accepts a sentence string as a parameter and returns its acronym. For example, `acronym("I know, right?")` should return `"ikr"`. Do _not_ use a loop; instead, use some combination of `map`, `filter`, and/or `reduce`. _Hint:_ Look up the functions `split` and `join`.
1. (textbook Chapter 5 Exercise 32) Write a function called `twice` that takes a function `f` and a value `x` as its parameters and returns `f(f(x))`. For example, `twice(function (x) { return x * x; }, 3)` should return `81`.
1. Write a constructor and prototype for a `Person` object that accepts two properties: a `fullName` (string) and a `birthdate` (`Date`). Give its prototype two functions: an `initials` function that returns the person’s full name as initials (_Hint:_ See the `acronym` function above) and an `age` function that returns the person’s age in years. When you’re done, code like this should work:
```javascript
  var p = new Person("Evan Rachel Wood", new Date(1987, 8, 7));
  alert(p.fullName);   // Should display "Evan Rachel Wood"
  alert(p.birthdate);  // Should display "Mon Sep 07 1987 00:00:00 GMT-0700 (PDT)" (time zone may vary)
  alert(p.initials()); // Should display "ERW"
  alert(p.age());      // Should display 29
```

### Programs

_20 points each, 40 points total_

1. Write a Khan Academy “drawing selector” program that draws one of five (5) different pictures, which the user selects by pressing a key. Encapsulate each “picture” within its own self-contained function, and do _not_ use conditional statements to choose among the functions. Submit this program to this repository as _pictures.js_.
1. Write a JSFiddle program that implements a binary calculator: it has two `input` elements to represent operands, with a `select` dropdown in between them listing at least ten (10) possible operations (addition, subtraction, multiplication, exponentiation, etc.), with one of these operations being a random number in between the two operands, inclusive. Provide a _Compute_ button that performs the selected calculation and displays the result. Represent each operation internally as a function that accepts two parameters and returns the result, and do _not_ use conditional statements to choose among the functions. Submit this program to this repository as _calculator.html_ and _calculator.js_, as well as _calculator.css_ if you wrote some CSS for your program.
