---
layout: default
title: Use the flex-basis Property to Set the Initial Size of an Item
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 14
---
# Use the flex-basis Property to Set the Initial Size of an Item
## Summary
- The `flex-basis` property specifies the initial size of the item before CSS makes adjustments with `flex-shrink` or `flex-grow`.

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
    flex-basis: 10em;
  }

  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-basis: 20em;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}