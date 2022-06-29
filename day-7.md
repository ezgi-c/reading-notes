[Home](/README.md)

# Code 102 Day 6 Notes - Programming with Javascript

## Operators and Loops

### Assignment Operator

- assigns value of operand on on its right to the operand on its left

#### examples

Assignment:                `x = f()`      means       `x = f()`

Addition assignment:        `x += f()`       means      `x = x + f()`

Subtraction assignment:     `x -= f()`      means          `x = x - f()`

Multiplication assignment:  `x *= f()`      means       `x = x * f()`

Division assignment:        `x /= f()`       means      `x = x / f()`

### Comparison Operator

> A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.

#### examples

| Operator | Description | Examples returning true|
|:----------|:-------------:|------------------------|
|Equal (==) |Returns true if the operands are equal.| 3 == var1|
|            |               |                         "3" == var1|
|             |               |                             3 == '3'|
|Not equal (!=) | Returns true if the operands are not equal. |var1 != 4|
|                |                                               |     var2 != "3"|

### Loops

Purpose of a loop: running a code a number of times until  a condition is met

#### while loop:

while (some condition is true){
do something over and over and over again
}

```js
let x = 0;
While(x < 5){
 console.log(x);
// need to do something with x so that it eventually becomes >= 5.
// x = x + 1;
x++;
}

Console.log(‘i am done’);
```

`string !== string` (strict, only used for similar data types)
`string != int` (loose, use when crossing data types)

```js
guessNumberofCats();
Function guessNumberOfCats(){
 let answer = prompt(‘how many cats does Amanda have?’);
 while(answer != 2){
  if(answer <2){
   alert(’too low’);
  } else {
   alert(’too high’);
  }
  answer = prompt(‘how many cats does Amanda have?’);
}
Alert(‘Congrats you are correct!);
```

#### do...while Loop

- do…while loop gurantees us at least ONE iteration

- do…while is used more in front-end dev, while loops more on back-end

#### for loop

- core of alot of programming languages
- same across several different languages

3 main components:

1. variable declaration
2. condition that needs to be met
3. What do we do with the variable once iteration has completed

```js
Function forLoopExample(){
 for(let x = 0; x < 5; x++){
  console.log(x);
 }
 console.log(“i’m done”)

let student = [‘amanda’, ‘ezgi’, ‘manuch’];
 for(let x = 0; x < students.length; x++){
  console.log(students[x)];
 }
  ```
