---
layout: default
title: Make Links Navigable with HTML Access Keys
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 20
---
# Make Links Navigable with HTML Access Keys
## Summary
- The `accesskey` attribute allows the creation of shortcut keys.

## Final Code

{% highlight HTML %}
<body>
  <header>
    <h1>Deep Thoughts with Master Camper Cat</h1>
  </header>
  <article>


    <h2><a id="first" href="#" accesskey="g">The Garfield Files: Lasagna...</a></h2>


    <p>The internet is littered...</p>
  </article>
  <article>


    <h2><a id="second" href="#" accesskey="c">Is Chuck Norris a Cat Person?</a></h2>


    <p>Chuck Norris is widely regarded...</p>
  </article>
  <footer>&copy; 2018 Camper Cat</footer>
</body>
{% endhighlight %}