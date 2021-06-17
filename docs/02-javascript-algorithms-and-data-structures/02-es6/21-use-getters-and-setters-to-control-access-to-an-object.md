---
layout: default
title: Use getters and setters to Control Access to an Object
parent: ES6
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 21
---
# Use getters and setters to Control Access to an Object
## Summary
- A getter function is used to return the value of an object's private variable.
- A setter function is used to modify the value of an object's private variable.

## Final Code

{% highlight JavaScript %}
// Only change code below this line
class Thermostat {
  constructor(fahrenheit) {
    this.fahrenheit = fahrenheit;
  }
  
  get temperature() {
    return (5 / 9) * (this.fahrenheit - 32);
  }
  
  set temperature(celsius) {
    this.fahrenheit = (celsius * 9.0) / 5 + 32;
  }
}

// Only change code above this line

const thermos = new Thermostat(76); // Setting in Fahrenheit scale
let temp = thermos.temperature; // 24.44 in Celsius
thermos.temperature = 26;
temp = thermos.temperature; // 26 in Celsius
{% endhighlight %}