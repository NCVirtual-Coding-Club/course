---
layout: default
title: Change an Element's Relative Position
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 19
---
# Change an Element's Relative Position
## Summary
- CSS treats each HTML element as its own box.
    - Eeferred to as the CSS Box Model.
    - Block-level items automatically start on a new line (headings, paragraphs, and divs) while inline items sit within surrounding content (images or spans).
- The default layout of elements in this way is called the normal flow of a document.
    - Can be overridden.

## Final Code

{% highlight HTML %}
<style>
  h2 {
    position: relative;
    top: 15px
  }
</style>
<body>
  <h1>On Being Well-Positioned</h1>
  <h2>Move me!</h2>
  <p>I still think the h2 is where it normally sits.</p>
</body>
{% endhighlight %}