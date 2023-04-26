# HTML Forms

HTML forms allow you to collect input from users through a webpage. Forms consist of form elements, such as text fields, buttons, and checkboxes, that allow users to enter and submit data.

To create a form in HTML, you can use the `<form>` element. The `action` attribute of the `<form>` element specifies the URL of the server-side script that will process the form data, and the `method` attribute specifies the HTTP method (such as `GET` or `POST`) that will be used to submit the form data.

Here is an example of a basic HTML form:

```javascript
<form action="/submit-form" method="post">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name"><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email"><br>
  <label for="message">Message:</label><br>
  <textarea id="message" name="message"></textarea><br>
  <input type="submit" value="Submit">
</form> 
```

Inside the `<form>` element, you can use various form elements to collect different types of input from users.

* `<input>` elements are used for single-line text input, password input, and various types of data such as numbers, dates, and emails.
* `<textarea>` elements are used for multi-line text input.
* `<select>` and `<option>` elements are used for dropdown menus.
* `<button>` elements are used for buttons.
* `<fieldset>` and `<legend>` elements are used to group related form elements and provide a label for the group.
* `<label>` elements are used to label form elements and provide a visible name for the element.

You can use various attributes, such as `name`, `value`, and `placeholder`, to customize the behavior and appearance of the form elements.

To submit the form data, you can use a submit button, which is created using the `<input type="submit">` element. You can also use the `<button>` element to create a custom submit button.
