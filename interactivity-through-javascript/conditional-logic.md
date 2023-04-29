# Conditional Logic

In JavaScript, you can use conditional statements to execute different code based on different conditions.

The `if` statement is used to execute a block of code if a condition is true.

Example:

```javascript
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
}
```

The `if` statement can be extended with an `else` clause to execute a different block of code if the condition is false.

Example:

```javascript
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
} else {
  console.log("x is not greater than 5");
}
```

The `if` statement can also be extended with one or more `else if` clauses to test multiple conditions.

Example:

```javascript
let x = 10;
if (x > 20) {
  console.log("x is greater than 20");
} else if (x > 10) {
  console.log("x is greater than 10");
} else {
  console.log("x is not greater than 10 or 20");
}
```

In JavaScript, you can also use the `switch` statement to execute different code based on the value of a variable.

Example:

```javascript
let x = "hello";
switch (x) {
  case "hello":
    console.log("x is hello");
    break;
  case "world":
    console.log("x is world");
    break;
  default:
    console.log("x is neither hello nor world");
}
```

Conditional logic is an important part of programming, and it allows you to control the flow of your program and to execute different code based on different conditions.
