---
layout: default
title: Catch Use of Assignment Operator Instead of Equality Operator
parent: Debugging
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 7
---
# Catch Use of Assignment Operator Instead of Equality Operator

## Final Code

{% highlight JavaScript %}
let x = 7;
let y = 9;
let result = "to come";

if(x == y) {
  result = "Equal!";
} else {
  result = "Not equal!";
}

console.log(result);
{% endhighlight %}