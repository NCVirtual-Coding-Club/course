---
layout: default
title: Use a CSS Linear Gradient to Create a Striped Element
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 32
---
# Use a CSS Linear Gradient to Create a Striped Element
## Summary
- The `repeating-linear-gradient()` allows a gradient to be repeated.

## Final Code

{% highlight HTML %}
<style>

  div{
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin:  50 auto;
    background: repeating-linear-gradient(
      45deg,
      yellow 0px,
      yellow 40px,
      black 40px,
      black 80px
    );
  }

</style>

<div></div>
{% endhighlight %}