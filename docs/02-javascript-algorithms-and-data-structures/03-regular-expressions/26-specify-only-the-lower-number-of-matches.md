---
layout: default
title: Specify Only the Lower Number of Matches
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 26
---
# Specify Only the Lower Number of Matches
## Summary
- When using a specific range, leaving a range blank will remove such limit.

## Final Code

{% highlight JavaScript %}
let haStr = "Hazzzzah";
let haRegex = /Haz{4,}ah/; // Change this line
let result = haRegex.test(haStr);
{% endhighlight %}