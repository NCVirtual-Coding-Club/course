---
layout: default
title: Understanding Undefined Value returned from a Function
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 53
---
# Understanding Undefined Value returned from a Function
## Summary
- If a `return` value doesn't have a value, it is `undefined`.

## Final Code

{% highlight JavaScript %}
// Setup
var sum = 0;

function addThree() {
  sum = sum + 3;
}

// Only change code below this line
function addFive(num) {
  sum+=5;
}

// Only change code above this line

addThree();
addFive();
{% endhighlight %}