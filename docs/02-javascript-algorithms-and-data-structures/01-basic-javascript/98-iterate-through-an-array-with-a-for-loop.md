---
layout: default
title: Iterate Through an Array with a For Loop
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 98
---
# Iterate Through an Array with a For Loop
## Summary
- A `for` loop can be used to iterate through an array.

## Final Code

{% highlight JavaScript %}
// Setup
var myArr = [ 2, 3, 4, 5, 6];

// Only change code below this line

var total = 0;

for (var i = 0; i < myArr.length; i++) {
  total+=myArr[i];
}
{% endhighlight %}