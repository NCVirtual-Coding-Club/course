---
layout: default
title: Declare a Read-Only Variable with the const Keyword
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 3
---
# Declare a Read-Only Variable with the const Keyword
## Summary
- The `const` keyword can be used to create read-only variables.

## Final Code

{% highlight JavaScript %}
function printManyTimes(str) {

  // Only change code below this line

  const SENTENCE = str + " is cool!";
  for (let i = 0; i < str.length; i+=2) {
    console.log(SENTENCE);
  }

  // Only change code above this line

}
printManyTimes("freeCodeCamp");
{% endhighlight %}