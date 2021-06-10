---
layout: default
title: Add Gaps Faster with grid-gap
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 7
---
# Add Gaps Faster with grid-gap
## Summary
- `grid-gap` can be used to set both the column and row gap in one command (row_gap_value column_gap_value).

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
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    /* Only change code below this line */
    grid-gap: 10px 20px;
    
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