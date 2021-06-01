---
layout: default
title: Add Images to Your Website
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 9
---
# Add Images to Your Website
## Summary
- Images can be added to a website using the `img` element.
- The `src` attribute is used with the `img` element to point to a specific image's URL.
- `img` elements are self-closing
  - This means you do not need to include a closing tag (`</img>`)
- `img` elements must include an `alt` attribute.
  - The text inside an `alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.
  - If the image is purely decorative, using an empty `alt` attribute is a best practice.

## Final Code

{% highlight HTML %}
<h2>CatPhotoApp</h2>
<main>
  <img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere...</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe...</p>
</main>
{% endhighlight %}