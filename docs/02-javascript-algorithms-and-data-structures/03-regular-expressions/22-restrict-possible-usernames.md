---
layout: default
title: Restrict Possible Usernames
parent: Regular Expressions
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 22
---
# Restrict Possible Usernames
## Summary

## Final Code

{% highlight JavaScript %}
let username = "JackOfAllTrades";
let userCheck = /^[a-z][a-z]+\d*$|^[a-z]\d\d+$/i;
let result = userCheck.test(username);
console.log(result)
{% endhighlight %}