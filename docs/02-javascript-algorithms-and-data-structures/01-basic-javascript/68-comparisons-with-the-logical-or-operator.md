---
layout: default
title: Comparisons with the Logical Or Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 68
---
# Comparisons with the Logical Or Operator
## Summary
- The logical or operator (`||`) returns `true` if either of the operands is `true`. Otherwise, it returns `false`.

## Final Code

{% highlight JavaScript %}
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20) {
    return "Outside";
  }

  // Only change code above this line
  return "Inside";
}

testLogicalOr(15);
{% endhighlight %}