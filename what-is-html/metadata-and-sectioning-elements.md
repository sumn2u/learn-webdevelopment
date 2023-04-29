# Metadata and Sectioning Elements

Metadata elements in HTML provide information about a webpage that is not visible to the user, but is used by browsers, search engines, and other applications. Sectioning elements are used to organize the content of a webpage into sections and sub-sections.

Here are some common metadata and sectioning elements in HTML:

Metadata elements:

* `<title>`: The title of the webpage, which is displayed in the browser's title bar or tab.
* `<meta>`: Meta elements are used to provide metadata about the webpage, such as a description, keywords, the author, and more. Meta elements are placed in the head of the document.

Sectioning elements:

* `<header>`: The header of a webpage, which typically contains the logo, site navigation, and other elements that are common to all or most pages on the site.
* `<footer>`: The footer of a webpage, which typically contains information such as the copyright notice, contact information, and links to related pages.
* `<section>`: A section of content that is thematically related, such as a chapter in a book or a news article.
* `<article>`: A standalone piece of content, such as a blog post or news article.
* `<nav>`: A section of the webpage that contains navigation links.

Here is an example of how these elements could be used in an HTML document:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
    <meta name="description" content="This is my personal website where I post my thoughts and ideas.">
    <meta name="keywords" content="personal website, blog, thoughts, ideas">
  </head>
  <body>
    <header>
      <h1>My Website</h1>
      <nav>
        <ul>
          <li>
            <a href="/">Home</a>
          </li>
          <li>
            <a href="/about">About</a>
          </li>
          <li>
            <a href="/contact">Contact</a>
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <section>
        <h2>Latest Blog Posts</h2>
        <article>
          <h3>Why I love cats</h3>
          <p>I've always been a cat person. There's just something about the way they purr and cuddle that makes me feel warm and fuzzy inside.</p>
        </article>
        <article>
          <h3>My favorite hiking trails</h3>
          <p>I love to get out into nature and explore the great outdoors. Here are my favorite hiking trails in the area.</p>
        </article>
      </section>
    </main>
    <footer>
      <p>Copyright 2023</p>
      <p>Contact: <a href="mailto:info@mywebsite.com">info@mywebsite.com</a>
      </p>
    </footer>
  </body>
</html>
```
