---
layout: default
title: Use grid-area Without Creating an Areas Template
parent: CSS Grid
grand_parent: Responsive Web Design
has_children: false
nav_order: 16
---
# Use grid-area Without Creating an Areas Template
## Summary
- Area templates can be created "on the fly" using the `grid-area` property.

{% highlight HTML %}
item1 { grid-area: 1/1/2/4; }
{% endhighlight %}

{% highlight HTML %}
item1 { grid-area: 1/1/2/4; }
{% endhighlight %}

## Final Code

{% highlight HTML %}
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}

  .item5 {
    background: PaleGreen;
    /* Only change code below this line */
    grid-area: 3/1/4/4;

    /* Only change code above this line */
  }

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