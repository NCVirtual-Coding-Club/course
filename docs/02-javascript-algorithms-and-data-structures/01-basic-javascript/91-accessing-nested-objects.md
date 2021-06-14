---
layout: default
title: Accessing Nested Objects
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 91
---
# Accessing Nested Objects
## Summary
- sub-properties of objects can be accessed by chaining together dot or bracket notation.

## Final Code

{% highlight JavaScript %}
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

var gloveBoxContents = myStorage.car.inside["glove box"];
{% endhighlight %}