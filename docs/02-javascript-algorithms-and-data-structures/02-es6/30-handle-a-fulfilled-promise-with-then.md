---
layout: default
title: Handle a Fulfilled Promise with then
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 30
---
# Handle a Fulfilled Promise with then
## Summary
- The `then` method can be used to complete an action after a promise is fulfilled.

## Final Code

{% highlight JavaScript %}
const makeServerRequest = new Promise((resolve, reject) => {
  // responseFromServer is set to false to represent an unsuccessful response from a server
  let responseFromServer = false;
    
  if(responseFromServer) {
    resolve("We got the data");
  } else {  
    reject("Data not received");
  }
});

makeServerRequest.then(result => {
  console.log(result);
});
{% endhighlight %}