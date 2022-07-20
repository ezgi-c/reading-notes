[Home](/README.md)

# Class 03 - HTML Lists, CSS Boxes, JS Control Flow

## HTML - Ordered and Unordered lists

1. When should you use an `unordered list` in your HTML document?  
We use and `unordered list` when the order of the list items do not matter.
2. How do you change the `bullet style` of `unordered list` items?  
We can use the `type` attribute i.e. `<ol type="disc">` or `list-style-type` property in CSS.
3. When should you use an `ordered list` vs an `unordered list` in your HTML document?  
We use an `ordered list` when the order of the list items are important. For example, step by step instructions.
4. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?  
It can be changed by the `type` attribute in HTML or `list-style-type` property in CSS.

## CSS - The Box Model

1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?  
`margin` is the distance between a block box and rest of the items on a page. `padding` is the space between the border of the box and its contents.
2. List and describe the four parts of an HTML elements box as referred to by the `box model`.  
From [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model):

>- Content box: The area where your content is displayed; size it using properties like `inline-size` and `block-size` or `width` and `height`.
>- Padding box: The padding sits around the content as white space; size it using `padding` and related properties.
>- Border box: The border box wraps the content and any padding; size it using `border` and related properties.
>- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using `margin` and related properties.

## JS - Arrays. Operators and Expressions. Conditionals. Loops

1. What `data types` can you store inside of an `Array`?  
"list-like objects"
2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?  

    ```js
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    ```

    Yes, this is a multidimensional array. Values can be accessed like this: 

    ```js 
    console.log(people[0]); // to access the first array within the array which is:
    ['pete', 32, 'librarian', null] // and so on.
    ```

3. List **five** shorthand operators for assignment in javascript and describe what they do.
4. Read the code below and evaluate the last `expression` and explain what the result would be and why.

    ```js
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;
    ```

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
6. Give an example of when a `Loop` is useful in JavaScript.
