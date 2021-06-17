---
layout: default
title: Mutate an Array Declared with const
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 4
---
# Mutate an Array Declared with const
## Summary
- Objects inside a `const` variable are still mutable.

## Final Code

{% highlight JavaScript %}
const s = [5, 7, 2];
function editInPlace() {
  // Only change code below this line
  s[0] = 2;
  s[1] = 5;
  s[2] = 7;
  // Only change code above this line
}
editInPlace();
{% endhighlight %}