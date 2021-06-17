---
layout: default
title: Use * to Import Everything from a File
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 25
---
# Use * to Import Everything from a File
## Summary
- `*` can be used to import all contents from a .js file.

## Final Code

{% highlight JavaScript %}
import * as stringFunctions from "./string_functions.js";

// Only change code above this line

stringFunctions.uppercaseString("hello");
stringFunctions.lowercaseString("WORLD!");
{% endhighlight %}