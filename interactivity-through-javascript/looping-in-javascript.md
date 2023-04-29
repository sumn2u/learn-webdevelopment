# Looping in JavaScript

In JavaScript, you can use loops to execute a block of code multiple times.

The `for` loop is used to execute a block of code a specified number of times.

Example:

```javascript
for (let i = 0; i < 10; i++) {
  console.log(i);
}
```

This will print the numbers from 0 to 9.

The `while` loop is used to execute a block of code as long as a condition is true.

Example:

```javascript
let i = 0;
while (i < 10) {
  console.log(i);
  i++;
}
```

This will also print the numbers from 0 to 9.

The `do...while` loop is similar to the `while` loop, but it guarantees that the block of code will be executed at least once.

Example:

```javascript
var i = 0;
do {
  console.log(i);
  i++;
} while (i < 10);
```

This will also print the numbers from 0 to 9.

In JavaScript, you can also use the `break` and `continue` statements to control the flow of the loop. The `break` statement is used to exit the loop, and the `continue` statement is used to skip the rest of the current iteration and move to the next one.

Example:

```javascript
for (let i = 0; i < 10; i++) {
  if (i % 2 == 0) continue;  // skip even numbers
  if (i > 5) break;         // exit loop when i is greater than 5
  console.log(i);            // prints 1, 3, 5
}
```
