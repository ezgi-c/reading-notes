[Home](/README.md)

# Code 102 Day 6 Notes - Programming with Javascript

## Control Flow

In Javascript, code is executed from top to bottom and left to right. The order of execution is also affected by program structures such as _conditionals_ and _loops_ that can change the order.

i.e.:

``` js
if (field==empty) {
    promptUser();
} else {
    submitForm();
}
```

## Functions

> A JavaScript function is a block of code designed to perform a particular task.
>
> A JavaScript function is executed when "something" invokes it (calls it).
>
> Example:

``` js
    function myFunction(p1, p2) {
        return p1 * p2;   // The function returns the product of p1 and p2
    }
```

## Lecture Notes

### FUNctions

- comparmentalize and encapsulate code so it can be repeated thorughout the code
- increases usability and efficiency
- make code more readable

``` js
let firstName  = prompt(‘what is your name?’);

// call the function getGreeting with the ARGUMENT of firstName
getGreeting(firstName);

getSum(5, 25);
or
Let sum = getSum(5,25);
 console.log(‘you returned the value of sum ‘ + sum);

// parenthesis will be our ‘parameters'
function getGreeting(name){
 console.log(‘Hello, ‘ + name)
 console.log(’this was run from the function’);
}

function getSum(numA, numB){
 console.log(numA + numB);
}
 or
 return numA + numB;

Function getFirstname(){
 let firstName  = prompt(‘what is your name?’);
 return firstName;
}
```

- Function will not run unless called

``` js
<h2><script>getGreeting()</script></h2>
 ```
