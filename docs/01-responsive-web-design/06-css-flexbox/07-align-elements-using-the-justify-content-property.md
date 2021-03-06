---
layout: default
title: Align Elements Using the justify-content Property
parent: CSS Flexbox
grand_parent: Responsive Web Design
has_children: false
nav_order: 7
---
# Align Elements Using the justify-content Property
## Summary
- The `justify-content` property allows custom alignments and spacing in CSS along the main axis.
<img src="https://www.w3.org/TR/css-flexbox-1/images/flex-direction-terms.svg">
    - `justify-content`: Aligned all flex items to the nter of the flex container.
    - `flex-start`: aligns items to the start of the flex container. For a row, this pushes the items to the left of the container. For a column, this pushes the items to the top of the container. This is the default alignment if no justify-content is specified.
    - `flex-end`: aligns items to the end of the flex container. For a row, this pushes the items to the right of the container. For a column, this pushes the items to the bottom of the container.
    - `space-between`: aligns items to the center of the main axis, with extra space placed between the items. The first and last items are pushed to the very edge of the flex container. For example, in a row the first item is against the left side of the container, the last item is against the right side of the container, then the remaining space is distributed evenly among the other items.
    - `space-around`: similar to space-between but the first and last items are not locked to the edges of the container, the space is distributed around all the items with a half space on either end of the flex container.
    - `space-evenly`: Distributes space evenly between the flex items with a full space at either end of the flex container

## Final Code

{% highlight HTML %}
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    justify-content: center;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 25%;
    height: 100%;
  }

  #box-2 {
    background-color: orangered;
    width: 25%;
    height: 100%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
{% endhighlight %}