---
layout: default
title: Add Items to an Array with push() and unshift()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 3
---
# Add Items to an Array with push() and unshift()
## Summary
- `.push` and `.unshift` can be used to modify an array.
- The `push()` method adds elements to the end of an array.
- The `unshift()` adds elements to the beginning.

## Final Code

{% highlight JavaScript %}
function mixedNumbers(arr) {
  // Only change code below this line
  arr.unshift('I', 2, 'three')
  arr.push(7, 'VIII', 9)
  // Only change code above this line
  return arr;
}

console.log(mixedNumbers(['IV', 5, 'six']));
{% endhighlight %}