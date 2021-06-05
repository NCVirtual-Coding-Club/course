---
layout: default
title: Lock an Element to the Browser Window with Fixed Positioning
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 22
---
# Lock an Element to the Browser Window with Fixed Positioning
## Summary
- The `fixed` `position` property locks an element relative to the browser window.
- Removes the element from the normal flow of the document.
- Elements with a fixed position won't move when the user scrolls.

## Final Code

{% highlight HTML %}
<style>
  body {
    min-height: 150vh;
  }
  #navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #767676;
  }
  nav ul {
    margin: 0px;
    padding: 5px 0px 5px 30px;
  }
  nav li {
    display: inline;
    margin-right: 20px;
  }
  a {
    text-decoration: none;
  }
</style>
<body>
  <header>
    <h1>Welcome!</h1>
    <nav id="navbar">
      <ul>
        <li><a href="">Home</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </nav>
  </header>
  <p>I shift up when the #navbar is fixed to the browser window.</p>
</body>
{% endhighlight %}