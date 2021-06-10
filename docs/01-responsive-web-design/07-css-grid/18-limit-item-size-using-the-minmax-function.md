---
layout: default
title: Limit Item Size Using the minmax Function
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 18
---
# Limit Item Size Using the minmax Function
## Summary
- `minmax` can be used to limit the size of items when the container size changes.

## Final Code

{% highlight HTML %}
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* Only change code below this line */

    grid-template-columns: repeat(3, minmax(90px, 1fr));

    /* Only change code above this line */
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