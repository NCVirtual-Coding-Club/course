---
layout: default
title: Write Arrow Functions with Parameters
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 7
---
# Write Arrow Functions with Parameters
## Summary
- Arguments can be passed in arrow functions.

## Final Code

{% highlight JavaScript %}
const myConcat = (arr1, arr2) => arr1.concat(arr2);

console.log(myConcat([1, 2], [3, 4, 5]));
{% endhighlight %}