---
layout: default
title: Testing Objects for Properties
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 89
---
# Testing Objects for Properties
## Summary
- `.hasOwnProperty(propname)` is used to check of a object has a specific property.
- Returns `true` or `false`.

## Final Code

{% highlight JavaScript %}
function checkObj(obj, checkProp) {
  // Only change code below this line
  if(obj.hasOwnProperty(checkProp)) {
    return obj[checkProp];
  } else {
    return "Not Found";
  }
  // Only change code above this line
}
{% endhighlight %}