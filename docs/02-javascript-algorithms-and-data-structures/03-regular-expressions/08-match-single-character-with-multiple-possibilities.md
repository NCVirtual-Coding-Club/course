---
layout: default
title: Match Single Character with Multiple Possibilities
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 8
---
# Match Single Character with Multiple Possibilities
## Summary
- Character classes `[]` can be used define a group of characters to match.

## Final Code

{% highlight JavaScript %}
let quoteSample = "Beware of bugs in the above code; I have only proved it correct, not tried it.";
let vowelRegex = /[aeiou]/gi; // Change this line
let result = quoteSample.match(vowelRegex); // Change this line
{% endhighlight %}