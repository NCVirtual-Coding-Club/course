---
layout: default
title: Use the order Property to Rearrange Items
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 16
---
# Use the order Property to Rearrange Items
## Summary
- The `order` property is used to tell CSS the order of how flex items appear in the flex container.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    order: 2;
    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;
    order: 1;
    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}