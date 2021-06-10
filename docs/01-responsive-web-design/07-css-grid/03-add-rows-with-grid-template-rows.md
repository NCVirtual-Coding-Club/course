---
layout: default
title: Add Rows with grid-template-rows
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 3
---
# Add Rows with grid-template-rows
## Summary
- To add rows to a grid, use the `grid-template-rows` property on a grid container.

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
    display: grid;
    grid-template-columns: 100px 100px 100px;
    /* Only change code below this line */
    grid-template-rows: 50px 50px;
    
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