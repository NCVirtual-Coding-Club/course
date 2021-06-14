---
layout: default
title: Chaining If Else Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 72
---
# Chaining If Else Statements
## Summary
- `if`/`else` statements can be chained together for complex logic.

## Final Code

{% highlight JavaScript %}
function testSize(num) {
  // Only change code below this line
  if (num < 5) {
    return "Tiny";
  } else if (num < 10) {
    return "Small";
  } else if (num < 15) {
    return "Medium";
  } else if (num < 20) {
    return "Large";
  } else if (num >= 20) {
    return "Huge";
  } else {
    return "Change Me";
  }

  // Only change code above this line
}

testSize(7);
{% endhighlight %}