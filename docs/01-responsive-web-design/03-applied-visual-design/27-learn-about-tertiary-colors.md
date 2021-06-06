---
layout: default
title: Learn about Tertiary Colors
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 27
---
# Learn about Tertiary Colors
## Summary
- Computer monitors and device screens create different colors by combining amounts of red, green, and blue light.
    - Known as the RGB additive color model in modern color theory.
- Mixing two primary colors creates the secondary colors cyan (G + B), magenta (R + B) and yellow (R + G).
    - These secondary colors happen to be the complement to the primary color not used in their creation, and are opposite to that primary color on the color wheel.
- Tertiary colors are the result of combining a primary color with one of its secondary color neighbors.
- One way to select colors that result in a harmonious combination is the split-complemenary color scheme.
    - starts with a base color, then pairs it with the two colors that are adjacent to its complement.

## Final Code

{% highlight HTML %}
<style>
  body {
    background-color: #FFFFFF;
  }

  .orange {
    background-color: #FF7F00;
  }

  .cyan {
    background-color: #00FFFF;
  }

  .raspberry {
    background-color: #FF007F;
  }

  div {
    height: 100px;
    width: 100px;
    margin-bottom: 5px;
  }
</style>

<div class="orange"></div>
<div class="cyan"></div>
<div class="raspberry"></div>
{% endhighlight %}