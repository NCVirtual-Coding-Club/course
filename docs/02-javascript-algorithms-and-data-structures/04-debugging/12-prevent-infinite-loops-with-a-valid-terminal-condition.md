---
layout: default
title: Prevent Infinite Loops with a Valid Terminal Condition
parent: Debugging
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 12
---
# Prevent Infinite Loops with a Valid Terminal Condition

## Final Code

{% highlight JavaScript %}
function myFunc() {
  for (let i = 1; i <= 4; i += 2) {
    console.log("Still going!");
  }
}
{% endhighlight %}