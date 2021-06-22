---
layout: default
title: Remove Items Using splice()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 5
---
# Remove Items Using splice()
## Summary
- `.splice()` is used to remove an element anywhere in an array.
- `.splice()`'s first parameter represents the index on the array from which to begin removing elements, while the second parameter indicates the number of elements to delete.

## Final Code

{% highlight JavaScript %}
const arr = [2, 4, 5, 1, 7, 5, 2, 1];
// Only change code below this line
arr.splice(1, 4)
// Only change code above this line
console.log(arr);
{% endhighlight %}