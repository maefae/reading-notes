# 201 Class Notes - Class 07: Object-Oriented Programming, HTML Tables

201 Class Notes - Class 07: Object-Oriented Programming, HTML Tables

This topic is important because we don't have to create nearly as many objects.

# Reading Questions

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Explain why we need domain modeling.  

We need domain modeling because it helps govern the development of an application more easily. Can also support the comprehension of a specific problem among various stakeholders. 

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

2. Why should tables not be used for page layouts?

Tables produce tag soup. Tables were intended to be used for presenting tabular data. Layout tables reduce accessibility for visually impaired users. Tables are not automatically responsive.

3. List and describe 3 different semantic HTML elements used in an HTML

 Every table's content is enclosed by the table tags. Add these inside the body of your HTML doc. 

A table cell is the smallest container inside a table, and it's created by a td tag element (td = table data). Each td tag element creates a single cell that makes up the first row. Every cell you add makes the row become bigger. To make the row quit increasing in size and start placing subsequent cells on the second row, you need to use the tr tag (table row) element.

to summarize in a simpler fashion:

<tr table row designates a new row to be filled with:
<td table data, containers for data, contained by <tr like: <li inside of <ol
<th table header, used in place of <td, works the same way but has styling to make it stand out.

# Introducing Constructors

4. What is a constructor and what are some advantages to using it? How does the term this differ when used in an object literal versus when used in a constructor? 

A constructor is like an object literal, but you can create more than one object which saves coding space. Also, if we want to change some properties of the object - like adding a height property - then we should remember to update every object.

[Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

5. Explain prototypes and inheritance via an analogy from your previous work experience. NOTE: This is a very common front end developer interview question. 

the lab inherits the tissue samples (prototypes) from the medical courier, and the medical courier inherits the prototypes from clinics where the nurses inherit the tissue samples from their patients

# Bookmark and Review

[HTML Table Advanced Features and Accessibility](HTML Table Advanced Features and Accessibility)

# things I wanna know more about

I need to re-read these articles to understand them better. 
  
  
