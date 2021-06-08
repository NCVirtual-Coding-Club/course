---
layout: default
title: Use a Retina Image for Higher Resolution Displays
parent: Responsive Web Design Principles
grand_parent: Responsive Web Design
has_children: false
nav_order: 3
---
# Use a Retina Image for Higher Resolution Displays
## Summary
- The simplest way to make images properly appear on High-Resolution Displays is to define the `width` and `height` values as only half of what the original file is.

## Final Code

{% highlight HTML %}
<style>
  img {
    width: 100px;
    height: 100px;
  }
</style>

<img src="https://s3..." alt="freeCodeCamp sticker that says 'Because CamperBot Cares'">
{% endhighlight %}