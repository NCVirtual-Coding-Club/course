---
layout: default
title: Create Strings using Template Literals
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 17
---
# Create Strings using Template Literals
## Summary
- Template literals allow the creation of multi-line strings and the use of string interpolation features to create strings.

## Final Code

{% highlight JavaScript %}
const result = {
  success: ["max-length", "no-amd", "prefer-arrow-functions"],
  failure: ["no-var", "var-on-top", "linebreak"],
  skipped: ["no-extra-semi", "no-dup-keys"]
};
function makeList(arr) {
  // Only change code below this line
  const failureItems = [];
  for (let i = 0; i < arr.length; i++) {
    failureItems.push(`<li class="text-warning">${arr[i]}</li>`)
  }
  
  // Only change code above this line

  console.log(failureItems);
  return failureItems;
}

const failuresList = makeList(result.failure);
{% endhighlight %}