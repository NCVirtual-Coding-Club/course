---
layout: default
title: Override Class Declarations with Inline Styles
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 29
---
# Override Class Declarations with Inline Styles
## Summary
- ID attributes can be used to override CSS.

## Final Code

{% highlight HTML %}
<style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
  #orange-text {
    color: orange;
  }
</style>
<h1 class="pink-text blue-text" id="orange-text">Hello World!</h1>
{% endhighlight %}