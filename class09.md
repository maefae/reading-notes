# 201 class 09 Reading Notes: Forms and JS Events

This topic is important, because we need forms in order for a user and a website/app to have a way to interact with one another. 

## Reading Questions: 

[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
[Your first Web Form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form) 
[How To Structure A Web Form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

1. Why are forms so important in web development?

  because web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- Always take the time to think about your form and design a quick mockup
- Bigger the form, the more likely you are to frustrate users so keep it simple and stay focused on asking for the data you only need

3. List 5 form elements and explain their importance.

```markdown
- the **form** element essentially defines the form. it's a container element like the **main** element.
- the < label > element increases the accessibility of your website. Labels also are clickable which makes them useful for receiving user input.
- the **button** element gives people the ability to submit the form.
- The <input> element contains the most important attribute called "type". This attribute is extremely important because it defines the way the < input > element appears and behaves. 
```

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Intro to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

4. How would you describe events to a non-technical friend?
Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.

  For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage.

5. When using the addEventListener() method, what 2 arguments will you need to provide?
The name of the event and the a function to handle the event 

7. Describe the event object. Why is the target within the event object useful?
it is automatically passed to event handlers to provide extra features and information.
e/evt/event are most commonly used by developers because they are short and easy to remember. It's always good to be consistent — with yourself, and with others if possible

7. What is the difference between event bubbling and event capturing?
Event capturing means propagation of event is done from ancestor elements to child element in the DOM while event bubbling means propagation is done from child element to ancestor elements in the DOM

# Bookmark and Review
[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)

## Things I wanna know more about
Ways I can utilize events to solve real world problems
