---
layout: default
title: Using Objects for Lookups
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 88
---
# Using Objects for Lookups
## Summary
- An object can be used rather than an `if`/`else` or `switch` statement.

## Final Code

{% highlight JavaScript %}
// Setup
function phoneticLookup(val) {
  var result = "";

  var lookup = {
    alpha: "Adams",
    bravo: "Boston",
    charlie: "Chicago",
    delta: "Denver",
    echo: "Easy",
    foxtrot: "Frank"
  };

  result = lookup[val]

  // Only change code above this line
  return result;
}

phoneticLookup("charlie");
{% endhighlight %}