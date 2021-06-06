---
layout: default
title: Adjust the Tone of a Color
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 30
---
# Adjust the Tone of a Color
## Summary
- The saturation percent changes the amount of gray and the lightness percent determines how much white or black is in the color. 
- This is useful when you have a base hue you like, but need different variations of it.

## Final Code

{% highlight HTML %}
<style>
  header {
    background-color: hsl(180, 90%, 35%);
    color: #FFFFFF;
  }

  nav {
    background-color: hsl(180, 80%, 25%);
  }

  h1 {
    text-indent: 10px;
    padding-top: 10px;
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
    color: inherit;
  }
</style>

<header>
  <h1>Cooking with FCC!</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Classes</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>
{% endhighlight %}