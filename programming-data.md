**CMSI 185** Computer Programming, Fall 2016

# Assignment 1011
With this assignment, we shift from freestyle to deep dive, starting with a long look at how we can express different kinds of information in JavaScript. With the deep dive comes a switch to solo flight. You have your own repository and may not share work with others.

## Background Reading
Read Chapter 3 of the textbook for additional and in-depth coverage of the material covered by this assignment.

## Automated Feedback Setup
In order to connect your repository to our automated code review and feedback system, once you are up and running please send your repository’s URL to Ed Seim. You can either find him in person in the lab, tweet him at [https://twitter.com/SirSeim](https://twitter.com/SirSeim), or mention him in a GitHub comment (`SirSeim`). Once he has you hooked up, the system will provide feedback on code formatting and quality whenever you commit a new version to GitHub. _Points will be deducted if issues here linger in the final submission._

## For Submission
The assignment consists of three (3) sections: _Exercises_, _Programs_, and _Questions_. For each section, follow the specifications given for submitting the requested work.

The raw point total for this assignment is 180 points. Final percentage score will be used for grading purposes (i.e., 162 out of 180 points = 90% = 90 points in the final grading total).

### Exercises
Do the following data/expression exercises. Provide your answers in a file called _exercises.js_ (template provided). Reflecting the theme of this assignment, the final version of this file will hold one object per section, assigned to variables as specified therein, with one property for each of your exercise answers. For example, if _English to JavaScript Part 1_ has three (3) exercises and _JavaScript to English_ has one (1), your _exercises.js_ file would look like this:

```javascript
var englishToJavaScript1 = {
    1: 42,
    2: "Because it is always 42.",
    3: Math.pow(2, 5) / ((18 + 14) / ((20 + 1) * 2))
};

var javaScriptToEnglish = {
    1: {
        expression: "Two times the sum of eleven and ten",
        dataType: "Number",
        value: 42
    }
};
```

*Protip:* Try to “execute” your _exercises.js_ code in a JavaScript environment to make sure that it does not have language errors. The correct additional commands will also reveal if the expressions you wrote yield the correct value.

#### English to JavaScript Part 1
_2 points each, 40 points total_

Write the following values out as JavaScript expressions. Do _not_ pre-compute anything—let the computer do all of the work! (e.g., if you are asked to write “the number one plus the number two,” answer `1 + 2`, not `3`) Place your answers in an object assigned to a variable named `englishToJavaScript1` in _exercises.js_.

1. A three-character string containing the first three letters of the English alphabet in uppercase
1. Five divided by two
1. The number 64
1. A two-character string with `6` as the first character and `4` as the second
1. The date June 23, 1912
1. A string consisting of three consecutive `1` characters
1. A string containing the [PILE OF POO](https://codepoints.net/U+1F4A9) and [CHERRY BLOSSOM](https://codepoints.net/U+1F338) characters expressed as Unicode escape sequences (i.e., don’t type or copy/paste them in directly)
1. “Not” the empty string
1. Infinity plus the number five
1. Nine times the sum of three and twelve
1. A string stating `The answer is ` concatenated with the sum of 20 and 12
1. An expression whose value is whether one divided by zero is exactly equal to infinity
1. An expression whose value is whether the number four is between –10 and 3
1. An expression whose value is whether 20 is less than 10 or the string `hello` is exactly equal to the string `goodbye`
1. The sine of the product of two and π
1. The date and time twelve midnight on January 1, 1970
1. An expression whose value is the square root of –1 if the string `complex` is exactly equal to the string `imaginary`, or whose value is the exclamation point `!` if not
1. An expression whose value is whether infinity divided by itself is exactly equal to one
1. The string `César Chávez` but with accented characters expressed as Unicode escapes (`é` is codepoint E9 and `á` is codepoint E1)
1. The negative of –4

#### English to JavaScript Part 2
_3 points each, 30 points total_

Write the following values out as JavaScript expressions. Give careful thought to the structure of what is requested, and choose the corresponding JavaScript structure (array, object, etc.) in a way that matches the information’s content as closely as possible. Place your answers in an object assigned to a variable named `englishToJavaScript2` in _exercises.js_. 

1. An array of the first eight (8) prime numbers in ascending order
1. An array containing the two stars of the film _Thelma & Louise_ (look them up), with last names in the property `lastName` and first names in the property `firstName`, listed alphabetically by `lastName`
1. An object representing one thousand dollars, with the properties `amount` for the dollar value and `currency` for the monetary unit (`"$"`)
1. An object representing the three primary dreams from the film _Inception_ (watch or read about it if necessary), expressed as objects with a `location` and a `subdream` containing an object describing that dream, also with the same structure; the last dream has no `subdream`, and the `location`s for each dream are, in order, `Los Angeles`, `hotel`, and `fortress`
1. An array listing the three titles of the _Hunger Games_ series of novels in ascending publication order
1. An object consisting of a `parents` array and a `children` array, where `parents` consists of Richard Williams and Oracene Price and `children` consists of Venus Williams and Serena Williams, where each person is described with a `firstName` and `lastName`
1. An object containing the names and official abbreviations of Alaska, Washington, Oregon, California, and Hawaii, where the property names are the abbreviations and their corresponding values are the full names of each state
1. An array consisting of the number 100, the string `100`, and an object with a single `value` property set to the number 100, in that order
1. An array of the square roots (calculated by the computer) of 11, 17, 23, and 31
1. An object holding some of the biographical information for Rosalind Franklin (look her up), specifically with the properties `firstName`, `lastName`, `birthdate`, and `deathdate` (with the latter two being `Date` objects)

#### JavaScript to English
_3 points each, 45 points total_

State what these expressions evaluate to in plain English. Supply (a) what is being expressed (`expression`—similar to the way the earlier sections are phrased), (b) the final data type of the value with any helpful details like length or properties (`dataType`), and (c) the value itself (`value`). Place your answers in an object assigned to a variable named `javaScriptToEnglish` in _exercises.js_. The answers themselves are objects, with properties `expression`, `dataType`, and `value` for each of the requested portions. `expression` and `dataType` will be strings and `value` will be the final computed JavaScript value.

And yes, sometimes you will need to take operator precedence into account.

1. `"pie"`
1. `5 + 6 / 2`
1. `"ready" || "not"`
1. `!"nice"`
1. `4 > 5 <= 10`
1. `true && !false`
1. `!true || false`
1. `9 * 9 / 9`
1. `"night" + "and" + "day"`
1. `10 + "10"`
1. `[ { quantity: 2, ingredient: "egg" }, { quantity: 1, ingredient: "avocado" } ]`
1. `[ Math.pow(2, 0), Math.pow(2, 1), Math.pow(2, 2), Math.pow(2, 3) ]`
1. `{ sum: 2 + 3, product: 2 * 3, mod: 2 % 3 }`
1. `12 * 12 - 12 / -12 % 3`
1. `5 - 5 ? "no" : "yes"`

### Programs
_10 points each, 30 points total_

Write the following programs. Provide your code in the files specified.

1. (similar to textbook Chapter 3 Exercise 12) Write a JSFiddle two-dice-rolling program that (a) uses `addEventListener` to trigger an action when a `Roll Dice` control is clicked and (b) displays the dice as their equivalent Unicode codepoints (DIE FACE-1 to -6, respectively). Use CSS to spruce up how the dice look. Save these in files called _twoDice.html_, _twoDice.js_, and _twoDice.css_.
1. Modify one of your Khan Academy programs so that it groups related variables into an object definition instead. For example, if you had two variables `var birdX = 20;` and `var birdY = 300;`, rewrite these as `var bird = { x: 20, y: 300 };` instead. Save this new version (regardless of which) in a file called _khanWithObjects.js_.
1. (similar to textbook Chapter 3 Exercise 36) Write a JSFiddle program that takes a user’s input _as it is typed_ and displays that input appended to itself twice. For example, if the user types `"ho"`, the program should display `"hohoho"`. If the user types `"888"`, your script should display `"888888888"`. Save this in files called _appendTwice.html_, _appendTwice.js_, and, if applicable, _appendTwice.css_.

### Questions
_5 points each, 35 points total_

Answer the following questions. Provide these answers in a file called _questions.md_ (template provided). The file uses [Markdown (`.md`) format](https://guides.github.com/features/mastering-markdown/)—it can be thought of as “text with simple formatting markers.” The assignment writeups you’ve seen so far are written with Markdown—go ahead, try to edit them and see what shows up. If you need help with Markdown, ask me or any of the TAs.

1. Find five (5) published sentences or newspaper headlines that exhibit a kind of _structural_ ambiguity, such as “Seven foot doctors sue hospital.” Don’t choose phrases like “Red tape holds up bridge” because the ambiguity in the latter sentence is one of meaning only (both interpretations have the same sentence structure; it just so happens that _red tape_ and _holds up_ have alternative meanings). Cite the sources of each ambiguous construct.
1. How is the notion of ambiguity related to the theme of expressions/data for this assignment?
1. What if English and other languages had parentheses? Would it make the language less ambiguous? Provide three (3) concrete examples of why this would or would not be the case.
1. (textbook Chapter 3 Exercise 4) We saw in this chapter that `Math.sqrt(100)` evaluates to 10. The use of the dot makes it appear that `Math` is an object and `sqrt` is one of its properties. Is this true? Evaluate `Math["sqrt"](100)` in your favorite JavaScript environment and see if the result supports or refutes this hypothesis.
1. (textbook Chapter 3 Exercise 5) Use a shell to evaluate `~22`, `~105`, `~(~28)`, and a few other expressions involving `~` applied to whole numbers. Can you come up with a general rule for what this operator seems to do?
1. (similar to textbook Chapter 3 Exercise 20) What is the difference between `p["diddy"]` and `p[diddy]`?
1. (similar to textbook Chapter 3 Exercise 18) What is `q.b[2]` in:
```javascript
    var q = {
        a: 3,
        b: [ "fee", "fi", { f: "o" }, "fum" ]
    };
```


