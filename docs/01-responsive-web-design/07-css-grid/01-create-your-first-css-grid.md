---
layout: default
title: Create Your First CSS Grid
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 1
---
# Create Your First CSS Grid
## Summary
- Any HTML element can be made into a grid container by setting its `display` property to `grid`.
- In CSS Grid, the parent element is referred to as the ___container___ and its children are called ___items___.

## Final Code

{% highlight HTML %}
<style>
  .d1{background:LightSkyBlue;}
  .d2{background:LightSalmon;}
  .d3{background:PaleTurquoise;}
  .d4{background:LightPink;}
  .d5{background:PaleGreen;}

  .container {
    font-size: 40px;
    width: 100%;
    background: LightGray;
    /* Only change code below this line */
    display: grid;
    
    /* Only change code above this line */
  }
</style>

<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
{% endhighlight %}