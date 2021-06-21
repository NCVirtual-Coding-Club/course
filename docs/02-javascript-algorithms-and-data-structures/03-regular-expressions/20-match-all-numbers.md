---
layout: default
title: Match All Numbers
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 20
---
# Match All Numbers
## Summary
- `\d` can be used to look for digit characters.

## Final Code

{% highlight JavaScript %}
let movieName = "2001: A Space Odyssey";
let numRegex = /\d/gi; // Change this line
let result = movieName.match(numRegex).length;
{% endhighlight %}