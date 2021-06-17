---
layout: default
title: Explore Differences Between the var and let Keywords
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 1
---
# Explore Differences Between the var and let Keywords
## Summary
- The `let` keyword ensures that a variable is not accidentally overwriten.

## Final Code

{% highlight JavaScript %}
let catName;
let quote;
function catTalk() {
  "use strict";

  catName = "Oliver";
  quote = catName + " says Meow!";

}
catTalk();
{% endhighlight %}