---
layout: default
title: Match Letters of the Alphabet
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 9
---
# Match Letters of the Alphabet
## Summary
- The hyphen character `-` can be used to define a range on the alphabet.

## Final Code

{% highlight JavaScript %}
let quoteSample = "The quick brown fox jumps over the lazy dog.";
let alphabetRegex = /[a-z]/gi; // Change this line
let result = quoteSample.match(alphabetRegex); // Change this line
{% endhighlight %}