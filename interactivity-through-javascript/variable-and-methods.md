# Variable and Methods

In JavaScript, a variable is a named storage location for a value. Variables are used to store and manipulate data in a program.

To declare a variable in JavaScript, you can use the `var` keyword followed by the name of the variable.

Example:

```javascript
var x;
```

You can also assign a value to a variable when you declare it.

Example:

```javascript
var x = 10;
```

In JavaScript, variables can be reassigned and their values can be changed.

Example:

```javascript
var x = 10;
x = 20;
```

JavaScript supports different types of data, including numbers, strings, booleans, and objects.

Example:

```javascript
var x = 10;       // number
var y = "hello";  // string
var z = true;     // boolean
var obj = {};     // object
```

JavaScript methods are functions that are associated with objects. They are used to perform actions or to compute and return a value.

To define a method in JavaScript, you can use the `function` keyword followed by the name of the method and its parameters.

Example:

```javascript
function add(x, y) {
  return x + y;
}
```

To call a method, you can use the name of the method followed by parentheses and the arguments.

Example:

```javascript
var result = add(10, 20);
```

Methods can be defined on objects and can be called using the `.` operator.

Example:

```javascript
var obj = {
  name: "John",
  sayHello: function() {
    console.log("Hello, my name is " + this.name);
  }
};

obj.sayHello();  // prints "Hello, my name is John"
```
