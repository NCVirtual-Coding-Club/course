---
layout: default
title: Use HTML5 to Require a Field
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 21
---
# Use HTML5 to Require a Field
## Summary
- You can require fields to be filled out before a form is submitted.
- If you wanted to make a text `input` field required, you can just add the attribute `required` within your `input` element.

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
  
  <form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
{% endhighlight %}