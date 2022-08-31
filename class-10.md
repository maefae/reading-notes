# 201 Reading Notes: Class 10 - Debugging

This topic is important because debugging helps the programmer figure out how to fix issues in their code or someone elses.

## Reading Questions

[What Went Wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

Name some key differences between a Syntax Error and a Logic Error.
  **Syntax errors**: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — 
  you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools 
  and know what the error messages mean!
  
  **Logic errors**: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives
  incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
I had a javascript syntax error where a function would not work and after what felt like hours of trying to figure it out, I realized it was because I had capitalized 
the name of the function but had the invocation of the function lower-cased. 

Another error I came across was a logic error where the questions on my guessing game repeated entirely twice. I realized it was literally because I had accidentally 
wrote the line of code twice

How will this topic continue to influence your long term goals?
  It 

[The JavaScript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
  The Javascript Debugger tool is in the browser. It allows you to examine your code and evaluate each value/variable and set up breakpoints to help you determine where the code stopped working.

Define what a breakpoint is
 A breakpoint allows you to isolate sections of code to determine where things went wrong in the code project. You can set breakpoints to pause execution at a certain place in your code to see if it works or does not work.

What is the call stack?
 The **call stack** shows you what code was executed in order to get to the current line

#Bookmark and Review
[Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

[Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)

## Things I wanna know more about
- how to use the call stack as well as other tools for debugging
