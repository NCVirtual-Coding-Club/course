---
layout: default
title: Use class Syntax to Define a Constructor Function
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 20
---
# Use class Syntax to Define a Constructor Function
## Summary
- `class` can be used to replace a constructor function.

## Final Code

{% highlight JavaScript %}
// Only change code below this line
class Vegetable {
  constructor(name) {
    this.name = name;
  }
}
// Only change code above this line

const carrot = new Vegetable('carrot');
console.log(carrot.name); // Should display 'carrot'
{% endhighlight %}