---
layout: default
title: Add Different Margins to Each Side of an Element
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 20
---
# Add Different Margins to Each Side of an Element
## Summary
- CSS allows the control of the margin of all four individual sides of an element with the `margin-top`, `margin-right`, `margin-bottom`, and `margin-left` properties.

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
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
    margin-left: 40px;
  }

  .blue-box {
    background-color: blue;
    color: #fff;
    margin-top: 40px;
    margin-left: 40px;
    margin-bottom: 20px;
    margin-right: 20px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box blue-box">padding</h5>
</div>
{% endhighlight %}