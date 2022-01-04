---
layout: default
title: Convert Celsius to Fahrenheit
parent: Basic Algorithm Scripting
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 1
---
# Convert Celsius to Fahrenheit

## Final Code

{% highlight JavaScript %}
function convertToF(celsius) {
  let fahrenheit = celsius*9/5+32;
  return fahrenheit;
}

convertToF(30);
{% endhighlight %}