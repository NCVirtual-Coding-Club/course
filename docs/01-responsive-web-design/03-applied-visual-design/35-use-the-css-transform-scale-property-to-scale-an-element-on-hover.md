---
layout: default
title: Use the CSS Transform scale Property to Scale an Element on Hover
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 35
---
# Use the CSS Transform scale Property to Scale an Element on Hover
## Summary
- The `transform` property has a variety of functions that let you scale, move, rotate, skew, etc., elements.
- This can be used along with `:hover`.

## Final Code

{% highlight HTML %}
<style>
  div {
    width: 70%;
    height: 100px;
    margin:  50px auto;
    background: linear-gradient(
      53deg,
      #ccfffc,
      #ffcccf
    );
  }
    div:hover {
      transform: scale(1.1);
    }


</style>

<div></div>
{% endhighlight %}