---
layout: default
title: Match Anything with Wildcard Period
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 7
---
# Match Anything with Wildcard Period
## Summary
- The wildcard character `.` is used to search based on any one or more characters.

## Final Code

{% highlight JavaScript %}
let exampleStr = "Let's have fun with regular expressions!";
let unRegex = /un./; // Change this line
let result = unRegex.test(exampleStr);
{% endhighlight %}