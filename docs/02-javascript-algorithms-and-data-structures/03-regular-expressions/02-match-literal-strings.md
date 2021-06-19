---
layout: default
title: Match Literal Strings
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 2
---
# Match Literal Strings
## Summary
- Regex searches will only return true if two strings match perfectly.

## Final Code

{% highlight JavaScript %}
let waldoIsHiding = "Somewhere Waldo is hiding in this text.";
let waldoRegex = /Waldo/; // Change this line
let result = waldoRegex.test(waldoIsHiding);
{% endhighlight %}