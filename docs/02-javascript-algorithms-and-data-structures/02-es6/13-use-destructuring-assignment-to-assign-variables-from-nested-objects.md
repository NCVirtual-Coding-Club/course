---
layout: default
title: Use Destructuring Assignment to Assign Variables from Nested Objects
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 13
---
# Use Destructuring Assignment to Assign Variables from Nested Objects

## Final Code

{% highlight JavaScript %}
const LOCAL_FORECAST = {
  yesterday: { low: 61, high: 75 },
  today: { low: 64, high: 77 },
  tomorrow: { low: 68, high: 80 }
};

// Only change code below this line

const {today: {low: lowToday, high: highToday}} = LOCAL_FORECAST

// Only change code above this line
{% endhighlight %}