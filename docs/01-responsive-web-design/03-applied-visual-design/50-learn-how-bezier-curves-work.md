---
layout: default
title: Learn How Bezier Curves Work
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 50
---
# Learn How Bezier Curves Work
## Summary
- In CSS animations, `Bezier curves` are used with the cubic-bezier function.
- The shape of the curve represents how the animation plays out.
- The cubic-bezier function consists of four main points that sit on this 1 by 1 grid: `p0`, `p1`, `p2`, and `p3`. 
- More information can be found (here)[https://en.wikipedia.org/wiki/B%C3%A9zier_curve]

## Final Code

{% highlight HTML %}
<style>

  .balls{
    border-radius: 50%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    position: fixed;
    width: 50px;
    height: 50px;
    margin-top: 50px;
    animation-name: bounce;
    animation-duration: 2s;
    animation-iteration-count: infinite;
  }
  #ball1 {
    left: 27%;
    animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
  }
  #ball2 {
    left: 56%;
    animation-timing-function: ease-out;
  }

  @keyframes bounce {
    0% {
      top: 0px;
    }
    100% {
      top: 249px;
    }
  }

</style>

<div class="balls" id="ball1"></div>
<div class="balls" id="ball2"></div>
{% endhighlight %}