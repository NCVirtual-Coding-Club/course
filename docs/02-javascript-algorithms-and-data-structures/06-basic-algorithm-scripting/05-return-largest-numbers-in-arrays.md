---
layout: default
title: Return Largest Numbers in Arrays
parent: Basic Algorithm Scripting
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 5
---
# Return Largest Numbers in Arrays

## Final Code

{% highlight JavaScript %}
function largestOfFour(arr) {
  let results = [];
  for (let i = 0; i < arr.length; i++) {
    let largestNumber = arr[i][0];
    for (let j = 1; j < arr[i].length; j++) {
      if (arr[i][j] > largestNumber) {
        largestNumber = arr[i][j];
      }
    }
    results[i] = largestNumber;
  }

  return results;
}
{% endhighlight %}