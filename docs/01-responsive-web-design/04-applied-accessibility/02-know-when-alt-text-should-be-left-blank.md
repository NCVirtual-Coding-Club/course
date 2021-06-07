---
layout: default
title: Know When Alt Text Should be Left Blank
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 2
---
# Know When Alt Text Should be Left Blank
## Summary
- `alt` text should not be used when an image already has a caption, or is only used for decoration.
- Although `alt` text may not be needed, always include the `alt` attribute.

## Final Code

{% highlight HTML %}
<h1>Deep Thoughts with Master Camper Cat</h1>
<article>
  <h2>Defeating your Foe: the Red Dot is Ours!</h2>
  <p>To Come...</p>
</article>

<img src="samuraiSwords.jpeg" alt="">

<article>
  <h2>Is Chuck Norris a Cat Person?</h2>
  <p>To Come...</p>
</article>
{% endhighlight %}