---
layout: default
title: Reuse JavaScript Code Using import
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 24
---
# Reuse JavaScript Code Using import
## Summary
- `import` a function using `import { add } from 'url;`.

## Final Code

{% highlight JavaScript %}
import {uppercaseString, lowercaseString} from './string_functions.js'
// Only change code above this line

uppercaseString("hello");
lowercaseString("WORLD!");
{% endhighlight %}