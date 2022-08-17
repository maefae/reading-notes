# 201 Reading Notes - Class 03: HTML Lists, Control Flow with JS, and the CSS Box Model

This topic matters because lists help us organize and eventually help functions 

## Links to Coding Guides
[learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
[order lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
[unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## Questions 

1. When should you use an unordered list in your HTML document?
You should use an unordered list when you're trying to list something that no numerical ordering

3. How do you change the bullet style of unordered list items?
Either by using CSS to style the bullet points or by nesting the bullets in each other with HTML

5. When should you use an ordered list vs an unordered list in your HTML document?
You should used an unordered list to create a list of related items, but in no particlar order. 
You should use ordered lists to create a list of related items in a specific order

7. Describe two ways you can change the numbers on list items provided by an ordered list?
You can use the <li> tag nested within the <ol> tag to produce regular numbers.
example:
<ol>
  <li>item 1</li>
</ol>
 
 You can use the <ol type="i"> tag to change the numbers to be roman numerals 
 example: 
 <ol type="i">
  <li>roman numeral i</li>
</ol> 

[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
  
  
2. List and describe the four parts of an HTML elements box as referred to by the box model.
  
  anatomy of a block box in CSS:

"Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
Padding box: The padding sits around the content as white space; size it using padding and related properties.
Border box: The border box wraps the content and any padding; size it using border and related properties.
Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties."
  
  ![box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model/box-model.png)
  - (https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

[learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
[arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
[loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

1. What data types can you store inside of an Array?
  strings, numbers, objects, and other arrays
  
Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why? 
The people array is valid. You can access it by using brackets that call the index of the value. for example, console.log(people[3][3]); would display the "artist" string in the console.

const people = [
  ['pete', 32, 'librarian', null],
  ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'],
  ['bill', null, 'artist', null],
];
List five shorthand operators for assignment in javascript and describe what they do.
‘x += y’ - Adds y to x and placed the result in x
‘x *= y’ - Multiplies y and x and places the result in x
‘x /= y’ - Divides x by y and places the result in x
‘x &= y’ - Performed a logical AND operation on x and y, and places the result in x
‘X++’ - Increments x by 1 (equivalent of x = x + 1)
- Read the code below and evaluate the last expression and explain what the result would be and why.

let a = 10; let b = 'dog'; let c = false;

// evaluate this (a + c) + b;

(10 + false) + b

the answer is '10dog' because the c is a boolean

Describe a real-world example of when a conditional statement should be used in a JavaScript program
a conditional statement should be used when trying to decide what healthy option to eat. If you choose a healthy option, the food will be made for you. If it's something unhealthy, the response will be "choose something healthy".

Give an example of when a loop is useful in JS
A loop is useful in JS when something needs to "loop" until a condition is met. 

for example: let's say you ask a question, but the answer is incorrect. A loop can repeat the question until it's correct.

 (Links to an external site.)Things I want to know more about
I want to learn more about arrays and practice how to access them
