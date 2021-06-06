---
layout: default
title: Learn about Complementary Colors
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 26
---
# Learn about Complementary Colors
## Summary
- On a website, color can draw attention to content, evoke emotions, or create visual harmony.
- Using different combinations of colors can change the look of a website, and a lot of thought can go into picking a color palette that works with your content.
- The color wheel is a useful tool to visualize how colors relate to each other.
    - A circle where similar hues are neighbors and different hues are farther apart.
- There are many color picking tools available online that have an option to find the complement of a color.

## Final Code

{% highlight HTML %}
<style>
  body {
    background-color: #FFFFFF;
  }
  .blue {
    background-color: blue;
  }
  .yellow {
    background-color: yellow;
  }
  div {
    display: inline-block;
    height: 100px;
    width: 100px;
  }
</style>
<div class="blue"></div>
<div class="yellow"></div>
{% endhighlight %}