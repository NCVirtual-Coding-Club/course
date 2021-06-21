---
layout: default
title: Catch Missing Open and Closing Parenthesis After a Function Call
parent: Debugging
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 8
---
# Catch Missing Open and Closing Parenthesis After a Function Call

## Final Code

{% highlight JavaScript %}
function getNine() {
  let x = 6;
  let y = 3;
  return x + y;
}

let result = getNine();
console.log(result);
{% endhighlight %}