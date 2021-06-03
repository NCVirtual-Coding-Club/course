---
layout: default
title: Override All Other Styles by using Important
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 31
---
# Override All Other Styles by using Important
## Summary
- `!important` can be used to override all CSS.

## Final Code

{% highlight HTML %}
<style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }
  #orange-text {
    color: orange;
  }
  .pink-text {
    color: pink !important;
  }
  .blue-text {
    color: blue;
  }
</style>
<h1 id="orange-text" class="pink-text blue-text" style="color: white">Hello World!</h1>
{% endhighlight %}