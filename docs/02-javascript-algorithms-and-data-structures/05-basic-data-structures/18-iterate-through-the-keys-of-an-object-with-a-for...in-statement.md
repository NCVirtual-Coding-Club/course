---
layout: default
title: Iterate Through the Keys of an Object with a for...in Statement
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 18
---
# Iterate Through the Keys of an Object with a for...in Statement
## Summary
- The for..in statement can be used to iterate through the keys within an object.

## Final Code

{% highlight JavaScript %}
function countOnline(usersObj) {
  // Only change code below this line
  let result = 0;
  for (let user in usersObj) {
    if (usersObj[user].online === true) {
      result++;
    }
  }
  return result;
  // Only change code above this line
}
{% endhighlight %}