# Problem Domain, Objects, and the DOM

This topic matters because objects help condense code by holding a collection of data.

# Reading Questions 
[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. How would you describe an object to a non-technical friend you grew up with?
An object is a collection of data that typically consists of several functions and variables (which are called properties and methods when they're inside objects)

3. What are some advantages to creating object literals?
Object literals are where you literally write out the object contents as you create it. It's easier to send a single object rather than several items individually. 
It's more efficient than working with an array when you want to identify individual items by name.

5. How do objects differ from arrays?
objects are stored in key value pair and the key can be anything whereas arrays store the data in an ordered collection in which the data can be accessed using a numerical 
index

7. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation
if an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable 
inside brackets.

```markdown
const person = {
  name: ['Bob', 'Smith'],
  age: 32
}
const input = prompt('Get name or age?')
console.log(person[input])
```

9. Evaluate the code below. What does the term **this** refer to and what is the advantage to using this?

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

The **this** keyword refers to the current object the code is being written inside — so in this case this is equivalent to person.
If you create more than one, this enables you to use the same method definition for every object you create.

[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

6. What is the DOM?
(document object model: data representation of the objects that comprise the structure and content of a document on the web. IT's a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

8. Briefly describe the relationship between the DOM and JavaScript.
The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node. js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.


# Bookmark and Review

[Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

[What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

# Things I wanna know about
How is the DOM and an object used in real life situations?
