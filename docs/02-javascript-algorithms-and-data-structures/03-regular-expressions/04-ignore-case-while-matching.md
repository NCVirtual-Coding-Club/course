---
layout: default
title: Ignore Case While Matching
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 4
---
# Ignore Case While Matching
## Summary
- The `i` flag is used to ignore case in a search.

## Final Code

{% highlight JavaScript %}
let myString = "freeCodeCamp";
let fccRegex = /freeCodeCamp/i; // Change this line
let result = fccRegex.test(myString);
{% endhighlight %}