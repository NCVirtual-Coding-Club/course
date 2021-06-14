---
layout: default
title: Iterate with JavaScript While Loops
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 94
---
# Iterate with JavaScript While Loops
## Summary
- Code can be ran multiple times using a loop.
- The `while` loop only runs while a specific condition is true.

## Final Code

{% highlight JavaScript %}
// Setup
var myArray = [];

// Only change code below this line
var i = 5;
while(i >= 0) {
  myArray.push(i);
  i--;
}
{% endhighlight %}