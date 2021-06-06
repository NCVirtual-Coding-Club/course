---
layout: default
title: Modify Fill Mode of an Animation
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 42
---
# Modify Fill Mode of an Animation
## Summary
- The `animation-fill-mode` specifies the style applied to an element when the animation has finished.

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
    /* Only change code below this line */
    animation-fill-mode: forwards;
    /* Only change code above this line */
  }
  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }
</style>
<button>Register</button>
{% endhighlight %}