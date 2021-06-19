---
layout: default
title: Using the Test Method
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 1
---
# Using the Test Method
## Summary
- Regular expressions are used in programming languages to match parts of strings.
- The `.test()` method takes the regex, applies it to a string (which is placed inside the parentheses), and returns `true` or `false`.

## Final Code

{% highlight JavaScript %}
let myString = "Hello, World!";
let myRegex = /Hello/;
let result = myRegex.test(myString); // Change this line
{% endhighlight %}