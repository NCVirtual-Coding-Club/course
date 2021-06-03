---
layout: default
title: Override Class Declarations with Inline Styles
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 30
---
# Override Class Declarations with Inline Styles
## Summary
- Inline styles can be used to override CSS.

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
    color: pink;
  }
  .blue-text {
    color: blue;
  }
</style>
<h1 id="orange-text" class="pink-text blue-text" style="color: white;">Hello World!</h1>
{% endhighlight %}