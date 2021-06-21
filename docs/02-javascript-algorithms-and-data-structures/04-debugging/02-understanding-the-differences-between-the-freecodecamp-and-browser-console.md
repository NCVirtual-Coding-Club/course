---
layout: default
title: Understanding the Differences between the freeCodeCamp and Browser Console
parent: Debugging
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 2
---
# Understanding the Differences between the freeCodeCamp and Browser Console
## Summary
- `console.clear()` can be used to clear the console after each iteration.

## Final Code

{% highlight JavaScript %}
// Open your browser console.
let output = "Get this to log once in the freeCodeCamp console and twice in the browser console";
// Use console.log() to print the output variable.
console.clear()
console.log(output)
// Run the tests to see the difference between the two consoles.

// Now, add console.clear() before your console.log() to clear the browser console, and pass the tests.
{% endhighlight %}