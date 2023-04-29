# CSS Mixins

CSS mixins are reusable blocks of CSS code that can be included in other stylesheets. They are useful for creating modular and maintainable styles, and for reducing repetition and duplication in your code.

To create a mixin, you can use the `@mixin` rule and define the styles that you want to include in the mixin.

Example:

```css
@mixin border-radius {
  border-radius: 5px;
}
```

To include the mixin in your styles, you can use the `@include` directive.

Example:

```css
.button {
  @include border-radius;
  border: 1px solid #ccc;
  padding: 10px;
  color: #000;
}
```

You can also pass arguments to mixins, which allows you to customize the styles that are included in the mixin.

Example:

```css
@mixin border-radius($radius) {
  border-radius: $radius;
}

.button {
  @include border-radius(10px);
  border: 1px solid #ccc;
  padding: 10px;
  color: #000;
}
```

CSS mixins are a powerful tool for organizing and maintaining your styles. They allow you to create reusable and customizable styles that can be easily updated and maintained, and that can be shared between different stylesheets.
