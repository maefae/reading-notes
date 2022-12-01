Readings: Express REST API

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

Classes are a template for creating ____.
- objects 

Can a class declaration be hoisted?
- a class will reject being hoisted because they have to be defined before they're constructed

How would you describe a constructor and contextual “this” to a non-technical friend?
- Let's say you have a coffee machine that only produces drip. Same as the contextual, the coffee
maker will always have the same result. 
contextual 'this' = the coffee
constructor = coffee maker.

# Using Express Routing

Within Express, what does routing refer to?
- Routing refers to how an app's endpoints respond to client requests.

What is the difference between a route path and a route method?
- a route method comes from a HTTP metod and attaches to an instance of an express class. Whereas, a route path can be used in conjunction with a method to create an end point.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?


# Express Routing

What is an Express Router?
- a mini instance of the express app. It can only contain the routing functionality.

2. By what mean do we initialize express.Router() in an express server?
- to intialize: let router = express.Router();

3. What do we use route middleware for?
To handle anything we'd like before the request is complete. This can include verifying whether the data is correct, or to confirm that the user is authenticated, etc.

# Reflection

What are your learning goals after reading and reviewing the class README?
