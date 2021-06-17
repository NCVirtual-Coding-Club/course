---
layout: default
title: Write Concise Object Literal Declarations Using Object Property Shorthand
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 18
---
# Write Concise Object Literal Declarations Using Object Property Shorthand
## Summary
- Object literals can be used to prevent to use of redundant variables.

## Final Code

{% highlight JavaScript %}
const createPerson = (name, age, gender) => {
  // Only change code below this line

  return {
    name,
    age,
    gender,
  };
  
  // Only change code above this line
};
{% endhighlight %}