---
layout: default
title: Adding a Default Option in Switch Statements
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 75
---
# Adding a Default Option in Switch Statements
## Summary
- The `default` statement is executed in a `switch` statement when no other conditions are met.

## Final Code

{% highlight JavaScript %}
function switchOfStuff(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case "a":
      return "apple";
      break;
    case "b":
      return "bird";
      break;
    case "c":
      return "cat";
      break;
    default:
      return "stuff";
      break;
  }


  // Only change code above this line
  return answer;
}

switchOfStuff(1);
{% endhighlight %}