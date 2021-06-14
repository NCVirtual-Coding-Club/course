---
layout: default
title: Replace Loops using Recursion
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 101
---
# Replace Loops using Recursion
## Summary
- Recursion is the concept that a function can be expressed in terms of itself.

## Final Code

{% highlight JavaScript %}
function sum(arr, n) {
  // Only change code below this line
  if(n <= 0) {
    return 0;
  } else {
    return sum(arr, n - 1) + arr[n - 1];
  }
  // Only change code above this line
}
{% endhighlight %}