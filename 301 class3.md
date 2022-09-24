[Home](/README.md)

# Class 03 - Passing Functions as Props

## React Docs - lists and keys

1. What does .map() return?  
   **.map() takes an array as input and returns a new array with the results of calling a function on each element of the input array.**
2. If I want to loop through an array and display each value in JSX, how do I do that in React?  
   **We can use curly braces `{}` to include the return of the .map() method in JSX. From reactjs.org:**

   > Below, we loop through the numbers array using the JavaScript map() function. We return a `<li>` element for each item. Finally, we assign the resulting array of elements to listItems:

   ```js
   const numbers = [1, 2, 3, 4, 5];
   const listItems = numbers.map((number) => <li>{number}</li>);
   ```

   >Then, we can include the entire listItems array inside a `<ul>` element:

    ```js
    <ul>{listItems}</ul>
    ```

3. Each list item needs a unique **key**.
4. What is the purpose of a key?  
    **A key uniquely identifies a list element from its siblings and gives it a stable identitiy.**

## The Spread Operator

1. What is the spread operator?  
    **The spread operator `(...)` is a syntax used for spreading an array into a function's arguments, combining arrays or objects, and adding items to an array.**
2. List 4 things that the spread operator can do.  
    - **Copying an array**
    - **Concatenating or combining arrays**
    - **Using Math functions**
    - **Using an array as arguments**
3. Give an example of using the spread operator to combine two arrays.  

    ```js
    const array1 = [`fall`,`is`,`here`]
    const array2 = [`leaves`,`are`,`falling`]
    const combinedArray = [...myArray,...yourArray]
    console.log(...combinedArray) // fall is here leaves are falling
    ```

4. Give an example of using the spread operator to add a new item to an array.  

    ```js
    const numbers = [1, 2, 3]
    const moreNumbers = [...numbers, 4, 5]
    console.log(moreNumbers) //  Array(5) [ 1, 2, 3, 4, 5 ]
    ```

5. Give an example of using the spread operator to combine two objects into one.  

```js
    const obj1 = {name: "Ezgi"}
    const obj2 = {lastName: "Coban"}
    const obj3 = {...obj1, ...obj2, age: 34}
    console.log(obj3) // Object { name: "Ezgi", lastName: "Coban", age: "34" }
```

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?  
    ****
2. In your own words, what does the `increment` function do?
3. How can you pass a method from a parent component into a child component?
4. How does the child component invoke a method that was passed to it from a parent component?

## Bookmark and Review

- [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)
