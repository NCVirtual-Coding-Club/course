---
layout: default
title: Improve Readability with High Contrast Text
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 16
---
# Improve Readability with High Contrast Text
## Summary
- It is important to remove/change any low contrast text.
- The Web Content Accessibility Guidelines (WCAG) recommend at least a 4.5 to 1 contrast ratio for normal text.

## Final Code

{% highlight HTML %}
<head>
  <style>
  body {
    color: #636363;
    background-color: #FFF;
  }
  </style>
</head>
<body>
  <header>
    <h1>Deep Thoughts with Master Camper Cat</h1>
  </header>
  <article>
    <h2>A Word on the Recent Catnip Doping Scandal</h2>
    <p>The influence that catnip has on feline behavior is well-documented, and its use as an herbal supplement in competitive ninja circles remains controversial. Once again, the debate to ban the substance is brought to the public's attention after the high-profile win of Kittytron, a long-time proponent and user of the green stuff, at the Claw of Fury tournament.</p>
    <p>As I've stated in the past, I firmly believe a true ninja's skills must come from within, with no external influences. My own catnip use shall continue as purely recreational.</p>
  </article>
</body>
{% endhighlight %}