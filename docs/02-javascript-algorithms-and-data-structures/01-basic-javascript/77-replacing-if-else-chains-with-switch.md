---
layout: default
title: Replacing If Else Chains with Switch
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 77
---
# Replacing If Else Chains with Switch
## Summary
- `if`/`else if` statements can be replaced with switch statements.

## Final Code

{% highlight JavaScript %}
function chainToSwitch(val) {
  var answer = "";
  // Only change code below this line

  switch(val) {
    case "bob":
      answer = "Marley";
      break;
    case 42:
      answer = "The Answer";
      break;
    case 1:
      answer = "There is no #1";
      break;
    case 99:
      answer = "Missed me by this much!";
      break;
    case 7:
      answer = "Ate Nine";
      break;
  }

  // Only change code above this line
  return answer;
}

chainToSwitch(7);
{% endhighlight %}