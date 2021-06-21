---
layout: default
title: Specify Upper and Lower Number of Matches
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 25
---
# Specify Upper and Lower Number of Matches
## Summary
- Curly brackets can be used to match a certain range of patterns when using `+` or `*`.

## Final Code

{% highlight JavaScript %}
let ohStr = "Ohhh no";
let ohRegex = /Oh{3,6}\sno/; // Change this line
let result = ohRegex.test(ohStr);
{% endhighlight %}