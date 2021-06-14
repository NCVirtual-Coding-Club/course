---
layout: default
title: Comparison with the Greater Than Or Equal To Operator
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 64
---
# Comparison with the Greater Than Or Equal To Operator
## Summary
- The greater than or equal to operator (`>=`) compares the values of two numbers for the larger number.

## Final Code

{% highlight JavaScript %}
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }

  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

testGreaterOrEqual(10);
{% endhighlight %}