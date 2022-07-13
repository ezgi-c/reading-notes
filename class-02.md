[Home](/README.md)

# Class 02 - Basics of HTML, CSS & JS

This assignment goes deeper into learning about HTML, CSS and especially JavaScript. It is important to keep building on these concept as they make up the foundations of web development and even software development.

## HTML Text Fundamentals. HTML Advanced Text Formatting

1. **Why is it important to use semantic elements in our HTML?**

Semantic elements give meaning to content. For example, `<h1>` semantic element signifies that the content within the tags is the main heading. This is useful as it makes our code more meaningful. The contents of semantic elements are used as keywords by search engines. Using semantic elements also makes our code more accessible to visually impaired users as it optimizes the function of their screen reading aids.

2. **How many levels of headings are there in HTML?**

There are 6 heading levels in HTML. `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`. It is best practice to used the headings in this order in a single page, as in not to use a `<h1>` heading following an `<h2>` heading.

3. **What are some uses for the `<sup>` and `<sub>` elements?**

They format text into superscript and subscript respectively.

4. **When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?**

The `title` attribute.

## How CSS Is Structured

1. **What are ways we can apply CSS to our HTML?**

 We can apply it from an external file with a *.css* extension by linking it in the `<head>` section. We can also have the whole CSS code in the `<head>` section within `<style></style>` tasgs. Third way of applying is inline in `<body>` of the HTML, like so: `<p style="color:blue">content</p>`

2. **Why should we avoid using inline styles?**

It makes code harder to read and doesn't allow us to apply a certain style to multiple elements requiring us to repeat the code unnecessarily.

3. **Review the block of code below and answer the following questions:**

    ``` CSS
   h2 {
     color: black;
     padding: 5px;
   }
   ```

    1. What is representing the selector?

        `h2`

    2. Which components are the CSS declarations?

       `color: black;`

       `padding: 5px;`

    3. Which components are considered properties?

        `color`

        `padding`

## JavaScript Basics

1. **What data type is a sequence of text enclosed in single quote marks?**

string

2. **List 4 types of JavaScript operators.**

    1. Addition: `+`
    2. Subtraction, Multiplication, Division: `-`, `*`, `/`
    3. Assignment: `=`
    4. Strict equality: `===`
    5. Not, Does-not-equal: `!`, `!==`

3. **Describe a real world Problem you could solve with a Function.**

We can use a function to make a website more dynamic and interactive by changing the output based on user input.

## Making Decisions In Your Code – Conditionals

1. **An if statement checks a __ and if it evaluates to ___, then the code block will execute.**

conditon, true

2. **What is the use of an else if?**

`else if` follows an `if` statement and its resulting code. It displays a different condition than the `if` statement and results in a different outcome.

3. **List 3 different types of comparison operators.**

    1. strictly equals: `===`
    2. less than or equal to: `<=`
    3. not equal to: `!==`

4. **What is the difference between the logical operator `&&` and `||`?**

`&&`: AND, requires both expressions left and right og the operator to be `true` for the whole expression to be `true`;

`||`: OR, requires only one of the exdpressions to be `true`.

## Bookmark and Review

[How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
