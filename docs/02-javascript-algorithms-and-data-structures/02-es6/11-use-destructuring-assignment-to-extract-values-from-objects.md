---
layout: default
title: Use Destructuring Assignment to Extract Values from Objects
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 11
---
# Use Destructuring Assignment to Extract Values from Objects
## Summary
- Destructuring assignment can be used to neatly assign values taken directly from an object.

## Final Code

{% highlight JavaScript %}
const HIGH_TEMPERATURES = {
  yesterday: 75,
  today: 77,
  tomorrow: 80
};

// Only change code below this line

const {today, tomorrow} = HIGH_TEMPERATURES

// Only change code above this line
{% endhighlight %}