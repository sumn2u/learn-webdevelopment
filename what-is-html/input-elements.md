# Input Elements

The `<input>` element is used to create input fields in HTML forms. The `type` attribute of the `<input>` element specifies the type of input field, such as a text field, email field, or radio button.

Here is an example of how to create a text input field:

```javascript
<input type="text">
```

Here is an example of how to create an email input field:

```javascript
<input type="email">
```

Here is an example of how to create a radio button:

```javascript
<input type="radio" name="gender" value="male"> Male<br>
<input type="radio" name="gender" value="female"> Female<br>
```

The `name` attribute specifies a name for the field, which is used to identify the field when the form is submitted. The `value` attribute specifies the value of the field, which is sent to the server when the form is submitted.

In addition to the `type` attribute, the `<input>` element also supports various attributes that allow you to control the behavior and appearance of the input field, such as the `value` attribute, which specifies the default value of the field, and the `placeholder` attribute, which specifies a short hint that is displayed in the field when it is empty.

Here is an example of how to use the `value` and `placeholder` attributes:

```javascript
<input type="text" value="John Doe" placeholder="Enter your name">
```

The `<input>` element can be styled using CSS to match the design of the website. It can be placed inside a `<form>` element or used as a standalone element.

\
