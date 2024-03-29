# Command Line Programming Quiz

## Description
Create a programming quiz on the command line to test the skill of your fellow students.


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand JavaScript expressions
* Understand JavaScript types
* Understand JavaScript variables
* Understand boolean logic
* Understand control flow with if / else / if else statements


### Performance Objectives

After completing this assignment, you be able to effectively use

* Math object
* variables
* booleans
* numbers
* strings



## Details

### Deliverables

* A repo containing at least:
  * `main.js`

### Requirements

* No eshint warnings or errors


## Normal Mode
Create a quiz for your fellow classmates to take. The quiz should ask at least 15 HTML, CSS and JavaScript related questions. For each of the questions your program should ask the question using console.log and prompt the test taker for an answer. Keep track of the number of total answers that the test taker answers correctly. When the test taker has answered all of the questions display the total number of questions that they answered correctly as well as the percentage that they got right.

## Hard Mode
* If a test taker gets an answer correct your test should immediately tell them that they were correct. If the test taker gets a question wrong it should tell them that they were wrong and tell them the correct answer.
* Your answers should be case insensitive. For example, if the answer to a particular question is **div** the test taker should be able to answer **DIV** or **div** or **dIV** and any of those answers should be counted as a correct answer.
* Try to time the test and inform the user how long they took to complete the test at the end.

## Nightmare Mode
* Make your test adaptive. If a user gets a question correct, give them a harder question next time. If they get a question incorrect, give them an easier question next time instead.
* After the test taker is done taking the test, inform them where they need to improve their skills based on the types of questions that they got wrong. If they answered all of the CSS questions correctly, but the HTML questions only got 50% tell them to brush up on their HTML skills, etc.

## Notes

You should use the [sync-prompt](https://github.com/shovon/sync-prompt) node module to accept user input. You will need to use `npm` to install sync-prompt and `var prompt = require('sync-prompt')` to use it within your code.

## Additional Resources

* Read []()
