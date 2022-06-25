[Home](README)

# Code 102 Day 5 Notes - JavaScript

## JavaScript Variables

>Variables are containers for storing data.

- Variables in JS are declared with following words:
  `var`,
  `let`,
  `const`
- `var` and `let` are variables that are changeable while `const` is not
- The variables have no value until we assign them value using `=`
- Example:

  ```
  let x= 10
  let y= 20
  let z= x+y
  ```

- First step: create new file, most commonly used name: "app.js"
- link to the script in the HTML file in the section we want it to load
- start document with  `'use strict'` ;tells us to follow some baseline 'strict rules'
- `//` is used to comment out code. "ctrl + k + c" to comment out multiple lines
Example script:

```
let firstName = prompt('What is your name?')

let time = prompt('What hour is it (0-24)')
let message = '';
// if time of day is before noon then we want to say "Good Morning"

if(time <= 11){
    message = 'Good Morning!! ';
} else if(time <= 18){
    message = 'Good Afternoon!! ';
} else if(time <= 24){
    message = 'Good Night!! ';
} else{
    message = 'Good Day!! ';
}

document.write('Hello ' + firstName +'! ' + message);
```

- Script is ran from top to bottom; after running the first part of the script, it skips over the `else if` and `else`

## How Computers Work

- All computers do 4 things
  - Input
  - Storage
  - Processing
  - Output
- All input is translated into ***binary***: 1's and 0's
  - Everything from numbers to letters to sounds to images is able to be tranlated to binary through combinations of 1's and 0's.
  - 1's and 0's are physically correlated to wires which either have current (1) or they don't (0)
- CPU = Central Processing Unit
  - controls all circuits of the computer
  - softwares tell CPU what to do
- The Operating System (OS) controls softwares which control the hardwares
