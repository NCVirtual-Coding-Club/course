---
layout: default
title: Reverse a String
parent: Basic Algorithm Scripting
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 2
---
# Reverse a String

## Final Code

{% highlight JavaScript %}
function reverseString(str) {
  for (var reversedStr = "", i = str.length - 1; i >= 0; i--) {
    reversedStr += str[i];
  }
  return reversedStr;
}

reverseString("hello");
{% endhighlight %}