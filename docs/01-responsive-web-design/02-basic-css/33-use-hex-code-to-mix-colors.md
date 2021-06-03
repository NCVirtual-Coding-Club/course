---
layout: default
title: Use Hex Code to Mix Colors
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 33
---
# Use Hex Code to Mix Colors
## Summary
- The digit `0` is the lowest number in hex code, and represents a complete absence of color.
- The digit `F` is the highest number in hex code, and represents the maximum possible brightness.

## Final Code

{% highlight HTML %}
<style>
  .red-text {
    color: #FF0000;
  }
  .green-text {
    color: #00FF00;
  }
  .dodger-blue-text {
    color: #1E90FF;
  }
  .orange-text {
    color: #FFA500;
  }
</style>

<h1 class="red-text">I am red!</h1>

<h1 class="green-text">I am green!</h1>

<h1 class="dodger-blue-text">I am dodger blue!</h1>

<h1 class="orange-text">I am orange!</h1>
{% endhighlight %}