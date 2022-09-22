# Class 301 Reading Notes- React and Forms
Why is this topic important?
because forms are how data is collected and passed in react.

[React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?

They are components where the form data is handled by the component’s state.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

should not wait to store the users responses. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

3. How do we target what the user is entering if we have an event handler on an input field?
Using the value of: event.target.name.

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

1. Why would we use a ternary operator?
It is an expression that returns a value and requires less code to write.

2. Rewrite the following statement using a ternary statement:

```markdown
    if(x===y){
      console.log(true);
    } else {
      console.log(false);
    }
```
Rewritten:
```markdown
    console.log(x === y ? true : false);
```


# Bookmark and Review
React Bootstrap - Forms
React Docs - conditional rendering

# Things I wanna know more about
More about forms in react
