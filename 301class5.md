[Home](/README.md)

# Class 05 - Putting it all together

## React Docs - Thinking in React

1. What is the `single responsibility principle` and how does it apply to components?  
    It is a technique that explains that a component should only do one thing. If the component grows complex, it should be divided into sub components.
1. What does it mean to build a ‘static’ version of your application?  
    It means to build the components with only render() methods and props. This renders the UI without any interactivity. This step is the first step of building the application as it doesnt require a lot of thinking and creates all the reusable components.
1. Once you have a static application, what do you need to add?  
    After building the static application, next step is to add the parts that are interactive. We achieve this by adding state.
1. What are the three questions you can ask to determine if something is state?  
    >
    >1. Is it passed in from a parent via props? If so, it probably isn’t state.
    >1. Does it remain unchanged over time? If so, it probably isn’t state.
    >1. Can you compute it based on any other state or props in your component? If so, it isn’t state.
    >
1. How can you identify where state needs to live?  
    First we identify each component that needs the state to render something, and place the state in the component that these components have in common higher up in the hierarchy.

## Higher-Order Functions

1. What is a “higher-order function”?  
    A higher-order function takes in as argument or returns other functions.
1. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?  
    Line 2 of the function, `return m => m > n;`, returns an arrow function which has `m` as its parameter/argument.
1. Explain how either `map` or `reduce` operates, with regards to higher-order functions.  
    Both `map` and `reduce` are methods/higher-order functions that take in callback functions as arguments. In the following example, `arr.map(obj => {return obj.name;})`, the `map` method iterates over an array of objects and applies the function it takes as an argument to each object in the array.