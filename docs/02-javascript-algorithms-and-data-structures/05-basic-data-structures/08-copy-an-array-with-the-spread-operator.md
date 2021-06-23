---
layout: default
title: Copy an Array with the Spread Operator
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 8
---
# Copy an Array with the Spread Operator
## Summary
- Spread syntax (`...myArray`) allows an entire array to be copyed.

## Final Code

{% highlight JavaScript %}
function copyMachine(arr, num) {
  let newArr = [];
  while (num >= 1) {
    // Only change code below this line
    newArr.push([...arr]);
    // Only change code above this line
    num--;
  }
  return newArr;
}

console.log(copyMachine([true, false, true], 2));
{% endhighlight %}