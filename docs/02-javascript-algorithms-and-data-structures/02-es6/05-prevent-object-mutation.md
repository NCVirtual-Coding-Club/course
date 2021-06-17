---
layout: default
title: Prevent Object Mutation
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 5
---
# Prevent Object Mutation
## Summary
- The function `Object.freeze` is used to prevent data mutation.

## Final Code

{% highlight JavaScript %}
function freezeObj() {
  const MATH_CONSTANTS = {
    PI: 3.14
  };
  // Only change code below this line
  Object.freeze(MATH_CONSTANTS)

  // Only change code above this line
  try {
    MATH_CONSTANTS.PI = 99;
  } catch(ex) {
    console.log(ex);
  }
  return MATH_CONSTANTS.PI;
}
const PI = freezeObj();
{% endhighlight %}