---
layout: default
title: Factorialize a Number
parent: Basic Algorithm Scripting
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 3
---
# Factorialize a Number

## Final Code

{% highlight JavaScript %}
function factorialize(num) {
  for (var product = 1; num > 0; num--) {
    product *= num;
  }
  return product;
}

factorialize(5);
{% endhighlight %}