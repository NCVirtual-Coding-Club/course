---
layout: default
title: Comparison with the Strict Equality Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 59
---
# Comparison with the Strict Equality Operator
## Summary
- The stritct equality operator compares two items based on their values, and data type.

## Final Code

{% highlight JavaScript %}
// Setup
function testStrict(val) {
  if (val === 7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);
{% endhighlight %}