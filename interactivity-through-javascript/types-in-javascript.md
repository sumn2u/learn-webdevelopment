# Types in JavaScript

In JavaScript, there are several types of data that you can use in your programs.

* Number: A numeric value. JavaScript has only one type of number, which can be an integer or a floating-point value.

Example:

```javascript
const x = 10;
const y = 3.14;
```

* String: A sequence of characters. Strings can be enclosed in single or double quotes.

Example:

```javascript
const str = "hello";
const str2 = 'world';
```

* Boolean: A value that represents true or false.

Example:

```javascript
const flag = true;
const flag2 = false;
```

* Null: A value that represents the absence of a value.

Example:

```javascript
const x = null;
```

* Undefined: A value that represents the absence of a value that has not been assigned.

Example:

```javascript
const x;
console.log(x);  // prints undefined
```

* Object: A collection of key-value pairs.

Example:

```javascript
const obj = {
  name: "John",
  age: 30
};
```

In JavaScript, the type of a value is determined at runtime, and the same value can have different types at different points in the program.

JavaScript has a built-in function called `typeof` that returns a string that represents the type of a value.

Example:

```javascript
console.log(typeof 10);     // prints "number"
console.log(typeof "hello"); // prints "string"
console.log(typeof true);    // prints "boolean"
console.log(typeof {});      // prints "object"
```
