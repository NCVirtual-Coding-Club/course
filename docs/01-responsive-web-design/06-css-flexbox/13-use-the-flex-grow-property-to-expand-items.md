---
layout: default
title: Use the flex-grow Property to Expand Items
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 13
---
# Use the flex-grow Property to Expand Items
## Summary
- The `flex-grow` property controls the size of items when the parent container expands.
    - If one item has a `flex-grow` value of `1` and the other has a `flex-grow` value of `3`, the one with the value of `3` will grow three times as much as the other.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    display: flex;
    height: 500px;
  }

  #box-1 {
    background-color: dodgerblue;
    height: 200px;
    flex-grow: 1;
  }

  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-grow: 2;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}