reading notes for class 7 - [Javascript Functions](https://www.w3schools.com/js/js_operators.asp)
# Control Flow
The **control flow** is the order in which the computer executes statements in a script.
For example, imagine a script used to validate user data from a webpage form. 
The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. 
To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:
```markdown
if (field==empty) {
    promptUser();
} else {
    submitForm();
}
```
# Javascript Functions
A **JavaScript function** is a block of code designed to perform a particular task.
A JavaScript function is executed when "something" invokes it (calls it).
```markdown
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```
# Javascript Function Syntax

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}
```markdown
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```
Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

# Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)

# Javascript Operators
Assign values to variables and add them together:
```markdown
let x = 5;         // assign the value 5 to x
let y = 2;         // assign the value 2 to y
let z = x + y;     // assign the value 7 to z (5 + 2)
```
The **assignment** operator (=) assigns a value to a variable.
# Assignment
```markdown
let x = 10;
```
Assignment operators assign values to JavaScript variables.
```markdown
Operator	Example	Same As
=         x = y    x = y
+=        x += y  x = x + y
*=        x *= y  x = x * y
```
var - older version of variable
let - newer version
const - a variable that never changes
