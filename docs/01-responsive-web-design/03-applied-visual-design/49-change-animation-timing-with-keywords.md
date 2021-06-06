---
layout: default
title: Change Animation Timing with Keywords
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 49
---
# Change Animation Timing with Keywords
## Summary
- The `animation-timing-function` property controls how quickly an animated element changes over the duration of the animation.
    - The default value `ease`, starts slow, speeds up in the middle, and then slows down again in the end.
    - The value `ease-out` starts quick, then slows down.
    - The value `ease-in` starts slow, then speeds up.
    - The value `linear` is constant.

## Final Code

{% highlight HTML %}
<style>

  .balls {
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
    left:27%;
    animation-timing-function: linear;
  }
  #ball2 {
    left:56%;
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