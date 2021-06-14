---
layout: default
title: Iterate with JavaScript Do...While Loops
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 100
---
# Iterate with JavaScript Do...While Loops
## Summary
- The `do...while` checks the conditions after the loop is ran (during an iteration).

## Final Code

{% highlight JavaScript %}
// Setup
var myArray = [];
var i = 10;

// Only change code below this line
do {
  myArray.push(i);
  i++;
} while (i < 5);
{% endhighlight %}