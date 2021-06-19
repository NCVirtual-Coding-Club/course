---
layout: default
title: Match Numbers and Letters of the Alphabet
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 10
---
# Match Numbers and Letters of the Alphabet
## Summary
- The hyphen character `-` can be used to define a range of numbers.

## Final Code

{% highlight JavaScript %}
let quoteSample = "Blueberry 3.141592653s are delicious.";
let myRegex = /[h-s2-6]/gi; // Change this line
let result = quoteSample.match(myRegex); // Change this line
{% endhighlight %}