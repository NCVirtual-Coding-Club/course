---
layout: default
title: Match Beginning String Patterns
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 16
---
# Match Beginning String Patterns
## Summary
- When used outside of a character set, `^` is used to search for patterns at the beginning of a string.

## Final Code

{% highlight JavaScript %}
let rickyAndCal = "Cal and Ricky both like racing.";
let calRegex = /^Cal/; // Change this line
let result = calRegex.test(rickyAndCal);
{% endhighlight %}