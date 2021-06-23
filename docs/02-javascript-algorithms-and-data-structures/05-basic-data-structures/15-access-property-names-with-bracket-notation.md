---
layout: default
title: Access Property Names with Bracket Notation
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 15
---
# Access Property Names with Bracket Notation
## Summary
- Bracket notation can be used to check a value of a object property.

## Final Code

{% highlight JavaScript %}
let foods = {
  apples: 25,
  oranges: 32,
  plums: 28,
  bananas: 13,
  grapes: 35,
  strawberries: 27
};

function checkInventory(scannedItem) {
  // Only change code below this line
  return foods[scannedItem];
  // Only change code above this line
}

console.log(checkInventory("apples"));
{% endhighlight %}