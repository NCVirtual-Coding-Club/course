---
layout: default
title: Combine Arrays with the Spread Operator
parent: Basic Data Structures
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 9
---
# Combine Arrays with the Spread Operator
## Summary
- The spread operator can be used to combine arrays.

## Final Code

{% highlight JavaScript %}
function spreadOut() {
  let fragment = ['to', 'code'];
  let sentence = ["learning", ...fragment, "is", "fun"]; // Change this line
  return sentence;
}

console.log(spreadOut());
{% endhighlight %}