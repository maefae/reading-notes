# 201 reading notes for class 1 - 
# [How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

It's important to understand how the web works in order to truly understand the very foundation which one will be learning about in their journey through tech. Building a strong foundation will allow the future software developer to see the bigger picture.


## Clients and Servers
Clients and servers are computers connected to the web.
![client and server](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works/simple-client-server.png)

**Clients** are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).

**Servers** are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

## Other parts of the toolbox
**Internet connection**: allows you to send and receive data on the web
**TCP/IP**: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet
**DNS**:  Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website
**HTTP**: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other.
**Component files**: A website is made up of many different files, which are like the different parts of the goods you buy from the shop. These files come in two main types:
 - Code files: Websites are built primarily from HTML, CSS, and JavaScript, though you'll meet other technologies a bit later.
 - Assets: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

## What happens when you type a webaddress into your browser?

1. The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
2. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
3. If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
4. The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

## Order in which component files are parsed *
When browsers send requests to servers for HTML files, those HTML files often contain <link> elements referencing external CSS stylesheets and <script> elements referencing external JavaScript scripts. It's important to know the order in which those files are parsed by the browser as the browser loads the page:
  
  - The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
  
  - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
  
  - The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
  
  - As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

# Web Design and Process - what will your website look like?
## Planning
Ask yourself questions like,
1. What is your website about? Do you like dogs, New York, or Pac-Man?
2. What information are you presenting on the subject? Write a title and a few paragraphs and think of an image you'd like to show on your page.
3. What does your website look like, in simple high-level terms? What's the background color? What kind of font is appropriate: formal, cartoony, bold and loud, subtle?

## Sketching 
![sketch](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like/website-drawing-scan.png)

## Choosing assets
such as font, text, images, and so on
  
 ### To choose a color, 
go to the Color Picker and find a color you like. When you click on a color, you'll see a strange six-character code like #660066. That's called a hex code (short for hexadecimal), and represents your color
  
### How can you find images to add to a website? *
  
1. To choose an image, go to Google Images and search for something suitable.
2. When you find the image you want, click on the image to get an enlarged view of it.
3. Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.

###  Font
To choose a font:

1. Go to Google Fonts and find one you like.
2. Copy the lines of code Google gives you into your text editor to save for later.
  
# [Javascript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
**JavaScript** is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. 

The language was written by Brendan Eich.
  
 ## Variables
Variables are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable:
  
  ### Types of Variables
String:	This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks.	let myVariable = 'Bob';
  
Number:	This is a number. Numbers don't have quotes around them.	let myVariable = 10;
  
Boolean:	This is a True/False value. The words true and false are special keywords that don't need quote marks.	let myVariable = true;
  
Array:	This is a structure that allows you to store multiple values in a single reference.	let myVariable = [1,'Bob','Steve',10];
Refer to each member of the array like this:
myVariable[0], myVariable[1], etc.
 
Object:	This can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn.	let myVariable = document.querySelector('h1');
  
### Comments
// this is a single lined comment
  
  /*
Everything in between is a comment.
*/
  
  ### Operators
  A mathematical symbol that produces a result based on two values (or variables).
  
### Conditionals
Conditionals are code structures used to test if an expression returns true or not. A very common form of conditionals is the if...else statement.
  
 ### Functions
Functions are a way of packaging functionality that you wish to reuse. It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code. You have already seen some uses of functions.
  
  ### Events
Real interactivity on a website requires event handlers. These are code structures that listen for activity in the browser, and run code in response. The most obvious example is handling the click event, which is fired by the browser when you click on something with your mouse.
  
  # QUESTIONS
  
 1. Compose a short poem describing how HTTP sends data between computers.
  ## HTTP Poem 
http, I'll forever be in your browser. 
Asking you to send me a site of you in your trousers
Sending me little messages 
You're speaking all my languages
I want the clearest copy, 
no need to get sloppy 
use icp/ip, cause I wanna see you entirely
  
  
2. Describe how HTML, CSS, and JS files are “parsed” in the browser
  
  When browsers send requests to servers for HTML files, those HTML files often contain <link> elements referencing external CSS stylesheets and <script> elements referencing external JavaScript scripts. It's important to know the order in which those files are parsed by the browser as the browser loads the page:
  
  - Browser parses HTML first, which leads to the browser checking for any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
  
  - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
  
  - The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
  
  - As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
  
  - How can you find images to add to a Website?
  
  3. How can you find images to add to a website? 
- To choose an image, go to Google Images and search for something suitable.
- When you find the image you want, click on the image to get an enlarged view of it.
- Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.
    
4. How do you create a String vs a Number in JavaScript?
  a string is created by using quote marks ("") For example: let myVariable = 'bob; or "bob";
  A number does not require quote marks and can be created by simply saying something like, let myVariable = 10
  
