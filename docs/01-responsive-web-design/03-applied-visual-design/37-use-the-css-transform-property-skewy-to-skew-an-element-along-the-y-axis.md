---
layout: default
title: Use the CSS Transform Property skewY to Skew an Element Along the Y-Axis
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 37
---
# Use the CSS Transform Property skewY to Skew an Element Along the Y-Axis
## Summary
- The `skewY()` function of the `transform` property is used to skew an element along the y-axis by a given degree.

## Final Code

{% highlight HTML %}
<style>
  div {
    width: 70%;
    height: 100px;
    margin: 50px auto;
  }
  #top {
    background-color: red;
    transform: skewY(-10deg);
  }
  #bottom {
    background-color: blue;
    transform: skewX(24deg);
  }
</style>

<div id="top"></div>
<div id="bottom"></div>
{% endhighlight %}