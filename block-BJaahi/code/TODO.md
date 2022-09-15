For the given code below:

- re-write the code in ways that system will understand

For Example:

1.

```js
var username = 'Arya';
let brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Declaration Phase
var username = undefined;
let brothers;

function sayHello(name) {
  return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

// Execution Phase

username = 'Arya';
brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello('Test');
```

2.

```js
console.log(username, numbers);

var username = 'Arya';
let number = 21;

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```
<!-- Answer -->
// Declaration Phase
var username;
let number;
function sayHello(name) {
  return `Hello ${name}`;
}
let message;
let nextMessage;
// Execution Phase

username='Arya';
number=21;
message = sayHello(username);
nextMessage = sayHello('Test');

```js
// Your code goes here
```

3.

```js
console.log(username, numbers);
let username = 'Arya';
let number = 21;

let sayHello = function (name) {
  return `Hello ${name}`;
};

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here
```

4.

```js
let username = 'Arya';
console.log(username, numbers);

let number = 21;
let message = sayHello(username);

let sayHello = function (name) {
  return `Hello ${name}`;
};

var nextMessage = sayHello('Test');
```

<!-- Answer -->
//Declaration Phase
let username;
let number;
let message;
let sayHello;
var nextMessage=undefined;
//Execution Phase
username = 'Arya'
number = 21;
message = sayHello(username)
let sayHello = function (name) {
  return `Hello ${name}`;
};
nextMessage = sayHello('Test')

```js
// Your code goes here
```

5.

```js
console.log(name);
console.log(age);
var name = 'Lydia';
let age = 21;
```

<!-- Answer -->
//Declaration Phase
var name
let age
//Execution Phase
console.log(name);
console.log(age);
```js
// Your code goes here
```

6.

```js
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

sayHi();
```
//Declaration Phase
sayHi=function
//Execution Phase
console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
<!-- Answer -->

```js
// Your code goes here
```

7.

```js
sayHi();
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}
```

<!-- Answer -->

```js
// Your code goes here
```

8.

```js
sayHi();
let sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
};
```

<!-- Answer -->
ReferenceError: Cannot access 'sayHi' before initialization
```js
// Your code goes here
```

9.

```js
let num1 = 21;
console.log(sum);
var sum = num1 + num2;
let num2 = 30;
```
//declaration phase
let num1;
var sum=undefined;
let num2;
//Execution Phase
num1=21;
console.log(sum);
sum = num1 + num2
num2 = 30
<!-- Answer -->

```js
// Your code goes here
```

10.

```js
var num1 = 21;

let sum2 = addAgain(num1, num2, 4, 5, 6);

let add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
function addAgian(a, b) {
  return a + b;
}
let num2 = 200;

let sum = add(num1, num2, 4, 5, 6);
```

<!-- Answer -->
//declaration Phase
var num1;
let sum2
let add;
addAgain()
let num2;
let sum;
//Execution Phase
num1=21;
sum2 = addAgain(num1, num2, 4, 5, 6)
add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
sum = add(num1, num2, 4, 5, 6);

```js
// Your code goes here
```

11.

```js
function test(a) {
  let num1 = 21;
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
  return a + b;
};
```
//declaration phase
test()
let sum
let add
//Execution Phase
sum = test(100)
  let num1 = 21;
  return add(a, num1);

<!-- Answer -->

```js
// Your code goes here
```

12.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

function add(a, b) {
  return a + b;
}
```

<!-- Answer -->
//declaration Phase
test()
add()
//Execution Phase
sum=test(100)
let num1 = 21;
  return add(a, num1);
```js
// Your code goes here
```
