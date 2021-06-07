---
layout: default
title: Improve Accessibility of Audio Content with the audio Element
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 9
---
# Improve Accessibility of Audio Content with the audio Element
## Summary
- The `audio` element gives semantic meaning when it wraps sound or audio stream content.
- The `audio` tag supports the controls attribute, allowing the browser to default play, pause, and other controls.

## Final Code

{% highlight HTML %}
<body>
  <header>
    <h1>Real Coding Ninjas</h1>
  </header>
  <main>
    <p>A sound clip of Zersiax's screen reader in action.</p>
    <audio controls>
      <source src="https://s3.amazonaws.com/freecodecamp/screen-reader.mp3" type="audio/mpeg">
    </audio>

  </main>
</body>
{% endhighlight %}