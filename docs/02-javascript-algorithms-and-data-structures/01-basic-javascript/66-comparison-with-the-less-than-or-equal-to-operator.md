---
layout: default
title: Comparison with the Less Than Or Equal To Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 66
---
# Comparison with the Less Than Or Equal To Operator
## Summary
- The less than or equal to operator (`<=`) compares the values of two numbers.

## Final Code

{% highlight JavaScript %}
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }

  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

testLessOrEqual(10);
{% endhighlight %}