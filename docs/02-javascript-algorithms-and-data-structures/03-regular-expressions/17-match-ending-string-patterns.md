---
layout: default
title: Match Ending String Patterns
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 17
---
# Match Ending String Patterns
## Summary
- `$` is used to search for patterns at the end of a string.

## Final Code

{% highlight JavaScript %}
let caboose = "The last car on a train is the caboose";
let lastRegex = /caboose$/; // Change this line
let result = lastRegex.test(caboose);
{% endhighlight %}