# Variable and Methods

In JavaScript, a variable is a named storage location for a value. Variables are used to store and manipulate data in a program.

To declare a variable in JavaScript, you can use the `var` keyword followed by the name of the variable.

Example:

```javascript
let x;
```

You can also assign a value to a variable when you declare it.

Example:

```javascript
let x = 10;
```

In JavaScript, variables can be reassigned and their values can be changed.

Example:

```javascript
let x = 10;
x = 20;
```

JavaScript supports different types of data, including numbers, strings, booleans, and objects.

Example:

```javascript
let x = 10;       // number
let y = "hello";  // string
let z = true;     // boolean
let obj = {};     // object
```

JavaScript methods are functions that are associated with objects. They are used to perform actions or to compute and return a value.

To define a method in JavaScript, you can use the `function` keyword followed by the name of the method and its parameters.

Example:

```javascript
const add = (x, y) => {
  return x + y;
}
```

To call a method, you can use the name of the method followed by parentheses and the arguments.

Example:

```javascript
const result = add(10, 20);
```

Methods can be defined on objects and can be called using the `.` operator.

Example:

```javascript
let obj = {
  name: "John",
  sayHello: function() {
    console.log("Hello, my name is " + this.name);
  }
};

obj.sayHello();  // prints "Hello, my name is John"
```
