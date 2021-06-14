---
layout: default
title: Global vs. Local Scope in Functions
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 51
---
# Global vs. Local Scope in Functions
## Summary
- It is possible to have both local and global variables with the same name.

## Final Code

{% highlight JavaScript %}
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
    var outerWear = "sweater";


  // Only change code above this line
  return outerWear;
}

myOutfit();
{% endhighlight %}