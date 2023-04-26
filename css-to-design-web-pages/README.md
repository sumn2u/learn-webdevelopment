# CSS to Design Web Pages

CSS (Cascading Style Sheets) is a stylesheet language that is used to control the look and feel of a webpage. It is used to style the layout, colors, fonts, and other aspects of the webpage.

CSS works by applying styles to HTML elements. You can use CSS to apply styles to specific elements, or to groups of elements. You can also use CSS to create reusable styles that can be applied to multiple elements or pages.

CSS is applied to an HTML document in one of three ways:

1. Inline styles: Styles are applied directly to the HTML element using the `style` attribute. Inline styles take precedence over other styles and are the least preferred method of applying styles.
2. Internal styles: You can define styles within the `<style>` element in the head of the HTML document. This method is useful for applying styles to multiple elements on a single webpage, but is not recommended for larger websites because it can make the HTML code difficult to read and maintain.
3. External stylesheets: You can create a separate CSS file and link to it from the HTML document using the `<link>` element in the head of the HTML document. This method is recommended for larger websites because it allows you to separate the styling from the HTML code, which makes the code easier to read and maintain.

```javascript
// inline style
<p style="color:red; font-size:24px;">This is a paragraph</p>  

// Internal styles
<head>
  <style>
    p {
      color: red;
      font-size: 24px;
    }
  </style>
</head>

// External stylesheets
<head> <link rel="stylesheet" href="/css/styles.css"> </head> 
```

In the external stylesheet file (styles.css), you can define the styles using CSS rules. A CSS rule consists of a selector and a declaration block. The selector specifies which elements the rule applies to, and the declaration block contains the styles that are applied to the elements.

```css
p { color: red; font-size: 24px; } 
```

You can use various CSS properties, such as color, _`font-size`_, and _`margin`_, to control the styling of the elements. You can also use CSS selectors to specify which elements the styles should be applied to. For example, you can use class and ID selectors to apply styles to specific elements, or use pseudo-classes to apply styles to elements in a certain state (such as hover).

Using an external stylesheet allows you to keep the styling separate from the HTML code, which makes the code easier to read and maintain. It also allows you to make global changes to the styling of the website by simply updating the CSS file, instead of having to update the styling in each HTML file.
