# Reading Notes for class 8 - JS [Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators) and [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

# (Review) What is the difference between:
= ; assignment operator --> GIVING something it's value. You are saying, "yes this thing has this value"

==; comparing -- this thing = that thing

===; this thing strictly = that thing

# Assignment operators

An **assignment operator** assigns a value to its left operand based on the value of its right operand. 
The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. 
That is, x = f() is an assignment expression that assigns the value of f() to x.

3                  +          4
operand 1     operator    operand 2

      assignment operator
x           =                  3

++ = add one
```markdown
let x = 0;
console.log(x);
x += 3 //x = x + 3
console.log(x);

x -= 1 //x = x - 1
console.log(x);
```

Assigning to properties
If an expression evaluates to an object, then the left-hand side of an assignment expression may make assignments to properties of that expression. For example:
```markdown
let obj = {};

obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj[key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5 }.
```
Examples of Operators include:
=, != (not equal), !== (strict, not equal), etc.

# Comparison Operators

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. 
The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. 
In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. 
This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, 
which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. 
The following table describes the comparison operators in terms of this sample code:

```markdown
const var1 = 3;
const var2 = 4;

another example:

let y = 5
let x = "5"

console.log(x==y) - output equals true because == is not strict so it sees the numbers as the same
console.log(x===y) - output is false because ==== strictly adheres to data types including numbers and strings
```
```markdown
## Truth Tables
Let x = true;
let y = true;

console.log(x && y) - output is true
----
Let x = true;
let y = true;

console.log(x || y) - (|| = or) output is true 

or

Let x = true;
let y = true;

console.log((x == y) && (x===)) - output is false
```

# for statement
A **for loop** repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

```markdown
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
```

# while statement

A **while statement** executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:
```markdown
while (condition)
  statement
```
