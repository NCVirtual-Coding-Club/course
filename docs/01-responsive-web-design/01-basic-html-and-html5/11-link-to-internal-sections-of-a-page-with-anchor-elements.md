---
layout: default
title: Link to Internal Sections of a Page with Anchor Elements
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 11
---
# Link to Internal Sections of a Page with Anchor Elements
## Summary
- `a` elements can be used to create internal links to different sections within a webpage.
- To create an internal link, you assign a link's `href` attribute to a hash symbol `#` plus the value of the `id` attribute for the element that you want to internally link to, usually further down the page. You then need to add the same `id` attribute to the element you are linking to.
- The `id` is an attribute that uniquely describes an element.

## Final Code

{% highlight HTML %}
<h2>CatPhotoApp</h2>
<main>
  <a href="#footer">Jump to Bottom</a>
  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere...</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe...</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box...</p>
  <p>Intently stare at the same spot poop in the plant pot...</p>
</main>
<footer id="footer">Copyright Cat Photo App</footer>
{% endhighlight %}