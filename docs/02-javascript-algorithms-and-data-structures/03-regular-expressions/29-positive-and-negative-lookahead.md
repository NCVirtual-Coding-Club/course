---
layout: default
title: Positive and Negative Lookahead
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 29
---
# Positive and Negative Lookahead
## Summary
- Lookaheads are patterns that tell JavaScript to look-ahead in a string to check for patterns further along.
- A positive lookahead will look to make sure the element in the search pattern is there, but won't actually match it.
- A negative lookahead will look to make sure the element in the search pattern is not there.

## Final Code

{% highlight JavaScript %}
let sampleWord = "astronaut";
let pwRegex =  /(?=\w{6})(?=\w*\d{2})/;
let result = pwRegex.test(sampleWord);
{% endhighlight %}