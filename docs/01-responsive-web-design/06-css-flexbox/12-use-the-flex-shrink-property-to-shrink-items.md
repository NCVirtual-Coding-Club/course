---
layout: default
title: Use the flex-shrink Property to Shrink Items
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 12
---
# Use the flex-shrink Property to Shrink Items
## Summary
- The `flex-shrink` property is used ot shrink a flex item if a flex container is smaller than the combined widths of all the flex items.
- The `flex-shrink` property takes numbers.
    - If one item has a `flex-shrink` value of `1` and the other has a `flex-shrink` value of `3`, the one with the value of `3` will shrink three times as much as the other.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 100%;
    height: 200px;
    flex-shrink: 1;
  }

  #box-2 {
    background-color: orangered;
    width: 100%;
    height: 200px;
    flex-shrink: 2;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}