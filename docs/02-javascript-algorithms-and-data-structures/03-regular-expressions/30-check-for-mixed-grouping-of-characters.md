---
layout: default
title: Check For Mixed Grouping of Characters
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 30
---
# Check For Mixed Grouping of Characters
## Summary
- Parentheses can be used to check string groups.

## Final Code

{% highlight JavaScript %}
let myString = "Eleanor Roosevelt";
let myRegex = /(Franklin|Eleanor).*Roosevelt/;
let result = myRegex.test(myString); // Change this line
// After passing the challenge experiment with myString and see how the grouping works
{% endhighlight %}