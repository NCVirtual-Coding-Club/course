---
layout: default
title: Introducing Else If Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 70
---
# Introducing Else If Statements
## Summary
- The `else if` statement can be used to add Additional conditional statements after an `if` statement.

## Final Code

{% highlight JavaScript %}
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  } else if (val < 5) {
    return "Smaller than 5";
  } else {
  return "Between 5 and 10";
  }
}

testElseIf(7);
{% endhighlight %}