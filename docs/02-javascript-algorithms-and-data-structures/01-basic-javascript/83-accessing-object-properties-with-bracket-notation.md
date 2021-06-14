---
layout: default
title: Accessing Object Properties with Bracket Notation
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 83
---
# Accessing Object Properties with Bracket Notation
## Summary
- Bracket Notation is used when a property name has spaces.

## Final Code

{% highlight JavaScript %}
// Setup
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};

// Only change code below this line

var entreeValue = testObj["an entree"];   // Change this line
var drinkValue = testObj["the drink"];    // Change this line
{% endhighlight %}