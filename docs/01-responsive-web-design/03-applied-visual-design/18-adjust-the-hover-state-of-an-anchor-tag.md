---
layout: default
title: Adjust the Hover State of an Anchor Tag
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 18
---
# Adjust the Hover State of an Anchor Tag
## Summary
- A pseudo-class is a keyword that can be added to selectors, in order to select a specific state of the element.

## Final Code

{% highlight HTML %}
<style>
  a {
    color: #000;
  }
  a:hover {
    color: blue;
  }


</style>
<a href="https://freecatphotoapp.com/" target="_blank">CatPhotoApp</a>
{% endhighlight %}