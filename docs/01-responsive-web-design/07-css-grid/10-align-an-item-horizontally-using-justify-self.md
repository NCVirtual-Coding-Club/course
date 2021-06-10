---
layout: default
title: Align an Item Horizontally using justify-self
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 10
---
# Align an Item Horizontally using justify-self
## Summary
- The content of each item is located in a box referred to as a ___cell___.
- The `justify-self` property is used to align a content's position within its cell horizontally.
    - `stretch`: Content will fill the width of the cell.
    - `start`: aligns the content at the left of the cell.
    - `center`: aligns the content in the center of the cell.
    - `end`: aligns the content at the right of the cell.

## Final Code

{% highlight HTML %}
<style>
  .item1{background: LightSkyBlue;}

  .item2 {
    background: LightSalmon;
    /* Only change code below this line */
    justify-self: center;
    
    /* Only change code above this line */
  }

  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
{% endhighlight %}