# Animation  using JavaScript

In JavaScript, you can use the `setInterval` function to create animation by repeatedly executing a block of code at a given interval.

The `setInterval` function takes a callback function and a delay in milliseconds as arguments, and it returns an interval ID that you can use to stop the interval.

Example:

```javascript
var i = 0;
var intervalID = setInterval(function() {
  console.log(i);  // prints 0, 1, 2, 3, 4, 5, ...
  i++;
  if (i > 5) {
    clearInterval(intervalID);
  }
}, 1000);  // 1000 milliseconds = 1 second
```

You can also use the `setTimeout` function to execute a block of code after a given delay. The `setTimeout` function is similar to `setInterval`, but it executes the callback function only once.

Example:

```javascript
setTimeout(function() {
  console.log("Hello");  // prints "Hello" after 1 second
}, 1000);
```

In addition to using `setInterval` and `setTimeout`, you can use the `requestAnimationFrame` function to create animation in JavaScript.

The `requestAnimationFrame` function tells the browser to execute a callback function before the next repaint, and it allows you to create smooth and efficient animations.

Example:

```javascript
var start = null;
var element = document.getElementById("myElement");
function animate(timestamp) {
  if (!start) start = timestamp;
  var progress = timestamp - start;
  element.style.left = Math.min(progress / 10, 200) + "px";
  if (progress < 2000) {
    requestAnimationFrame(animate);
  }
}
requestAnimationFrame(animate);
```

Using `setInterval`, `setTimeout`, and `requestAnimationFrame`, you can create various types of animations in JavaScript, such as moving elements, fading in and out, and changing the color of elements.
