---
layout: default
title: Use Headings to Show Hierarchical Relationships of Content
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 3
---
# Use Headings to Show Hierarchical Relationships of Content
## Summary
- Headings (`h1`-`h6`) should have a semantic meaning.
    - Semantic meaning means that the tag you use around content indicates the type of information it contains.
    - Should not be used to simply increase the font size.
        - Use CSS.
- Each page should include only one `h1` element.

## Final Code

{% highlight HTML %}
<h1>How to Become a Ninja</h1>
<main>
  <h2>Learn the Art of Moving Stealthily</h2>
  <h3>How to Hide in Plain Sight</h3>
  <h3>How to Climb a Wall</h3>

  <h2>Learn the Art of Battle</h2>
  <h3>How to Strengthen your Body</h3>
  <h3>How to Fight like a Ninja</h3>

  <h2>Learn the Art of Living with Honor</h2>
  <h3>How to Breathe Properly</h3>
  <h3>How to Simplify your Life</h3>
</main>
{% endhighlight %}