---
layout: default
title: Match Non-Whitespace Characters
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 24
---
# Match Non-Whitespace Characters
## Summary
- `\S` is used to search for non-whitespace.

## Final Code

{% highlight JavaScript %}
let sample = "Whitespace is important in separating words";
let countNonWhiteSpace = /\S/gi; // Change this line
let result = sample.match(countNonWhiteSpace);
{% endhighlight %}