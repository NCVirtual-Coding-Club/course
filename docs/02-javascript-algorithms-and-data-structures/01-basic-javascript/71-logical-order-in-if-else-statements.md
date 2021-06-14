---
layout: default
title: Logical Order in If Else Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 71
---
# Logical Order in If Else Statements
## Summary
- Order is important in `if`, `else if` statements.

## Final Code

{% highlight JavaScript %}
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if  (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

orderMyLogic(7);
{% endhighlight %}