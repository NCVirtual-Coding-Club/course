---
layout: default
title: Introducing Else Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 69
---
# Introducing Else Statements
## Summary
- The `else` statement is used when an `if` statement is not `true`.

## Final Code

{% highlight JavaScript %}
function testElse(val) {
  var result = "";
  // Only change code below this line

  if (val > 5) {
    result = "Bigger than 5";
  } else {
    result = "5 or Smaller";
  }

  // Only change code above this line
  return result;
}

testElse(4);
{% endhighlight %}