5. What is a Variable and why are they important in JavaScript?
A variable is a container that stores values. It's important in Javascript to declare a variable to a value, because if values couldn't change, then you couldn't do anything dynamic (like personalize a greeting message or change an image displayed in an image gallery).
  
  # Introduction to HTML
  
1. What is an HTML attribute?
  Attributes contain extra information about the element that won't appear in the content 
  for example: <p class ="editor-note">My cat is very grumpy</p>
  
2. Describe the Anatomy of an HTMl element.
  ![anatomy](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png)

  The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
  
The content: This is the content of the element. In this example, it is the paragraph text.
  
The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.
  
The element is the opening tag, followed by content, followed by the closing tag.
  
3. What is the Difference between <article> and <section> element tags?
  <article> tags enclose a block of related content that makes sense on its own without the rest of the page (for ex: a single blog post)
    whereas <section> tags are similar, but more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. 
    
4. What Elements does a “typical” website include?
    - header: <header>.
    - navigation bar: <nav>.
    - main content: <main>, with various content subsections represented by <article>, <section>, and <div> elements.
    - sidebar: <aside>; often placed inside <main>.
    - footer: <footer>.
    
5. How does metadata influence Search Engine Optimization?
    Metadata increases your SEO efforts because it's written in the search engine's language. It aids search engines by providing a better understanding the topic of your webpages and content. It also helps them display more relevant results to searchers
    
6. How is the <meta> HTML tag used when specifying metadata?
    The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data. <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
    
   ### How to start to design a Website.

1. What is the first step to designing a Website?
    define what you want to accomplish with it.
    
2. What is the most important question to answer when designing a Website?
    What exactly do I want to accomplish?
   
    ### Semantics.

1. Why should you use an <h1> element over a <span> element to display a top level heading?
    because <h1> easily and quickly automatically adjusts the size of the font whereas with span you have to be more intricately detaield

2. What are the benefits of using semantic tags in our HTML?
    Giving the webpage a more interesting and dynamic visual appearance with different sized texts
    
3. What is JavaScript?
    Javascript is a scripting language that runs in the browser (also in your 
local environment with NodeJS)
    
JS is behind every action/interaction you have performed on the browser
With JS you can create web apps that will run on any machine with a browser
    
    ### What is javascript?

1. Describe 2 things that require JavaScript in the Browser?
    A very common use of JavaScript is to dynamically modify HTML and CSS to update a user interface, via the Document Object Model API
    
    When the browser encounters a block of JavaScript, it generally runs it in order, from top to bottom. This means that you need to be careful what order you put things in. 
    
2. How can you add JavaScript to an HTML document?
    Three ways:
   ## internal:
    make a local copy of our example file apply-javascript.html. Save it in a directory somewhere sensible.
Open the file in your web browser and in your text editor. You'll see that the HTML creates a simple web page containing a clickable button.
Next, go to your text editor and add the following in your head — just before your closing </head> tag:
<script>

  // JavaScript goes here

</script>
Copy to Clipboard
Now we'll add some JavaScript inside our <script> element to make the page do something more interesting — add the following code just below the "// JavaScript goes here" line:
document.addEventListener('DOMContentLoaded', () => {
  function createParagraph() {
    const para = document.createElement('p');
    para.textContent = 'You clicked the button!';
    document.body.appendChild(para);
  }

  const buttons = document.querySelectorAll('button');

  for (const button of buttons) {
    button.addEventListener('click', createParagraph);
  }
});
Copy to Clipboard
Save your file and refresh the browser — now you should see that when you click the button, a new paragraph is generated and placed below.
    
    ## externally: 
    First, create a new file in the same directory as your sample HTML file. Call it script.js — make sure it has that .js filename extension, as that's how it is recognized as JavaScript.
Replace your current <script> element with the following:
<script src="script.js" defer></script>
Copy to Clipboard
Inside script.js, add the following script:
function createParagraph() {
  const para = document.createElement('p');
  para.textContent = 'You clicked the button!';
  document.body.appendChild(para);
}

const buttons = document.querySelectorAll('button');

for (const button of buttons) {
  button.addEventListener('click', createParagraph);
}
Copy to Clipboard
Save and refresh your browser, and you should see the same thing! It works just the same, but now we've got our JavaScript in an external file. This is generally a good thing in terms of organizing your code and making it reusable across multiple HTML files. Plus, the HTML is easier to read without huge chunks of script dumped in it.
    
   ## Inline JavaScript handlers
Note that sometimes you'll come across bits of actual JavaScript code living inside HTML. It might look something like this:

function createParagraph() {
  const para = document.createElement('p');
  para.textContent = 'You clicked the button!';
  document.body.appendChild(para);
}
<button onclick="createParagraph()">Click me!</button>

   ## Things I wanna know more about
   
Javascript and how to create games 
