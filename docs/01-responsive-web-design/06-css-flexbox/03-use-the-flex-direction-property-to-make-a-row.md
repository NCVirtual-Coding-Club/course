---
layout: default
title: Use the flex-direction Property to Make a Row
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 3
---
# Use the flex-direction Property to Make a Row
## Summary
- The `flex-direction` property can be used to align the children of an element into rows or columns.
- Other options for `flex-direction` are `row-reverse` and `column-reverse`.

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: row-reverse;
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