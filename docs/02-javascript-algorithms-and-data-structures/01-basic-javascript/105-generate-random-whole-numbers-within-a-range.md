---
layout: default
title: Generate Random Whole Numbers within a Range
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 105
---
# Generate Random Whole Numbers within a Range
## Summary
- Use `min` and `max` numbers to generate a value between a certain range.

## Final Code

{% highlight JavaScript %}
function randomRange(myMin, myMax) {
  // Only change code below this line
  return Math.floor(Math.random() * (myMax - myMin + 1)) + myMin;
  // Only change code above this line
}
{% endhighlight %}