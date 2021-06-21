---
layout: default
title: Specify Exact Number of Matches
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 27
---
# Specify Exact Number of Matches
## Summary
- To specify a certain number of patterns, have that one number between two curly brackets.

## Final Code

{% highlight JavaScript %}
let timStr = "Timmmmber";
let timRegex = /Tim{4}ber/; // Change this line
let result = timRegex.test(timStr);
{% endhighlight %}