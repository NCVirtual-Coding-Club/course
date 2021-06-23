---
layout: default
title: Modify an Object Nested Within an Object
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 14
---
# Modify an Object Nested Within an Object
## Summary
- Object properties can be nested to an arbitrary depth, and their values can be any type of data supported by JavaScript.

## Final Code

{% highlight JavaScript %}
let userActivity = {
  id: 23894201352,
  date: 'January 1, 2017',
  data: {
    totalUsers: 51,
    online: 42
  }
};

// Only change code below this line
userActivity.data.online = 45;
// Only change code above this line

console.log(userActivity);
{% endhighlight %}