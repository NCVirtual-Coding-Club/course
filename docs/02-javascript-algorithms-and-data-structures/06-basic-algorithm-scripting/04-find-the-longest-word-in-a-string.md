---
layout: default
title: Find the Longest Word in a String
parent: Basic Algorithm Scripting
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 4
---
# Find the Longest Word in a String

## Final Code

{% highlight JavaScript %}
function findLongestWordLength(str) {
  let words = str.split(' ');
  let maxLength = 0;

  for (let i = 0; i < words.length; i++) {
    if (words[i].length > maxLength) {
      maxLength = words[i].length;
    }
  }

  return maxLength;
}
{% endhighlight %}