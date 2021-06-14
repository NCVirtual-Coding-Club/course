---
layout: default
title: Practice comparing different values
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 60
---
# Practice comparing different values

## Final Code

{% highlight JavaScript %}
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

compareEquality(10, "10");
{% endhighlight %}