---
layout: default
title: Align Elements Using the align-items Property
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 9
---
# Align Elements Using the align-items Property
## Summary
<img src="https://www.w3.org/TR/css-flexbox-1/images/flex-direction-terms.svg">
- CSS offers the `align-items` property to align flex items along the cross axis.
    - `flex-start`: aligns items to the start of the flex container. For rows, this aligns items to the top of the container. For columns, this aligns items to the left of the container.
    - `flex-end`: aligns items to the end of the flex container. For rows, this aligns items to the bottom of the container. For columns, this aligns items to the right of the container.
    - `center`: align items to the center. For rows, this vertically aligns items (equal space above and below the items). For columns, this horizontally aligns them (equal space to the left and right of the items).
    - `stretch`: stretch the items to fill the flex container. For example, rows items are stretched to fill the flex container top-to-bottom. This is the default value if no align-items value is specified.
    baseline: align items to their baselines. Baseline is a text concept, think of it as the line that the letters sit on.


## Final Code

{% highlight HTML %}
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    align-items: center;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 200px;
    font-size: 24px;
  }

  #box-2 {
    background-color: orangered;
    width: 200px;
    font-size: 18px;
  }
</style>

<div id="box-container">
  <div id="box-1"><p>Hello</p></div>
  <div id="box-2"><p>Goodbye</p></div>
</div>
{% endhighlight %}