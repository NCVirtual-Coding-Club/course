---
layout: default
title: Global Scope and Functions
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 49
---
# Global Scope and Functions
## Summary
- Scope refers to the visibility of variables.
- Variables with a global scope can be accessed anywhere using JavaScript code.
- Variables which are declared without the var keyword are automatically created in the global scope.

## Final Code

{% highlight JavaScript %}
// Declare the myGlobal variable below this line


function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal = 5;
}
var myGlobal = 10;
// Only change code above this line

function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
{% endhighlight %}