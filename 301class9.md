[Home](/README.md)

# Class 09 - Functional Programming

## Functional Programming Concepts

1. What is functional programming?  
    >Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia

1. What is a pure function and how do we know if something is a pure function?  
    Requirements of a pure function is that it gives the same results when given the same arguments and there are no observable side effects such as modifying a global object. 
1. What are the benefits of a pure function?  
    Pure functions are stable, predictable and consistent. The code is easier to test. 
1. What is immutability?
    When data is immutable, its state can not change after it is created. 
1. What is Referential transparency?  
    A function is referentially transparent when it consistently outputs the same result for the same input.
    >pure functions + immutable data = referential transparency

## Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?  
    Modules are independent but inter-related pieces of code, that divide up our code into smaller chunks.
1. What does the word ‘require’ do?  
    It imports a module into another module.
1. How do we bring another module into the file the we are working in?
    We use require and pass in the file path of the module in a string. e.g.,

    ```js
    require('./someFile')
    ```

1. What do we have to do to make a module available?  
    We export from the module whatever variable or function we want to make available to other files. e.g.,

    ```js
    module.exports = someVariable
    ```  

    And the file importing the variable uses the following syntax:

    ```js
    var someVariable = require('./someFile')
    ```
