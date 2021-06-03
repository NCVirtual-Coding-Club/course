---
layout: default
title: Prioritize One Style Over Another
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 27
---
# Prioritize One Style Over Another

## Final Code

{% highlight HTML %}
<style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }
  .pink-text {
    color: pink
  }
</style>
<h1 class="pink-text">Hello World!</h1>
{% endhighlight %}