---
layout: default
title: Create Visual Balance Using the text-align Property
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 1
---
# Create Visual Balance Using the text-align Property
## Summary
- `text-align: justify;` causes all lines of text except the last line to meet the left and right edges of the line box.
- `text-align: center;` centers the text.
- `text-align: right;` right-aligns the text.
- `text-align: left;` (the default) left-aligns the text.

## Final Code

{% highlight HTML %}
<style>
  h4 {
    text-align: center;
  }
  p {
    text-align: justify;
  }
  .links {
    margin-right: 20px;

  }
  .fullCard {
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px 5px;
    padding: 4px;
  }
  .cardContent {
    padding: 10px;
  }
</style>
<div class="fullCard">
  <div class="cardContent">
    <div class="cardText">
      <h4>Google</h4>
      <p>Google was founded by Larry Page...</p>
    </div>
    <div class="cardLinks">
      <a href="https://en.wikipedia.org/wiki/Larry_Page" target="_blank" class="links">Larry Page</a>
      <a href="https://en.wikipedia.org/wiki/Sergey_Brin" target="_blank" class="links">Sergey Brin</a>
    </div>
  </div>
</div>
{% endhighlight %}