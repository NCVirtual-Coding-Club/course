---
layout: default
title: Use the flex-direction Property to Make a Column
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 5
---
# Use the flex-direction Property to Make a Column
## Summary
- The `flex-direction` can be used to stack an element vertically.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: column;
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