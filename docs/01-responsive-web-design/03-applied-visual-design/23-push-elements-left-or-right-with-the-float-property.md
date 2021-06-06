---
layout: default
title: Push Elements Left or Right with the float Property
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 23
---
# Push Elements Left or Right with the float Property
## Summary
- Floating elements are pushed to either the `left` or `right` of their containing parent element.
- Floating elements are removed from the normal flow of a document.

## Final Code

{% highlight HTML %}
<head>
  <style>
    #left {
      float: left;
      width: 50%;
    }
    #right {
      float: right;
      width: 40%;
    }
    aside, section {
      padding: 2px;
      background-color: #ccc;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome!</h1>
  </header>
  <section id="left">
    <h2>Content</h2>
    <p>Good stuff</p>
  </section>
  <aside id="right">
    <h2>Sidebar</h2>
    <p>Links</p>
  </aside>
</body>
{% endhighlight %}