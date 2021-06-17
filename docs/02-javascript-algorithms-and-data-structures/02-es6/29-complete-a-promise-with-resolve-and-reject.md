---
layout: default
title: Complete a Promise with resolve and reject
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 29
---
# Complete a Promise with resolve and reject
## Summary
- A promise has three states: `pending`, `fulfilled`, and `rejected`.
- Use conditions to determine the outcome of a promise.

## Final Code

{% highlight JavaScript %}
const makeServerRequest = new Promise((resolve, reject) => {
  // responseFromServer represents a response from a server
  let responseFromServer;
    
  if(responseFromServer) {
    resolve("We got the data")
  } else {  
    reject("Data not received")
  }
});
{% endhighlight %}