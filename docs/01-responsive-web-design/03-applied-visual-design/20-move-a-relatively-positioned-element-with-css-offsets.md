---
layout: default
title: Move a Relatively Positioned Element with CSS Offsets
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 20
---
# Move a Relatively Positioned Element with CSS Offsets
## Summary
- The CSS offsets of `top` or `bottom`, and `left` or `right` tell the browser how far to offset an item relative to where it would sit in the normal flow of the document. 

## Final Code

{% highlight HTML %}
<head>
<style>
  h2 {
    position: relative;
    left: 15px;
    bottom: 10px;
  }
</style>
</head>
<body>
  <h1>On Being Well-Positioned</h1>
  <h2>Move me!</h2>
  <p>I still think the h2 is where it normally sits.</p>
</body>
{% endhighlight %}