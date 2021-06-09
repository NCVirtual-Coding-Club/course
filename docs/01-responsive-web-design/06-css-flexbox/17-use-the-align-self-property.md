---
layout: default
title: Use the align-self Property
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 17
---
# Use the align-self Property
## Summary
- `align-self` is used to adjust an item's alignment indivdually, instead of all at once.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    align-self: center;
    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;
    align-self: flex-end;
    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}