---
layout: default
title: Use CSS Grid units to Change the Size of Columns and Rows
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 4
---
# Use CSS Grid units to Change the Size of Columns and Rows
## Summary
- Absolute and relative units can be used to define the size of rows and columns.
    - `fr`: sets the column or row to a fraction of the available space,
    - `auto`: sets the column or row to the width or height of its content automatically,
    - `%`: adjusts the column or row to the percent width of its container.

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

    grid-template-columns: 1fr 100px 2fr;

    /* Only change code above this line */
    grid-template-rows: 50px 50px;
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