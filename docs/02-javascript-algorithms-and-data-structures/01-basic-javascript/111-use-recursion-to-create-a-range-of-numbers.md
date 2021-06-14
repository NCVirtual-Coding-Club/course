---
layout: default
title: Use Recursion to Create a Range of Numbers
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 111
---
# Use Recursion to Create a Range of Numbers
## Summary

## Final Code

{% highlight JavaScript %}
function rangeOfNumbers(startNum, endNum) {
  if (endNum - startNum === 0) {
    return [startNum];
  } else {
    var numbers = rangeOfNumbers(startNum, endNum - 1);
    numbers.push(endNum);
    return numbers;
  }
}
{% endhighlight %}