---
layout: default
title: Delete Properties from a JavaScript Object
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 87
---
# Delete Properties from a JavaScript Object
## Summary
- Properties can be deleted using `delete`.

## Final Code

{% highlight JavaScript %}
// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

delete myDog.tails;
// Only change code below this line
{% endhighlight %}