---
layout: default
title: Use the CSS Transform Property skewX to Skew an Element Along the X-Axis
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 36
---
# Use the CSS Transform Property skewX to Skew an Element Along the X-Axis
## Summary
- The `skewX()` function of the `transform` property is used to skew an element along the x-axis by a given degree.

## Final Code

{% highlight HTML %}
<style>
  div {
    width: 70%;
    height: 100px;
    margin:  50px auto;
  }
  #top {
    background-color: red;
  }
  #bottom {
    background-color: blue;
    transform: skewX(24deg);
  }
</style>

<div id="top"></div>
<div id="bottom"></div>
{% endhighlight %}