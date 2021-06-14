---
layout: default
title: Local Scope and Functions
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 50
---
# Local Scope and Functions
## Summary
- Variables which are declared within a function, as well as the function parameters, have local scope.
    - They are only visible within a certain function.

## Final Code

{% highlight JavaScript %}
function myLocalScope() {

  // Only change code below this line
  var myVar;
  console.log('inside myLocalScope', myVar);
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);
{% endhighlight %}