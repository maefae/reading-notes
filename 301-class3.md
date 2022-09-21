# 301 class 3 Reading Notes - Passing Functions as Props
Why is this topic important?

[React Docs - List and Keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?
Returns a new array by calling a function and iterating through every element in the calling array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
You can use .map() to loop through an array and display each value

3. Each list item needs a unique ____key.

4. What is the purpose of a key?
to make each list item unique (readabiilty increase)

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. What is the spread operator?
represented with three dots (...), the spread operator gives you the ability to quickly copy all or part of an existing array or object into another object.

2. List 4 things that the spread operator can do.
- Copy an array
- Add to state in React
- Combine objects
- Use an array as an argument

3. Give an example of using the spread operator to combine two arrays.
```markdown
    const arrOne = [1,2,3];
    const arrTwo = [4,5,6];
    const combArr = [...arrOne,...arrTwo]; // [1,2,3,4,5,6]
```

4. Give an example of using the spread operator to add a new item to an array.
```markdown
    let numbers = [1, 2, 3, 4];
    numbers = [9, ...numbers];
    // numbers = [9, 1, 2, 3, 4]
```

5. Give an example of using the spread operator to combine two objects into one.
```markdown
    let objOne = { name: 'bob' };
    let objTwo = { id: 12 };
    let newObject = { ...objOne, ...objTwo };
    // newObject = { name: 'bob', id: 12 }
```

# Videos

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?
First step is to make a function that would be passed to the child component

2. In your own words, what does the increment function do?


3. How can you pass a method from a parent component into a child component?


4. How does the child component invoke a method that was passed to it from a parent component?

# Bookmark and Review
- [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)
