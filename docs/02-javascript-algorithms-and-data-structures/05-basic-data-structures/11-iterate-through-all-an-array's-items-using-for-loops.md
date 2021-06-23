---
layout: default
title: Iterate Through All an Array's Items Using For Loops
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 11
---
# Iterate Through All an Array's Items Using For Loops
## Summary
- A `for` loop can be used to access each set of data from an array.

## Final Code

{% highlight JavaScript %}
function filteredArray(arr, elem) {
  let newArr = [];
  // Only change code below this line
  for (let i = 0; i < arr.length; i++) {
    if (arr[i].indexOf(elem) == -1) {
      newArr.push(arr[i]);
    }
  }
  // Only change code above this line
  return newArr;
}

console.log(filteredArray([[3, 2, 3], [1, 6, 3], [3, 13, 26], [19, 3, 9]], 3));
{% endhighlight %}