---
layout: default
title: Use Destructuring Assignment with the Rest Parameter to Reassign Array Elements
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 15
---
# Use Destructuring Assignment with the Rest Parameter to Reassign Array Elements
## Summary
- When destructuring arrays, elements can be split.

## Final Code

{% highlight JavaScript %}
const source = [1,2,3,4,5,6,7,8,9,10];
function removeFirstTwo(list) {
  // Only change code below this line
  const [a, b, ...arr] = list; // Change this line
  // Only change code above this line
  return arr;
}
const arr = removeFirstTwo(source);
{% endhighlight %}