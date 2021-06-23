---
layout: default
title: Use the delete Keyword to Remove Object Properties
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 16
---
# Use the delete Keyword to Remove Object Properties
## Summary
- The `delete` keyword is used to remove a property from an object.

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

// Only change code below this line
delete foods.oranges;
delete foods.plums;
delete foods.strawberries;
// Only change code above this line

console.log(foods);
{% endhighlight %}