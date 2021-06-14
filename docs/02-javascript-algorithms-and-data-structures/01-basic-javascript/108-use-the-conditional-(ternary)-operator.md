---
layout: default
title: Use the Conditional (Ternary) Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 108
---
# Use the Conditional (Ternary) Operator
## Summary
- The conditional operator (ternary operator) can be used as a one line if-else expression.

## Final Code

{% highlight JavaScript %}
function checkEqual(a, b) {
  return a === b ? "Equal" : "Not Equal";
}

checkEqual(1, 2);
{% endhighlight %}