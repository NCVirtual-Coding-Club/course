---
layout: default
title: Match Single Characters Not Specified
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 11
---
# Match Single Characters Not Specified
## Summary
- `^` is used to define characters that should not match.

## Final Code

{% highlight JavaScript %}
let quoteSample = "3 blind mice.";
let myRegex = /[^aeiou3]/gi; // Change this line
let result = quoteSample.match(myRegex); // Change this line
{% endhighlight %}