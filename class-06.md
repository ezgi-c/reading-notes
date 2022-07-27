[Home](/README.md)

# Class 06 - JS Object Literals, the DOM

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?  
    I would use a metaphor, describing object as a suitcase. An object property would be an item of clothing with a value such as maybe its color. An object method would be a hair drier which has a functional use.
2. What are some advantages to creating object literals?  
    Advantages of creating object literals are containing related data in one object to make sending data more efficient and easier to use than arrays when it comes to accessing the data.
3. How do objects differ from arrays?  
    Object members have names and values and are easier to access.
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.  
    An example would be when the object property is defined dynamicaaly based on user input.
5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?  
    `this` refers to the object `dog`. The advantage of using `this` is we can re-use the method across different object literals.

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

## Introduction To The DOM

1. What is the DOM?  
Document Object Model is a programming interface for web documents.
2. Briefly describe the relationship between the DOM and JavaScript.  
JavaScript uses the DOM interface to manipulate elements of the page.
