---
layout: default
title: Use Capture Groups to Search and Replace
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 32
---
# Use Capture Groups to Search and Replace
## Summary
- `.replace` can be used to search and replace text.

## Final Code

{% highlight JavaScript %}
let str = "one two three";
let fixRegex = /(\w+)\s(\w+)\s(\w+)/; // Change this line
let replaceText = "$3 $2 $1"; // Change this line
let result = str.replace(fixRegex, replaceText);
{% endhighlight %}