[Home](/README.md)

# Class 07 - HTML Tables, JS Constructor Functions

## Domain Modeling

1. Explain why we need domain modeling.

    I did not really understand this concept.

## HTML Table Basics

1. Why should tables not be used for page layouts?

    Layout tables reduce accesibility for visually impaired users, make code harder to write and edit, and they are not automatically resposive and require more measures to correctly size.

2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.

    `<thead>`: head section of table; top row with headers
    `<tbody>`: body section of table; contains the data rows.
    `<tfoot>`: footer section of table; bottom row.

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?

    Constructors are functions used to create objects. Advantage of using constructors is to significantly reduce size of our code when we are creating more than one object. We can use the paramenters of the constructor functions to create many objects easily with different arguments.

2. How does the term `this` differ when used in an object literal versus when used in a constructor?
    
    When used in constructor, `this` is a placeholder for whatever object will be created by the contructor. In an object literal, `this` is used within the object to refer to itself.
