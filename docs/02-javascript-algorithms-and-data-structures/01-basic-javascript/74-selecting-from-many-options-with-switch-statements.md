---
layout: default
title: Selecting from Many Options with Switch Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 74
---
# Selecting from Many Options with Switch Statements
## Summary
- A `switch` statement tests a value and can have many case statements which define various possible values.
- `break` tells JavaScript to stop executing statements.

## Final Code

{% highlight JavaScript %}
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
switch(val) {
  case 1:
    answer = "alpha";
    break;
  case 2:
    answer = "beta";
    break;
  case 3:
    answer = "gamma";
    break;
  case 4:
    answer = "delta";
    break;
}


  // Only change code above this line
  return answer;
}

caseInSwitch(1);
{% endhighlight %}