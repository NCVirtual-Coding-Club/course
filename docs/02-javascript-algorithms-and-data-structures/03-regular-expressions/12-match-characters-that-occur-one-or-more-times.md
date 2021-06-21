---
layout: default
title: Match Characters that Occur One or More Times
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 12
---
# Match Characters that Occur One or More Times
## Summary
- The `+` character is used to match a character that occurs consecutively.

## Final Code

{% highlight JavaScript %}
let difficultSpelling = "Mississippi";
let myRegex = /s+/gi; // Change this line
let result = difficultSpelling.match(myRegex);
{% endhighlight %}