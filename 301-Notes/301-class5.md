# 301 Class 5 Reading Notes - Putting it all together

[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. What is the single responsibility principle and how does it apply to components?
  single responsibility principle is a component should only be doing one thing.

2. What does it mean to build a ‘static’ version of your application?
 A 'static' version of an app renders the UI but doesn't have a 'state' or any interactivity.
 
3. Once you have a static application, what do you need to add?
Add state to make your app/site interactive

4.What are the three questions you can ask to determine if something is state?
- Is it passed in from a parent using props? If so, it probably doesn’t have state.
- Does it remain unchanged? If so, it probably doesn’t have state.
- Can you compute it based on any other state or props  in your component? If so, it probably doesn’t have state.

5. How can you identify where state needs to live?

- Identify ever component that renders something based on that state.
- Find a common owner component above all other components that needs state.
- Either the common owner component or another component higher up in the hierarchy should own state.
- If you can’t find a common owner component to own state, make a new component responsible for holding state and make sure it is above the common owner component in the hierarchy.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. What is a “higher-order function”?
  It is a function that operates on other function by either taking them as arguments or returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  It is checking to see if a number is greater than another number, and it will return either true or false.

3. Explain how either map or reduce operates, with regards to higher-order functions.
  The map methods will transform the data by applying a function to all the elements and it will build a new array from the new returned values.

## Things I wanna know more about
I want to become more efficient in making static apps interactive with state.
