---
layout: default
title: Copy Array Items Using slice()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 7
---
# Copy Array Items Using slice()
## Summary
- `slice()` copies a given number of elements to a new array.
    - Uses two parameters.
- `slice()` leaves the original array untouched.

## Final Code

{% highlight JavaScript %}
function forecast(arr) {
  // Only change code below this line
  arr = arr.slice(2, 4)
  return arr;
}

// Only change code above this line
console.log(forecast(['cold', 'rainy', 'warm', 'sunny', 'cool', 'thunderstorms']));
{% endhighlight %}