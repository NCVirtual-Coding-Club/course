---
layout: default
title: Access Multi-Dimensional Arrays With Indexes
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 41
---
# Access Multi-Dimensional Arrays With Indexes
## Summary
- Arrays nested inside other arrays are called mutli-dimensional arrays.

## Final Code

{% highlight JavaScript %}
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

var myData = myArray[2][1];
{% endhighlight %}