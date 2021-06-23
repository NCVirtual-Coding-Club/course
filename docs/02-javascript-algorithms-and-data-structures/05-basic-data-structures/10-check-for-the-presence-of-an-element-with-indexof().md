---
layout: default
title: Check For The Presence of an Element With indexOf()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 10
---
# Check For The Presence of an Element With indexOf()
## Summary
- `indexOf()` can be used to find the index of a specific array.

## Final Code

{% highlight JavaScript %}
function quickCheck(arr, elem) {
  // Only change code below this line
  if (arr.indexOf(elem) === -1) {
    return false;
  } else {
    return true;
  }
  // Only change code above this line
}

console.log(quickCheck(['squash', 'onions', 'shallots'], 'mushrooms'));
{% endhighlight %}