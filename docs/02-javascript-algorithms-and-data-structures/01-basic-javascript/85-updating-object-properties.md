---
layout: default
title: Updating Object Properties
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 85
---
# Updating Object Properties
## Summary
- JavaScript object properties can eb updated at any time.

## Final Code

{% highlight JavaScript %}
// Setup
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line
myDog["name"] = "Happy Coder";
{% endhighlight %}

or

{% highlight JavaScript %}
// Setup
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line
myDog.name = "Happy Coder";
{% endhighlight %}