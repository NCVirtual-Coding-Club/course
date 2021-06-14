---
layout: default
title: $$$
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: ##
---
# $$$
## Summary
- A queue is an abstract Data Structure where items are kept in order.
- New items are added to the back of the queue, and old items are taken off.

## Final Code

{% highlight JavaScript %}
function nextInLine(arr, item) {
  // Only change code below this line
  arr.push(item);
  arr.push(item);
  return arr.shift();
  // Only change code above this line
  

}

// Setup
var testArr = [1,2,3,4,5];

// Display code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6));
console.log("After: " + JSON.stringify(testArr));
{% endhighlight %}