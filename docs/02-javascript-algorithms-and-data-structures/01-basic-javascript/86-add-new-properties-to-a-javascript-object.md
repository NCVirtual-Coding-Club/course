---
layout: default
title: Add New Properties to a JavaScript Object
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 86
---
# Add New Properties to a JavaScript Object
## Summary
- New object properties can be added to existing objects.

## Final Code

{% highlight JavaScript %}
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

myDog["bark"] = "woof"
{% endhighlight %}

or

{% highlight JavaScript %}
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

myDog.bark = "woof"
{% endhighlight %}