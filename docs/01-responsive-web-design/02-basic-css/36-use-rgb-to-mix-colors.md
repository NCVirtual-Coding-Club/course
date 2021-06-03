---
layout: default
title: Use RGB to Mix Colors
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 36
---
# Use RGB to Mix Colors
## Summary
- Similarly to a hex code, colors can be mixed in RGB by using combinations of different values.

## Final Code

{% highlight HTML %}
<style>
  .red-text {
    color: rgb(255, 0, 0);
  }
  .orchid-text {
    color: rgb(218, 112, 214);
  }
  .sienna-text {
    color: rgb(160, 82, 45);
  }
  .blue-text {
    color: rgb(0, 0, 255);
  }
</style>

<h1 class="red-text">I am red!</h1>

<h1 class="orchid-text">I am orchid!</h1>

<h1 class="sienna-text">I am sienna!</h1>

<h1 class="blue-text">I am blue!</h1>
{% endhighlight %}