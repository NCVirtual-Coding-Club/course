---
layout: default
title: Find Characters with Lazy Matching
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 14
---
# Find Characters with Lazy Matching
## Summary
- The `?` character can be used to search for the smallest possible match.

## Final Code

{% highlight JavaScript %}
let text = "<h1>Winter is coming</h1>";
let myRegex = /<.*?>/; // Change this line
let result = text.match(myRegex);
{% endhighlight %}