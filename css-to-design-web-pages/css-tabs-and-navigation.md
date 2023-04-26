# CSS Tabs and Navigation

CSS tabs and navigation allow you to create tabbed interfaces and navigation menus on a webpage.

To create tabs using CSS, you can use the `display`, `position`, and `:target` pseudo-class properties.

Here is an example of how to create tabs using CSS:

HTML:

```html
<div class="tabs">
  <a href="#tab1" class="tab">Tab 1</a>
  <a href="#tab2" class="tab">Tab 2</a>
  <a href="#tab3" class="tab">Tab 3</a>
  <div id="tab1" class="tab-content">
    Tab 1 content
  </div>
  <div id="tab2" class="tab-content">
    Tab 2 content
  </div>
  <div id="tab3" class="tab-content">
    Tab 3 content
  </div>
</div>
```

CSS:

```css
.tabs {
  display: flex;
}

.tab {
  display: inline-block;
  padding: 10px;
  border: 1px solid #ccc;
  cursor: pointer;
}

.tab-content {
  display: none;
  border: 1px solid #ccc;
  padding: 10px;
}

.tab:target {
  background: #eee;
}

#tab1:target,
#tab2:target,
#tab3:target {
  display: block;
}
```

To create a navigation menu using CSS, you can use the `display`, `position`, and `:hover` pseudo-class properties.

Here is an example of how to create a navigation menu using CSS:

HTML:

```html
<ul class="nav">
  <li><a href="#">Home</a></li>
  <li><a href="#">About</a></li>
  <li><a href="#">Contact</a></li>
</ul>
```

CSS:

```css
.nav {
  display: flex;
}

.nav li {
  list-style: none;
  margin-right: 10px;
}

.nav a {
  text-decoration: none;
  color: #000;
  padding: 10px;
  display: block;
}

.nav a:hover {
  background: #eee;
}
```

This will create a horizontal navigation menu with links that change color when hovered over.\
