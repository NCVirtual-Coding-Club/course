---
layout: default
title: Use the Rest Parameter with Function Parameters
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 9
---
# Use the Rest Parameter with Function Parameters
## Summary
- The rest parameter allows for a variable amount of arguments.
- This allows the use of `map()`, `filter()`, and `reduce`.

## Final Code

{% highlight JavaScript %}
const sum = (...args) => {
  return args.reduce((a, b) => a + b, 0);
}
console.log(sum(1, 2, 3));
{% endhighlight %}