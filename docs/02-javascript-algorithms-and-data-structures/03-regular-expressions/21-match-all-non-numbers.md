---
layout: default
title: Match All Non-Numbers
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 21
---
# Match All Non-Numbers
## Summary
- `\D` is used to search non-digit characters.

## Final Code

{% highlight JavaScript %}
let movieName = "2001: A Space Odyssey";
let noNumRegex = /\D/gi; // Change this line
let result = movieName.match(noNumRegex).length;
{% endhighlight %}