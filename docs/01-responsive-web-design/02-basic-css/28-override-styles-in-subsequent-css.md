---
layout: default
title: Override Styles in Subsequent CSS
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 28
---
# Override Styles in Subsequent CSS
## Summary
- Classes will override the `body` element's CSS.
- The second declaration will always take precedence over the first.

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
    color: blue
  }
</style>
<h1 class="pink-text blue-text">Hello World!</h1>
{% endhighlight %}