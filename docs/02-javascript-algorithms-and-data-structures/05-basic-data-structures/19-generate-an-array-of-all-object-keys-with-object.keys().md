---
layout: default
title: Generate an Array of All Object Keys with Object.keys()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 19
---
# Generate an Array of All Object Keys with Object.keys()
## Summary
- `Object.keys()` can be used to create an array that contains all keys stored in an object.

## Final Code

{% highlight JavaScript %}
let users = {
  Alan: {
    age: 27,
    online: false
  },
  Jeff: {
    age: 32,
    online: true
  },
  Sarah: {
    age: 48,
    online: false
  },
  Ryan: {
    age: 19,
    online: true
  }
};

function getArrayOfUsers(obj) {
  // Only change code below this line
  return Object.keys(obj);
  // Only change code above this line
}

console.log(getArrayOfUsers(users));
{% endhighlight %}