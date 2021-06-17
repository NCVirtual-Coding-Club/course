---
layout: default
title: Use the Spread Operator to Evaluate Arrays In-Place
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 10
---
# Use the Spread Operator to Evaluate Arrays In-Place
## Summary
- ES5 uses `apply()` to compute the maximum value in an array using `Math.math()`
- `apply()` is important as Math.max() expects comma-separated arguments.

## Final Code

{% highlight JavaScript %}
const arr1 = ['JAN', 'FEB', 'MAR', 'APR', 'MAY'];
let arr2;

arr2 = [...arr1];  // Change this line

console.log(arr2);
{% endhighlight %}