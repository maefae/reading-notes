# 301 Class 2 - State and Props
Why is this topic important?
So you can know when to use state and props in react.

## Reading Questions
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  The 'render' stage happens first
3. What is the very first thing to happen in the lifecycle of React?
  Mounting
5. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  constructor, render, React Updates, componentDidMount, react updates, and componentWillUnmount
7. What does componentDidMount do?
the method is invoked immediately after a component is mounted. This is where network requests go or to initialize the DOM or load things the network requests

## Videos

1. What types of things can you pass in the props?
  Props are like arguments to a function. 
  Let's say you have a counter app. The thing you're most likely to pass is the initial count (what your count should start at). You're going to pass your counter component, it's initial count, inside of the props. So you can pass things like strings and numbers.
  
2. What is the big difference between props and state?
   state is handled in the component and you can update it inside of the component. Props are outside of the component and are updated outside of the component. WHen you change the state inside of your application, it's going to re-render that section of your app. Props cannot be changed. You have to change them outside of the component and it's most likely going to be stored somewhere else in your app that's being passed down as props. it just displays it instead of changing it. 
   
3. When do we re-render our application?
  to change something, you have to use state so that it can re-render

4. What are some examples of things that we could store in state?
  You can create a count by passing it as a prop, but it updates with state. You can create dynamic elements within the application, if you want the title or description to change based on user input you would store it in state

## Bookmark and Review
React Docs - State and lifecycle
https://reactjs.org/docs/state-and-lifecycle.html

React Docs - Handling Events
https://reactjs.org/docs/handling-events.html

React Tutorial through 'Developer Tools'
https://reactjs.org/tutorial/tutorial.html

React Bootstrap Documentation
https://react-bootstrap.github.io/

Bootstrap Cheatsheet
https://getbootstrap.com/docs/5.0/examples/cheatsheet/

Bootstrap shuffle -a class "sandbox"
https://bootstrapshuffle.com/classes

Netlify
https://www.netlify.com/
------------ 
### Sources
[React Lifecycle}(https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
[react State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

## Things I wanna know more about
How to use states and props 

