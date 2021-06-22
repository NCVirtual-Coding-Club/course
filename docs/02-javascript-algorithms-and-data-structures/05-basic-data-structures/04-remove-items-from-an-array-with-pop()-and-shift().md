---
layout: default
title: Remove Items from an Array with pop() and shift()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 4
---
# Remove Items from an Array with pop() and shift()
## Summary
- `pop()` removes an element from the end of an array.
- `shift()` removes an element from the beginning of an array. 

## Final Code

{% highlight JavaScript %}
function popShift(arr) {
  let popped = arr.pop(); // Change this line
  let shifted = arr.shift(); // Change this line
  return [shifted, popped];
}

console.log(popShift(['challenge', 'is', 'not', 'complete']));
{% endhighlight %}