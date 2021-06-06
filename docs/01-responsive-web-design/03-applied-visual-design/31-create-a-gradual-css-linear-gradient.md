---
layout: default
title: Create a Gradual CSS Linear Gradient
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 31
---
# Create a Gradual CSS Linear Gradient
## Summary
- CSS provides the ability to use color transitions, otherwise known as gradients, on elements.
- The first argument specifies the direction from which color transition starts in degrees.

## Final Code

{% highlight HTML %}
<style>
  div {
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin: 50px auto;
    background: linear-gradient(35deg, #CCFFFF, #FFCCCC)
  }

</style>

<div></div>
{% endhighlight %}