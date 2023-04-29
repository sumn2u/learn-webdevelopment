# Adding images and links

HTML provides elements for adding images and links to a webpage.

To add an image to an HTML document, you can use the `<img>` element. The src attribute of the `<img>` element specifies the URL of the image, and the alt attribute provides alternative text for the image.

Here is an example of how to add an image to an HTML document:

```javascript
<img src="/images/cat.jpg" alt="A cute cat">
```

To add a link to an HTML document, you can use the &lt;a> element. The `href` attribute of the `<a>` element specifies the URL of the link, and the content inside the `<a>` element represents the text of the link.

Here is an example of how to add a link to an HTML document:

```javascript
<a href="https://www.google.com">Click here to visit Google</a>
```

You can also add images and links inside other elements, such as headings, paragraphs, and list items.

Here is an example of an HTML document with images and links:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Welcome to my website!</h1>
    <p>This is my personal website, where I post my thoughts and ideas. <a href="/about">Learn more about me</a>. </p>
    <h2>My favorite animals</h2>
    <ul>
      <li>
        <img src="/images/cat.jpg" alt="A cute cat">Cats
      </li>
      <li>
        <img src="/images/dog.jpg" alt="A playful dog">Dogs
      </li>
      <li>
        <img src="/images/bird.jpg" alt="A colorful bird">Birds
      </li>
    </ul>
    <p>For more information about pets, visit the <a href="https://www.aspca.org">ASPCA website</a>. </p>
  </body>
</html>
```
