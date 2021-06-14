---
layout: default
title: Use Recursion to Create a Countdown
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 110
---
# Use Recursion to Create a Countdown
## Summary
- The base case tells the recursive function when it no longer needs to call itself.
- The recursive call executres the original function with different arguments.

## Final Code

{% highlight JavaScript %}
// Only change code below this line
function countdown(n) {
  if (n < 1) {
    return [];
  } else {
    const arr = countdown(n - 1);
    arr.unshift(n);
    return arr;
  }
}
// Only change code above this line
{% endhighlight %}