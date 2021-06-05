---
layout: default
title: Create a More Complex Shape Using CSS and HTML
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 39
---
# Create a More Complex Shape Using CSS and HTML
## Summary
- The `::before` and `::after` pseudo-elements are used to add something before or after a selected element.
- The `::before` and `::after` pseudo-elements need a `content` property.
    - Typically used to add photos or text to an element.

## Final Code

{% highlight HTML %}
<style>
  .heart {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background-color: pink;
    height: 50px;
    width: 50px;
    transform: rotate(-45deg);
  }
  .heart::after {
    background-color: pink;
    content: "";
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: 0px;
    left: 25px;
  }
  .heart::before {
    content: "";
    background-color: pink;
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: -25px;
    left: 0px;
  }
</style>
<div class="heart"></div>
{% endhighlight %}