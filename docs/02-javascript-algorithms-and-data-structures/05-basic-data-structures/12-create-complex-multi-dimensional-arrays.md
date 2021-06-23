---
layout: default
title: Create complex multi-dimensional arrays
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 12
---
# Create complex multi-dimensional arrays
## Summary
- Arrays can be nested to an arbitrary depth, and their values can be any type of data supported by JavaScript

## Final Code

{% highlight JavaScript %}
let myNestedArray = [
  // change code below this line
  ["unshift", false, 1, 2, 3, "complex", "nested"],
  ["loop", "shift", 6, 7, 1000, "method"],
  ["concat", false, true, "spread", "array", ["deep"]],
  ["mutate", 1327.98, "splice", "slice", "push", [["deeper"]]],
  ["iterate", 1.3849, 7, "8.4876", "arbitrary", "depth", [[["deepest"]]]]
  // change code above this line
];
{% endhighlight %}