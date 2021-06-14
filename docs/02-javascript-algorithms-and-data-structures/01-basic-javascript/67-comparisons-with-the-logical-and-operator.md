---
layout: default
title: Comparisons with the Logical And Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 67
---
# Comparisons with the Logical And Operator
## Summary
- `&&` allows multiple conditional statements to be set.

## Final Code

{% highlight JavaScript %}
function testLogicalAnd(val) {
  // Only change code below this line

  if (val <= 50 && val >= 25) {
      return "Yes";
  }

  // Only change code above this line
  return "No";
}

testLogicalAnd(10);
{% endhighlight %}