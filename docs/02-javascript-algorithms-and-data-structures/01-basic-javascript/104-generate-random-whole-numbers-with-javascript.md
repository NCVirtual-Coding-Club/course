---
layout: default
title: Generate Random Whole Numbers with JavaScript
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 104
---
# Generate Random Whole Numbers with JavaScript
## Summary
- To create a random whole number, multiply a decimal by 20 (or other number), then use Math.floor() to round the number down to the nearest whole number.

## Final Code

{% highlight JavaScript %}
function randomWholeNum() {

  // Only change code below this line

  return Math.floor(Math.random() * 10);
}
{% endhighlight %}