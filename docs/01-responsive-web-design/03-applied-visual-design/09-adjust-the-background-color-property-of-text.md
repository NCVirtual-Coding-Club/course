---
layout: default
title: Adjust the background-color Property of Text
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 9
---
# Adjust the background-color Property of Text
## Summary
- `rgba()` controls the colors Red, Green, Blue, and the opacity of the color.

## Final Code

{% highlight HTML %}
<style>
  h4 {
    text-align: center;
    padding: 10px;
    background-color: rgba(45, 45, 45, 0.1);

  }
  p {
    text-align: justify;
  }
  .links {
    text-align: left;
    color: black;
  }
  .fullCard {
    width: 245px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px 5px;
    padding: 4px;
  }
  .cardContent {
    padding: 10px;
  }
  .cardText {
    margin-bottom: 30px;
  }
</style>
<div class="fullCard">
  <div class="cardContent">
    <div class="cardText">
      <h4>Alphabet</h4>
      <hr>
      <p><em>...they were <u>Ph.D. students</u> at <strong>Stanford University</strong>.</em></p>
    </div>
    <div class="cardLinks">
      <a href="https://en.wikipedia.org/..." target="_blank" class="links">Larry Page</a><br><br>
      <a href="https://en.wikipedia.org/..." target="_blank" class="links">Sergey Brin</a>
    </div>
  </div>
</div>
{% endhighlight %}