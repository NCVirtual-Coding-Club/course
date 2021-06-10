---
layout: default
title: Add Columns with grid-template-columns
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 2
---
# Add Columns with grid-template-columns
## Summary
- To add columns to a grid, use the `grid-template-columns` property on a grid container.
- The number of parameters given to the `grid-template-columns` property indicates the number of columns in the grid, and the value of each parameter indicates the width of each column.

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
    /* Only change code below this line */
    grid-template-columns: 100px 100px 100px;
    
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