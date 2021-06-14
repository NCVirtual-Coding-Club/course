---
layout: default
title: Multiple Identical Options in Switch Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 76
---
# Multiple Identical Options in Switch Statements
## Summary
- You can add multiple inputs to get the same output.

## Final Code

{% highlight JavaScript %}
function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case 1:
    case 2:
    case 3:
      return "Low";
      break;
    case 4:
    case 5:
    case 6:
      return "Mid";
      break;
    case 7:
    case 8:
    case 9:
      return "High";
      break;
  }


  // Only change code above this line
  return answer;
}

sequentialSizes(1);
{% endhighlight %}