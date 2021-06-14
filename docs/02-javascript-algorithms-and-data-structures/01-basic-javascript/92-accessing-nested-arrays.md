---
layout: default
title: Accessing Nested Arrays
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 92
---
# Accessing Nested Arrays
## Summary
- Array bracket notation can be chained to access nested arrays.

## Final Code

{% highlight JavaScript %}
var myPlants = [
  {
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }
];

var secondTree = myPlants[1].list[1];
{% endhighlight %}