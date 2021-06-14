---
layout: default
title: Comparison with the Greater Than Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 63
---
# Comparison with the Greater Than Operator
## Summary
- The greater than operator (`>`) compares the values of two numbers for the larger number.
- If the number to the left is greater than the number to the right, it returns `true`. Otherwise, it returns `false`.

## Final Code

{% highlight JavaScript %}
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }

  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

testGreaterThan(10);
{% endhighlight %}