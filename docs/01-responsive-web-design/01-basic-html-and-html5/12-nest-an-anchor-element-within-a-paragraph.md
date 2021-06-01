---
layout: default
title: Nest an Anchor Element within a Paragraph
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 12
---
# Nest an Anchor Element within a Paragraph
## Summary
- You can nest links within other text elements.
- `target` is an anchor tag attribute that specifies where to open the link. 
- The value `_blank` specifies to open the link in a new tab.

## Final Code

{% highlight HTML %}
<h2>CatPhotoApp</h2>
<main>
  <p>View more <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a></p>
  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere...</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe...</p>
</main>
{% endhighlight %}