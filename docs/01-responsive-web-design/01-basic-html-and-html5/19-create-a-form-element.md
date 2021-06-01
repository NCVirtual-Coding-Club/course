---
layout: default
title: Create a Form Element
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 19
---
# Create a Form Element
## Summary
- You can build web forms to submit data to a server.
  - This can be done using the `action` attribute on a `form` element.

## Final Code

{% highlight HTML %}
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://www.bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

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

  <form action="https://www.freecatphotoapp.com/submit-cat-photo"><input type="text" placeholder="cat photo URL"></form>
</main>
{% endhighlight %}