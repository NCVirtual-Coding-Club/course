---
layout: default
title: Remove Whitespace from Start and End
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 33
---
# Remove Whitespace from Start and End
## Summary

## Final Code

{% highlight JavaScript %}
let hello = "   Hello, World!  ";
let wsRegex = /^\s+|\s+$/g; // Change this line
let result = hello.replace(wsRegex, ""); // Change this line
{% endhighlight %}