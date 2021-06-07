---
layout: default
title: Improve Form Field Accessibility with the label Element
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 11
---
# Improve Form Field Accessibility with the label Element
## Summary
- The `label` tag wraps text for a specific form control item.
- The `for` attribute on a label tag explicitly associates that label with the form control and is used by screen readers.
- The value of the `for` attribute must be the same as the value of the `id` attribute of the form control.

## Final Code

{% highlight HTML %}
<body>
  <header>
    <h1>Deep Thoughts with Master Camper Cat</h1>
  </header>
  <section>
    <form>
      <p>Sign up to receive Camper Cat's blog posts by email here!</p>


      <label for="email">Email:</label>
      <input type="text" id="email" name="email">


      <input type="submit" name="submit" value="Submit">
    </form>
  </section>
  <article>
    <h2>The Garfield Files: Lasagna as Training Fuel?</h2>
    <p>The internet is littered with varying opinions...</p>
  </article>
  <img src="samuraiSwords.jpeg" alt="">
  <article>
    <h2>Defeating your Foe: the Red Dot is Ours!</h2>
    <p>Felines the world over have been waging war...</p>
  </article>
  <img src="samuraiSwords.jpeg" alt="">
  <article>
    <h2>Is Chuck Norris a Cat Person?</h2>
    <p>Chuck Norris is widely regarded as...</p>
  </article>
  <footer>&copy; 2018 Camper Cat</footer>
</body>
{% endhighlight %}