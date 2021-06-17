---
layout: default
title: Use Destructuring Assignment to Assign Variables from Objects
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 12
---
# Use Destructuring Assignment to Assign Variables from Objects
## Summary
- Destructuring allows a new variable name to be assigned when extracting values.

## Final Code

{% highlight JavaScript %}
const HIGH_TEMPERATURES = {
  yesterday: 75,
  today: 77,
  tomorrow: 80
};

// Only change code below this line

const {today: highToday, tomorrow: highTomorrow} = HIGH_TEMPERATURES

// Only change code above this line
{% endhighlight %}