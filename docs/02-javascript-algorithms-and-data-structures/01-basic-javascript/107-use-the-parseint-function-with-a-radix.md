---
layout: default
title: Use the parseInt Function with a Radix
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 107
---
# Use the parseInt Function with a Radix
## Summary
- `parseInt()` accepts a second argument that allows the base of the number (2-36) to be specified.

## Final Code

{% highlight JavaScript %}
function convertToInteger(str) {
  return parseInt(str, 2);
}

convertToInteger("10011");
{% endhighlight %}