---
layout: default
title: Extract Matches
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 5
---
# Extract Matches
## Summary
- The `.match()` method is used to return the matches of a search.

## Final Code

{% highlight JavaScript %}
let extractStr = "Extract the word 'coding' from this string.";
let codingRegex = /coding/; // Change this line
let result = extractStr.match(codingRegex); // Change this line
{% endhighlight %}