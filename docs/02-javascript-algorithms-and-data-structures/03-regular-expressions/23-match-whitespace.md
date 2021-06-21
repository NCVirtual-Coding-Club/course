---
layout: default
title: Match Whitespace
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 23
---
# Match Whitespace
## Summary
- `\s` can be used to search for whitespace.

## Final Code

{% highlight JavaScript %}
let sample = "Whitespace is important in separating words";
let countWhiteSpace = /\s/gi; // Change this line
let result = sample.match(countWhiteSpace);
{% endhighlight %}