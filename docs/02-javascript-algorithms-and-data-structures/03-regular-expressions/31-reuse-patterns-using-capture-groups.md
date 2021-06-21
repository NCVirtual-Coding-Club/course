---
layout: default
title: Reuse Patterns Using Capture Groups
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 31
---
# Reuse Patterns Using Capture Groups
## Summary
- Parentheses are used to find repeat substrings.
- To specify where that repeat string will appear, use a backslash and then a number.

## Final Code

{% highlight JavaScript %}
let repeatNum = "42 42 42";
let reRegex = /^(\d+)\s\1\s\1$/; // Change this line
let result = reRegex.test(repeatNum);
{% endhighlight %}