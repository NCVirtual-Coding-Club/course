---
layout: default
title: Confirm the Ending
parent: Basic Algorithm Scripting
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 6
---
# Confirm the Ending

## Final Code

{% highlight JavaScript %}
function confirmEnding(str, target) {
  // "Never give up and good luck will find you."
  // -- Falcor

  return str.slice(str.length - target.length) === target;
}

confirmEnding("He has to give me a new name", "name");
{% endhighlight %}