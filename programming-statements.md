**CMSI 185** Computer Programming, Fall 2016

# Assignment 1101
From nouns (expressions) we shift to verbs (statements), and the range of things you can code up jumps by another level. As before, you have your own repository for this one and may not share work with others.

## Background Reading
- Read Chapter 4 of the textbook for additional and in-depth coverage of the material covered by this assignment.
- As an epilogue of sorts to the Programming Data assignment, read this: [A JavaScript journey with only six characters](http://jazcash.com/a-javascript-journey-with-only-six-characters/). One of the questions below will involve this article.
- [JavaScript and your Brain](https://www.youtube.com/watch?v=cIOIyfRoGcM), a recorded presentation by renowned JavaScript author Douglas Crockford, around 37 minutes long. Watch it until the end—the Q&A section has some good stuff too.
- [The Real Computer Revolution Hasn't Happened Yet](http://www.vpri.org/pdf/m2007007a_revolution.pdf) by Alan Kay. This was written in 2007, and you are learning computer programming in 2016. Focus on how things have changed (or not) since then.

## Automated Feedback Setup
In order to connect your repository to our automated code review and feedback system, once you are up and running please send your repository’s URL to Ed Seim. You can either find him in person in the lab, tweet him at [https://twitter.com/SirSeim](https://twitter.com/SirSeim), or mention him in a GitHub comment (`SirSeim`). Once he has you hooked up, the system will provide feedback on code formatting and quality whenever you commit a new version to GitHub. _Points will be deducted if issues here linger in the final submission._

## For Submission

The assignment consists of four (4) sections: _Exercises_, _Warm-Up Programs_, _Stretch Programs_, and _Questions_. For each section, follow the specifications given for submitting the requested work.

### Exercises

_5 points each, 35 points total_

Do the following statement programming exercises. Provide your answers in the specified filename. Each exercise is essentially a self-contained mini-program, so they should be easy to verify in any of the JavaScript environments that you have seen so far (with perhaps a well-placed `alert` or `console.log` here and there—you may do that for testing, but don’t include them in your answer unless explicitly instructed to do so).

1. Write a mini-program that `prompt`s the user for a temperature in degrees Fahrenheit, then `alert`s whether water is “solid,” “liquid,” or “gas” at thet temperature. Consider water to be “gas” when the temperature is exactly its boiling point and “solid” when the temperature is exactly at its freezing point. Save this mini-program in a file called _winterIsComing.js_.
1. Write a mini-program that uses `console.log` to count down from 60 to zero. When the code reaches zero, have the program `console.log` the sentence “Lift-off!” Save this mini-program in a file called _countdown.js_.
1. Write a mini-program that computes two random integers ranging from 1 to 6. Have the program `alert` the numbers. If both numbers turn out to be 1, have the program then `alert` “Snake eyes!” Save this mini-program in a file called _snakeEyes.js_.
1. Write a mini-program that creates an array consisting of 100 random integers ranging from 1 to 6. Assign this array to a variable called `rolls`. Save this mini-program in a file called _rolls.js_.
1. Write a mini-program that keeps on `prompt`ing the user for some input until the user enters something that can be interpreted as a number. Save this mini-program in a file called _numbersOnly.js_.
1. Write a mini-program that repeatedly accesses the current date/time until the minute is odd (e.g., 10:31pm, 9:23am), at which point it `alert`s “Ring!” Save this mini-program in a file called _alarm.js_.
1. Pick a favorite language other than English and write a mini-program that accesses today’s `Date` then assigns the word for the current hour in that language to a variable called `thisHourInWords` _without_ using any kind of conditional statement (e.g., _uno_ for 1 o’clock in Spanish; _san_ for 3 o’clock in Japanese). Save this mini-program in a file called _thisHourInWords.js_.

### Warm-Up Programs

_10 points each, 20 points total_

Write the following programs. Provide your code in the files specified.

1. Write a Khan Academy program that draws a faux Rubik’s Cube in the drawing area in isometric 3D. i.e., Draw 9 identical parallelograms apiece for the three faces that one would see. Something like this:

    ![Isometric Rubik's Cube](isometric-rubiks-cube.jpg)

    Submit this program to this repository as _isometric-rubiks-cube.js_. _Do **not** use 27 separate parallelogram-drawing statements._
1. Read up on how to use the `select` and `option` elements in HTML. Write a JSFiddle web page that displays a `select` dropdown menu listing ten (10) countries of your choice. When the user selects a country, have the web page display that country’s emoji flag and capital city. _Do **not** use an `if` nor a `switch` statement (note that `switch` has not even been brought up in class!) to determine this information._ Submit this program to this repository as _countries.html_ and _countries.js_, as well as _countries.css_ if you wrote some CSS for your program.

### Stretch Programs

_15 points each, 30 points total_

Write the following programs. Provide your code in the files specified.

1. Write a Khan Academy program that renders an animated “precipitation” scene of your choice. Ideas include snowflakes, raindrops, hail, a sharknado, etc. Your animation should draw at least *100* such “particles.” You are free to decide how they should travel to the ground: accelerated by gravity, drifting in the breeze, etc. When a precipitation “particle” lands on the ground, reset it so that it starts back at the top of the screen on the next frame. Submit this program to this repository as _precipitation.js_.
1. Write a “guess the number” web page game in JSFiddle. Start with having the computer choose a random integer from zero to 99. Give the web page an `input` element and a _Guess_ button. Whenever the user clicks the _Guess_ button, the program states whether the number in the `input` element is higher or lower than the target integer. Or, if the user has guessed right, the program issues an appropriately celebratory message. Reloading/rerunning the page starts the program over. Submit this program to this repository as _guess.html_ and _guess.js_. Providing _guess.css_ is encouraged but not necessary.

### Questions

_5 points each, 15 points total_

Answer the following questions. Provide these answers in a file called _questions.md_ (use the previous template for the _programming-data_ assignment). As before, use the [Markdown (`.md`) format](https://guides.github.com/features/mastering-markdown/). If you need help with Markdown, ask me or any of the TAs. Recall also that the assignment writeups you’ve seen so far are written with Markdown, so you can also use those as examples for how to do certain things.

1. _Programming data epilogue_: After reading [A JavaScript journey with only six characters](http://jazcash.com/a-javascript-journey-with-only-six-characters/), (a) State the JavaScript language “trick” that the article uses to coax any JavaScript code out of just six of its characters, and (b) Express whether you think this is a flaw or feature of the JavaScript programming language.
1. (similar textbook Chapter 4 Exercise 18) Under what circumstances would it be better to use a `while` statement over `do-while` and vice versa, and why?
1. Here is another programmer joke: _A programmer goes to the shop to buy some milk. Her spouse calls and says “While you’re out, get some eggs.” She never returns._
    1. Why this is funny (or supposed to be funny)?
    1. Why do you need to be a programmer to appreciate this joke?
