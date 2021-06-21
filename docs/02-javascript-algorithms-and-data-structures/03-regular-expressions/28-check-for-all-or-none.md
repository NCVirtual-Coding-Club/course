---
layout: default
title: Check for All or None
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 28
---
# Check for All or None
## Summary
- To specify the possible existences of an element, use `?`

## Final Code

{% highlight JavaScript %}
let favWord = "favorite";
let favRegex = /favou?rite/; // Change this line
let result = favRegex.test(favWord);
{% endhighlight %}