---
layout: default
title: Avoid Colorblindness Issues by Using Sufficient Contrast
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 17
---
# Avoid Colorblindness Issues by Using Sufficient Contrast
## Summary
- Sufficient Contrast can also help users with Colorblindness.

## Final Code

{% highlight HTML %}
<head>
  <style>
  body {
    color: hsl(0, 55%, 15%);
    background-color: hsl(120, 25%, 55%);
  }
  </style>
</head>
<body>
  <header>
    <h1>Deep Thoughts with Master Camper Cat</h1>
  </header>
  <article>
    <h2>A Word on the Recent Catnip Doping Scandal</h2>
    <p>The influence that catnip has on feline...</p>
    <p>As I've stated in the past, I firmly believe...</p>
  </article>
</body>
{% endhighlight %}