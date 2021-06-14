---
layout: default
title: Use Multiple Conditional (Ternary) Operators
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 109
---
# Use Multiple Conditional (Ternary) Operators
## Summary
- Multiple conditional operators can be used together.

## Final Code

{% highlight JavaScript %}
function checkSign(num) {
  return (num > 0) ? "positive" : (num < 0) ? "negative" : "zero";
}

checkSign(10);
{% endhighlight %}