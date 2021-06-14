---
layout: default
title: Accessing Object Properties with Variables
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 84
---
# Accessing Object Properties with Variables
## Summary
- Bracket notation can be used to access a property which is stored as a value of a variable.

## Final Code

{% highlight JavaScript %}
// Setup
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line

var playerNumber = 16;       // Change this line
var player = testObj[playerNumber];   // Change this line
{% endhighlight %}