[Home](/README.md)

# Class 01 - 7/9/2022

The topics for this reading assignment are a review of foundational concepts in web development. These are important to go over as we will be building upon these principles in the course.

## Getting Started with Web Development

1. **Compose a short poem describing how HTTP sends data between computers.**

*Hypertext Transfer Protocol*  
*HTTP*  
*Computers talk to each other*  
*Just like you and me*  
*Syntax, Semantics, Timing, are the elements we need*  
*When we send a message to the server, we get a response indeed*

2. **Describe how HTML, CSS, and JS files are “parsed” in the browser.**

The browser first parses the HTML file. After recognizing links to CSS and JavaScript files, it sends a request to the server to parse these files.

3. **How can you find images to add to a Website?**

We can find images on Google search. It is best to filter the images to find images with "Creative Commons License" to avoid violating copyright.

4. **How do you create a String vs a Number in JavaScript?**

A string is created by putting quotation marks around a value. i.e. `'value'`, `'23'`, etc.  
Numbers do not have quotation marks around them. i.e. `5`, `3+4` etc.

5. **What is a Variable and why are they important in JavaScript?**

Variable are containers we use to store values. Variables are important for creating dynamic elements as their value can be changed by user input and other factors.

## Introduction to HTML

1. **What is an HTML attribute?**

An HTML attribute contains extra information about an HTML element.  
i.e. `<div id="section1"></div>`  
In this example `id` is an attribute that helps us specify the element.

2. **Describe the Anatomy of an HTML element.**

An HTML element consists of opening and closing tags withing angle brackets which define the content that goes between them.  
i.e. `<tag>content</tag>`

3. **What is the Difference between `<article>` and `<section>` element tags?**

`<article>` tag holds content that stands on it's own without needing to relate to rest of the page. The `<section>` tag divides page into sections that need to be grouped together. `<article>` tags can be used within `<section>` tags anf vice versa.

4. **What Elements does a “typical” website include?**

A typical website include the following elements:

``` HTML
<!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title></title>
        </head>
        <body>
            <header>
            </header>
            <main>
            </main>
            <footer>
            </footer>
        </body>
    </html>
```

5. **How does metadata influence Search Engine Optimization?**

Search engines utilize the metadata content of websites when displaying them in search results.

6. **How is the `<meta>` HTML tag used when specifying metadata?**

Attributtes within the tag are used to specify metadata.  
i.e. `<meta charset="utf-8">` which specifies the document's character set encoding.

## How to start to design a Website

1. **What is the first step to designing a Website?**

First step of designing a website is *project ideation*; deciding what we want to accomplish with the website.

2. **What is the most important question to answer when designing a Website?**

"What do I want to accomplish?"

## Semantics

1. **Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**

Because `<h1>` is a semantic element which is an element that defines its contents.

2. **What are the benefits of using semantic tags in our HTML?**

Some benefits of using semantic elements over non-semantic elements include search engines considering their contents important keywords, making it easier for visually impaired readers to navigate a page through screen readers, making it easier to find meaningful blocks of code, and more.

## JavaScript

1. **Describe 2 things that require JavaScript in the Browser?**

Dynamically updating websites require JS. These websites are able to update their content and display under different circumstances. Being able to interact with the user also requires JS.

2. **How can you add JavaScript to an HTML document?**

JavaScript can be added internally or externally to an HTML document. Internally it is added in body of the page within `<script></script>` tag. Externally the JS file is linked in the `<head>` section of the document as follows: `<script src="script.js" defer></script>`
