---
layout: default
title: Write Concise Declarative Functions with ES6
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 19
---
# Write Concise Declarative Functions with ES6
## Summary
- The `function` keyword is not needed to define a function in ES6.

## Final Code

{% highlight JavaScript %}
// Only change code below this line
const bicycle = {
  gear: 2,
  setGear(newGear) {
    this.gear = newGear;
  }
};
// Only change code above this line
bicycle.setGear(3);
console.log(bicycle.gear);
{% endhighlight %}