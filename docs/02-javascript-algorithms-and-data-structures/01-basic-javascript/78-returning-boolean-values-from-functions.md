---
layout: default
title: Returning Boolean Values from Functions
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 78
---
# Returning Boolean Values from Functions
## Summary
- It is better to return `true` or `false` directly from `===` than to use an `if`/`else` statement.

## Final Code

{% highlight JavaScript %}
function isLess(a, b) {
  // Only change code below this line
  return a < b;
  // Only change code above this line
}

isLess(10, 15);
{% endhighlight %}