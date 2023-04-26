# CSS Selectors

CSS selectors are patterns used to select the elements that you want to style in an HTML document. Selectors are used in CSS rules to specify which elements on the page should be affected by the rule.

There are several types of selectors, including:

* Element selectors: Select all elements of a particular type.

Example:

```css
p {
  /* Style all <p> elements */
}
```

* Class selectors: Select elements with a particular class attribute.

Example:

```css
.error {
  /* Style all elements with class="error" */
}
```

* ID selectors: Select a unique element with a particular id attribute.

Example:

```css
#footer {
  /* Style the element with id="footer" */
}
```

* Attribute selectors: Select elements with a particular attribute or attribute value.

Example:

```css
input[type="text"] {
  /* Style all <input> elements with type="text" */
}
```

* Descendant selectors: Select elements that are descendants of another element.

Example:

```css
body p {
  /* Style all <p> elements inside the <body> element */
}
```

* Child selectors: Select elements that are direct children of another element.

Example:

```css
ul > li {
  /* Style all <li> elements that are direct children of a <ul> element */
}
```

* Adjacent sibling selectors: Select elements that are directly adjacent to another element.

Example:

```css
h1 + p {
  /* Style all <p> elements that are directly after an <h1> element */
}
```

CSS selectors allow you to specify precise and flexible rules for styling elements in an HTML document. By using the right selectors, you can create powerful and efficient styles that are easy to maintain and update.
