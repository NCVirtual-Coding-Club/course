---
layout: default
title: Understanding Uninitialized Variables
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 6
---
# Understanding Uninitialized Variables
## Summary
- JavaScript variables are declared with an initial value of `undefined`.
- If you do a mathematical operation on an `undefined` variable your result will be `NaN` meaning ___Not A Number___.

## Final Code

{% highlight JavaScript %}
// Only change code below this line
var a = 5;
var b = 10;
var c = "I am a";
// Only change code above this line

a = a + 1;
b = b + 5;
c = c + " String!";
{% endhighlight %}