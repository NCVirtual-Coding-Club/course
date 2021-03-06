---
layout: default
title: Adjust the Padding of an Element
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 16
---
# Adjust the Padding of an Element
## Summary
- Three important properties control the space that surrounds each HTML element: `padding`, `border`, and `margin`.
- An element's `padding` controls the amount of space between the element's content and its `border`.


## Final Code

{% highlight HTML %}
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }

  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }

  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }

  .red-box {
    background-color: crimson;
    color: #fff;
    padding: 20px;
  }

  .blue-box {
    background-color: blue;
    color: #fff;
    padding: 20px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box blue-box">padding</h5>
</div>
{% endhighlight %}