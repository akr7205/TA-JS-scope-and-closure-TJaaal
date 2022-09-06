1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
const percentage=(marks,total) =>{
  return (marks * 100) / total;

}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
 Function Declaration
```

```js
let percentage = function percentage(param1,param2) {
  return (param1* 100) / param2;
};
Function expression
```
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
Function expression

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
Function expression

```js
let percentage = (marks, total) => (marks * 100) / total;
Function expression

```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
function percentage(marks, total) {
  return (marks * 100) / total;
}
A function expression is very similar to and has almost the same syntax as a function declaration (see function statement for details). The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions.

const percentage=(marks,total) =>{
  return (marks * 100) / total;

}


4. Why is a function call an expression in JavaScript?
A function call expression is used to execute a specified function with the provided arguments.

If the function being called is overloaded, the compiler will attempt to match the argument types with the function parameter types


5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer 5
five = add; // Answer

// ƒ add(a, b) {
//   return a + b;
// }
 

five = five(10, 11); // Answer 21

five = function () {
  return 'Hello';
};

ƒ () {
  return 'Hello';
}

```

6. What is the difference between function definition and function call? Explain with an example.
Defining a function is the creation of a function

function multiple(x,y){

return x*y;

}

Calling a function would look like

print multiply(2,3);

7. What is the similarities between function definition and function call?
nedd function name and parameter

8. Is the code below valid or invalid. Explain with reason.

```js

function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid  valid
```

9. What is higher order function explain with an example.
Higher-order functions in JavaScript are a special category of functions that either accept functions as an argument or return functions.

function calculate(operation, initialValue, numbers) {
  let total = initialValue;
  for (const number of numbers) {
    total = operation(total, number);
  }
  return total;
}
function sum(n1, n2) {
  return n1 + n2;
}
function multiply(n1, n2) {
  return n1 * n2;
}
calculate(sum, 0, [1, 2, 4]);      // => 7
calculate(multiply, 1, [1, 2, 4]); // => 8

10. Explain what is callback function. Why you can pass a function inside a function?
The callback is a function that's accepted as an argument and executed by another function (the higher-order function).

in above example sum() is a callback function.