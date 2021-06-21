---
layout: default
title: Match All Letters and Numbers
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 18
---
# Match All Letters and Numbers
## Summary
- `\w` is used to search for any letter or number.

## Final Code

{% highlight JavaScript %}
let quoteSample = "The five boxing wizards jump quickly.";
let alphabetRegexV2 = /\w/gi; // Change this line
let result = quoteSample.match(alphabetRegexV2).length;
{% endhighlight %}