---
layout: default
title: Add Items Using splice()
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 6
---
# Add Items Using splice()
## Summary
- The third parameter in `.splice()` can be used to add elements into an array, as a replacement.

## Final Code

{% highlight JavaScript %}
function htmlColorNames(arr) {
  // Only change code below this line
  arr.splice(0, 2, 'DarkSalmon', 'BlanchedAlmond')
  // Only change code above this line
  return arr;
}

console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush'...]));
{% endhighlight %}