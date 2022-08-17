# 201 Reading Notes - Class 03: HTML Lists, Control Flow with JS, and the CSS Box Model

## Links to Coding Guides
[learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
[order lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
[unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## Queestions 

1. When should you use an unordered list in your HTML document?
You should use an unordered list when you're trying to list something that no numerical ordering

3. How do you change the bullet style of unordered list items?
Either by using CSS to style the bullet points or by nesting the bullets in each other with HTML

5. When should you use an ordered list vs an unordered list in your HTML document?
You should used an unordered list to create a list of related items, but in no particlar order. 
You should use ordered lists to create a list of related items in a specific order

7. Describe two ways you can change the numbers on list items provided by an ordered list?
You can use the <li> tag nested within the <ol> tag to produce regular numbers.
<ol>
  <li>item 1</li>
</ol>
 
 You can use the <ol type="i"> tag to change the numbers to be roman numerals 
 example: 
 <ol type="i">
  <li>roman numeral i</li>
</ol> 

[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
The Box Model.

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
2. List and describe the four parts of an HTML elements box as referred to by the box model.

[learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
[arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
[loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

1. What data types can you store inside of an Array?
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
List five shorthand operators for assignment in javascript and describe what they do.
Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
Describe a real world example of when a conditional statement should be used in a JavaScript program.
Give an example of when a Loop is useful in JavaScript.
