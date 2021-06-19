---
layout: default
title: Find More Than the First Match
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 6
---
# Find More Than the First Match
## Summary
- The `g` flag is used to match a search more than once.

## Final Code

{% highlight JavaScript %}
let twinkleStar = "Twinkle, twinkle, little star";
let starRegex = /Twinkle/gi; // Change this line
let result = twinkleStar.match(starRegex); // Change this line
{% endhighlight %}