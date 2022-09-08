Find the output of the code snippets below:

```js
console.log(numA + numB); //NaN
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT ReferenceError: Cannot access 'numA' before initialization
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //OUTPUT 51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT Hello
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion"; //Tyrion
sayHello(); // OUTPUT
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT ReferenceError: Cannot access 'username' before initialization
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT ReferenceError: Cannot access 'sayHello' before initialization
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
var username = "Tyrion"; //ReferenceError: Cannot access 'sayHello' before initialization
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT ReferenceError: Cannot access 'sayHello' before initialization
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // OUTPUT undefined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); //  John
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // OUTPUT ReferenceError: Cannot access 'username' before initialization
```