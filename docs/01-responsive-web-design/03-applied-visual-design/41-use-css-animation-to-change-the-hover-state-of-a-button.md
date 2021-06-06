---
layout: default
title: Use CSS Animation to Change the Hover State of a Button
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 41
---
# Use CSS Animation to Change the Hover State of a Button
## Summary
- The CSS `@keyframes` rule can be used to change the color of a button in its hover state.

## Final Code

{% highlight HTML %}
<style>
  button {
    border-radius: 5px;
    color: white;
    background-color: #0F5897;
    padding: 5px 10px 8px 10px;
  }

  button:hover {
    animation-name: background-color;
    animation-duration: 500ms;
  }
  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }

</style>

<button>Register</button>
{% endhighlight %}