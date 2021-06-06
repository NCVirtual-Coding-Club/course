---
layout: default
title: Adjust the Hue of a Color
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 29
---
# Adjust the Hue of a Color
## Summary
- Colors have several characteristics including hue, saturation, and lightness.
- CSS3 introduced the `hsl()` property as an alternative way to pick a color by directly stating these characteristics.
- Hue (`h`) is the color.
    - Uses the color wheel.
    - Value between `0` and `360`.
- Saturation (`s`) is the amount of gray in a color.
- Lightness (`l`) is the amount of white or black in a color.

## Final Code

{% highlight HTML %}
<style>
  body {
    background-color: #FFFFFF;
  }

  .green {
    background-color: hsl(120, 100%, 50%);
  }

  .cyan {
    background-color: hsl(180, 100%, 50%);
  }

  .blue {
    background-color: hsl(240, 100%, 50%);
  }

  div {
    display: inline-block;
    height: 100px;
    width: 100px;
  }
</style>

<div class="green"></div>
<div class="cyan"></div>
<div class="blue"></div>
{% endhighlight %}