---
layout: default
title: Make an Image Responsive
parent: Responsive Web Design Principles
grand_parent: Responsive Web Design
has_children: false
nav_order: 2
---
# Make an Image Responsive
## Summary
- Images can be made responsive by using the `max-width` and `height` properties.

## Final Code

{% highlight HTML %}
<style>
.responsive-img {
  max-width: 100%;
  height: auto;
}

img {
  width: 600px;
}
</style>

<img class="responsive-img" src="https://s3.amazonaws.com/freecodecamp/FCCStickerPack.jpg" alt="freeCodeCamp stickers set">
<img src="https://s3.amazonaws.com/freecodecamp/FCCStickerPack.jpg" alt="freeCodeCamp stickers set">
{% endhighlight %}