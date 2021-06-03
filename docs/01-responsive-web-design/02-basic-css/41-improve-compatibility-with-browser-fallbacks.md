---
layout: default
title: Improve Compatibility with Browser Fallbacks
parent: Basic CSS
grand_parent: Responsive Web Design
has_children: false
nav_order: 41
---
# @@@
## Summary
- Browsers may have compatibility issues when running CSS.
- It is important to use fallbacks.

## Final Code

{% highlight HTML %}
<style>
  :root {
    --red-color: red;
  }
  .red-box {
    background: red;
    background: var(--red-color);
    height: 200px;
    width:200px;
  }
</style>
<div class="red-box"></div>
{% endhighlight %}