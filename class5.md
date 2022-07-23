# CSS

## What is CSS?
(Cascading Style Sheets) allows you to create great-looking web pages! CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

**document** is typically a text that's structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

**Presenting** a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector, or printer.

## CSS Syntax
CSS is a rule-based language where you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page. 
```markdown
h1 {
    color: red;
    font-size: 5em;
}
```
## Three methods to link your style (CSS) to your page
- External CSS: Separate CSS file is referenced to the HTML doc 
for example: 
```markdown
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
```
- Internal CSS: Utilize the < style> </style > tag within the html doc
- Inline CSS: use css within an html tag. 
For example: <h1 style="color:blue;text-align:center;">I am a happy heading.</h1>
