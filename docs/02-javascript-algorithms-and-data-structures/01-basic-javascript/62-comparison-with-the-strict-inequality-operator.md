---
layout: default
title: Comparison with the Strict Inequality Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 62
---
# Comparison with the Strict Inequality Operator
## Summary
- The stritct inequality operator compares two items based on their values, and data type.

## Final Code

{% highlight JavaScript %}
// Setup
function testStrictNotEqual(val) {
  if (val !== 17) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testStrictNotEqual(10);
{% endhighlight %}