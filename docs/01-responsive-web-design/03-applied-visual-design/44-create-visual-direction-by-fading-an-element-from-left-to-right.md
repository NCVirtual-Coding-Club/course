---
layout: default
title: Create Visual Direction by Fading an Element from Left to Right
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 44
---
# Create Visual Direction by Fading an Element from Left to Right
## Summary
- `opacity` can be changed using an animation.

## Final Code

{% highlight HTML %}
<style>

  #ball {
    width: 70px;
    height: 70px;
    margin: 50px auto;
    position: fixed;
    left: 20%;
    border-radius: 50%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    animation-name: fade;
    animation-duration: 3s;
  }

  @keyframes fade {
    50% {
      left: 60%;
      opacity: 0.1;
    }
  }

</style>

<div id="ball"></div>
{% endhighlight %}