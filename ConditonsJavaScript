// Exercise 1: Multiple Conditions
// Write a program that takes a number as input and displays "Positive" if the number is positive, "Negative" if it's negative, and "Zero" if it's equal to zero.

var number = null;

if (number > 0){
  console.log("Positive")
} else if (number < 0){
  console.log("Negative")
} else if (number === 0){
  console.log("Zero");
}

// Exercise 2: Nested Conditions
// 1. Write a program that asks the user to enter their age.
// 2. Depending on the user's age, display different messages. For example, if the user is under 18 years old, display "Minor". If the user is between 18 and 65 years old, display "Adult". If the user is 65 years old or older, display "Senior".
let userInput = prompt("How old are you?");
let userAge = parseInt(userInput); // parseInt: converts the user's input into an integer. It is a JavaScript function that converts a string to an integer.

if (userAge < 18){
  console.log("You are a minor")
} else if (userAge >=18 && userAge <= 65){
  console.log("You are an adult")
} else if (userAge >= 65){
  console.log("You are a senior")
}

// Exercise 3: Logical Operators
// 1. Write a program that asks the user to enter two numbers.
// 2. Use conditions to determine if both numbers are positive. Display "Both numbers are positive" if they are. Otherwise, display an appropriate message.
let askUser = prompt("Enter the first number");
let firstNumber = parseInt(askUser);

askUser = prompt("Enter the second number");
let secondNumber = parseInt(askUser);

if (firstNumber >= 0 && secondNumber >= 0){
  console.log("Both numbers are positive");
} else {
  console.log("At least one of the numbers is negative");
}

// Exercise 4: Ternary Operators
// Rewrite exercise 1 using the ternary operator to simplify the code.
var number = 15;
var message = (number > 0) ? "Positive" : (number < 0 ? "Negative" : "Zero");
console.log(message);

// Exercise 5: Strict and Non-Strict Equalities
// Compare two variables containing values of different types (for example, a number and a string) using both the strict equality operator (===) and the non-strict equality operator (==). Observe how they react differently.

var number = 10;
var string = "10";

console.log("Strict Equality (===):");
console.log(number === string); // Returns "false" because the types are different

console.log("Non-Strict Equality (==):");
console.log(number == string); // Returns "true" because the values are equivalent after conversion
