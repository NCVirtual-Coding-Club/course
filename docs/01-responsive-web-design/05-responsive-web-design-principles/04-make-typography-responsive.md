---
layout: default
title: Make Typography Responsive
parent: Responsive Web Design Principles
grand_parent: Responsive Web Design
has_children: false
nav_order: 4
---
# Make Typography Responsive
## Summary
- Instead of using `em` or `px` to size text viewport units can be used for responsive typography.
- The four different viewport units are:
    - `vw` (viewport width): `10vw` would be 10% of the viewport's width.
    - `vh` (viewport height): `3vh` would be 3% of the viewport's height.
    - `vmin` (viewport minimum): `70vmin` would be 70% of the viewport's smaller dimension (height or width).
    - `vmax` (viewport maximum): `100vmax` would be 100% of the viewport's bigger dimension (height or width).

## Final Code

{% highlight HTML %}
<style>
  h2 {
    width: 80vw;
  }
  p {
    width: 75vmin;
  }
</style>

<h2>Importantus Ipsum</h2>
<p>Lorem ipsum dolor sit amet...</p>
{% endhighlight %}