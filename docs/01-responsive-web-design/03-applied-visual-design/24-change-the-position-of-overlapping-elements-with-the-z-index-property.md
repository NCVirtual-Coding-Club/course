---
layout: default
title: Change the Position of Overlapping Elements with the z-index Property
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 24
---
# Change the Position of Overlapping Elements with the z-index Property
## Summary
- When elements are positioned to overlap (i.e. using `position:` `absolute`, `relative`, `fixed`, `sticky`), the element coming later in the HTML markup will, by default, appear on the top of the other elements.
- The `z-index` property can specify the order of how elements are stacked on top of one another.
    - Must be an integer.
    - Higher values for the `z-index` property of an element move it higher in the stack than those with lower values.

## Final Code

{% highlight HTML %}
<style>
  div {
    width: 60%;
    height: 200px;
    margin-top: 20px;
  }

  .first {
    background-color: red;
    position: absolute;
    z-index: 2;
  }
  .second {
    background-color: blue;
    position: absolute;
    left: 40px;
    top: 50px;
    z-index: 1;
  }
</style>

<div class="first"></div>
<div class="second"></div>
{% endhighlight %}