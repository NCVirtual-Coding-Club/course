---
layout: default
title: Comparison with the Inequality Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 61
---
# Comparison with the Inequality Operator
## Summary
- The inequality operator (`!=`) is the opposite of the equality operator (`==`).
- The inequality operator returns `true` if the values are not equal.

## Final Code

{% highlight JavaScript %}
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testNotEqual(10);
{% endhighlight %}