---
layout: default
title: Match a Literal String with Different Possibilities
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 3
---
# Match a Literal String with Different Possibilities
## Summary
- Adding `|` to a Regex can be used to add search items to a single `.text`.

## Final Code

{% highlight JavaScript %}
let petString = "James has a pet cat.";
let petRegex = /dog|cat|bird|fish/; // Change this line
let result = petRegex.test(petString);
{% endhighlight %}