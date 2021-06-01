---
layout: default
title: Create an Ordered List
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 16
---
# Create an Ordered List
## Summary
- Ordered (numbered) lists can be created by using `<ol>` and `<li>` elements.
- Ordered lists start with an opening `<ol>` element, followed by any number of `<li>` elements. Finally, ordered lists are closed with the `</ol>` tag.

## Final Code

{% highlight HTML %}
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  <a href="#"><img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange..."></a>
  <p>Things cats love:</p>

  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>

  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
</main>
{% endhighlight %}