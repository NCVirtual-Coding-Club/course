---
layout: default
title: Comparison with the Less Than Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 65
---
# Comparison with the Less Than Operator
## Summary
- The less than operator (`<`) compares the values of two numbers.
- If the number to the left is less than the number to the right, it returns `true`. Otherwise, it returns `false`.

## Final Code

{% highlight JavaScript %}
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }

  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

testLessThan(10);
{% endhighlight %}