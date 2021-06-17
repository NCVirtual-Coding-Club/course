---
layout: default
title: Compare Scopes of the var and let Keywords
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 2
---
# Compare Scopes of the var and let Keywords
## Summary
- When using the `let` keyword, the scope is limited to that block, statement, or expression.

## Final Code

{% highlight JavaScript %}
function checkScope() {
  let i = 'function scope';
  if (true) {
    let i = 'block scope';
    console.log('Block scope i is: ', i);
  }
  console.log('Function scope i is: ', i);
  return i;
}
{% endhighlight %}