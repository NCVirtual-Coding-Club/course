---
layout: default
title: Create a Graphic Using CSS
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 38
---
# Create a Graphic Using CSS
## Summary
- CSS can be used to create graphics.

## Final Code

{% highlight HTML %}
<style>
  .center {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100px;
    height: 100px;
    background-color: transparent;
    border-radius: 50%;
    box-shadow: 25px 10px 0px 0px blue;
  }

</style>
<div class="center"></div>
{% endhighlight %}