---
layout: default
title: "Use display: flex to Position Two Boxes"
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 1
---
# Use display: flex to Position Two Boxes
## Summary
- Using the display: flex; CSS property allows the use of other flex properties to build a responsive page.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    height: 500px;
    display: flex;
  }

  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }
</style>
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}