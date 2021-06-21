---
layout: default
title: Catch Arguments Passed in the Wrong Order When Calling a Function
parent: Debugging
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 9
---
# Catch Arguments Passed in the Wrong Order When Calling a Function

## Final Code

{% highlight JavaScript %}
function raiseToPower(b, e) {
  return Math.pow(b, e);
}

let base = 2;
let exp = 3;
let power = raiseToPower(base, exp);
console.log(power);
{% endhighlight %}