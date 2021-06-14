---
layout: default
title: Nesting For Loops
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 99
---
# Nesting For Loops
## Summary
- `for` loops can be used to loop through multi-dimensional arrays.

## Final Code

{% highlight JavaScript %}
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
    for (var i = 0; i < arr.length; i++) {
      for (var j=0; j < arr[i].length; j++) {
        product*=(arr[i][j]);
      }
    }
  // Only change code above this line
  return product;
}

multiplyAll([[1,2],[3,4],[5,6,7]]);
{% endhighlight %}