---
layout: default
title: Match Everything But Letters and Numbers
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 19
---
# Match Everything But Letters and Numbers
## Summary
- `\W` searches for everything that is not a letter or number.

## Final Code

{% highlight JavaScript %}
let quoteSample = "The five boxing wizards jump quickly.";
let nonAlphabetRegex = /\W/gi; // Change this line
let result = quoteSample.match(nonAlphabetRegex).length;
{% endhighlight %}