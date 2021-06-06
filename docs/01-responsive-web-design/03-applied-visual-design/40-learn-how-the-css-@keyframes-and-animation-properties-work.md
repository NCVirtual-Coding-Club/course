---
layout: default
title: Learn How the CSS @keyframes and animation Properties Work
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 40
---
# Learn How the CSS @keyframes and animation Properties Work
## Summary
- The animation properties and the `@keyframes` rule are used to animate an element.
- The animation properties control how the animation should behave and the `@keyframes` rule controls what happens during that animation.
    - `animation-name` sets the name of the animation.
    - `animation-duration` sets the length of time for the animation.
- `frames` range from 0% to 100%.

## Final Code

{% highlight HTML %}
<style>
  div {
    height: 40px;
    width: 70%;
    background: black;
    margin: 50px auto;
    border-radius: 5px;
  }

  #rect {
    animation-name: rainbow;
    animation-duration: 4s;
  }
  @keyframes rainbow {
    0% {
      background-color: blue;
    }
    50% {
      background-color: green;
    }
    100% {
      background-color: yellow;
    }
  }



</style>
<div id="rect"></div>
{% endhighlight %}