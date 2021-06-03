---
layout: default
title: Understand Absolute versus Relative Units
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 24
---
# Understand Absolute versus Relative Units
## Summary
- Absolute units tie to physical units of length.
- Relative units, such as `em` or `rem`, are relative to another length value.

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
    padding: 20px 40px 20px 40px;
  }

  .red-box {
    background-color: red;
    margin: 20px 40px 20px 40px;
    padding: 1.5em
  }

  .green-box {
    background-color: green;
    margin: 20px 40px 20px 40px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
{% endhighlight %}