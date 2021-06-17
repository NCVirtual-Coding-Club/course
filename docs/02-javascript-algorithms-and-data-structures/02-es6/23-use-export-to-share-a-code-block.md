---
layout: default
title: Use export to Share a Code Block
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 23
---
# Use export to Share a Code Block
## Summary
- To share a function between JavaScript files, `export` the function.

## Final Code

{% highlight JavaScript %}
const uppercaseString = (string) => {
  return string.toUpperCase();
}

const lowercaseString = (string) => {
  return string.toLowerCase()
}

export {lowercaseString, uppercaseString};
{% endhighlight %}