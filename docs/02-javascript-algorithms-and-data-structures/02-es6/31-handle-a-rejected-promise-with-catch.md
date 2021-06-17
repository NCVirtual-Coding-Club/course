---
layout: default
title: Handle a Rejected Promise with catch
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 31
---
# Handle a Rejected Promise with catch
## Summary
- The `catch` method can be used to complete an action after a promise is rejected.

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
makeServerRequest.catch(error => {
  console.log(error);
});
{% endhighlight %}