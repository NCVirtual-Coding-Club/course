---
layout: default
title: Comparison with the Equality Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 58
---
# Comparison with the Equality Operator
## Summary
- The most basic operator is the equality operator `==` used to compare two items for equality.

## Final Code

{% highlight JavaScript %}
// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testEqual(10);
{% endhighlight %}