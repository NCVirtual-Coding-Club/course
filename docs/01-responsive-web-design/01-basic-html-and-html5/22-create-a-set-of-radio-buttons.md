---
layout: default
title: Create a Set of Radio Buttons
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 22
---
# Create a Set of Radio Buttons
## Summary
- `Radio` buttons are buttons that only allowed one button to be selected at any given time. 
- `Radio` buttons are a type of `input`.
- Each of your `radio` buttons can be nested within its own `label` element. By wrapping an `input` element inside of a `label` element it will automatically associate the `radio` button `input` with the `label` element surrounding it.
- All related `radio` buttons should have the same `name` attribute to create a `radio` button group.
- Should include a `for` attribute on the `label` element with a value that matches the value of the `id` attribute of the `input` element.

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

  <form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>

</main>
{% endhighlight %}