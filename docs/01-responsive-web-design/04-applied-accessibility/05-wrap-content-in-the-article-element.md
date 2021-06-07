---
layout: default
title: Wrap Content in the article Element
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 5
---
# Wrap Content in the article Element
## Summary
- `article` is used to wrap content when it is a blog entry, forum post, or news article.
- `article` is used for content that can stand alone.
- `<div>` - groups content `<section>` - groups related content `<article>` - groups independent, self-contained content.

## Final Code

{% highlight HTML %}
<h1>Deep Thoughts with Master Camper Cat</h1>
<main>
  <article>
    <h2>The Garfield Files: Lasagna as Training Fuel?</h2>
    <p>The internet is littered with varying opinions...</p>
  </div>

  <img src="samuraiSwords.jpeg" alt="">

  <article>
    <h2>Defeating your Foe: the Red Dot is Ours!</h2>
    <p>Felines the world over have been waging war...</p>
  </article>

  <img src="samuraiSwords.jpeg" alt="">

  <article>
    <h2>Is Chuck Norris a Cat Person?</h2>
    <p>Chuck Norris is widely regarded as the premier...</p>
  </article>
</main>
{% endhighlight %}