---
layout: default
title: Use Destructuring Assignment to Pass an Object as a Function's Parameters
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 16
---
# Use Destructuring Assignment to Pass an Object as a Function's Parameters
## Summary
- In some cases, the object in a function argument can destructure itself.

## Final Code

{% highlight JavaScript %}
const stats = {
  max: 56.78,
  standard_deviation: 4.34,
  median: 34.54,
  mode: 23.87,
  min: -0.75,
  average: 35.85
};

// Only change code below this line
const half = ({max, min}) => (max + min) / 2.0; 
// Only change code above this line
{% endhighlight %}