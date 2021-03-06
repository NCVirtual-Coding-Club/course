---
layout: default
title: Add a box-shadow to a Card-like Element
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 11
---
# Add a box-shadow to a Card-like Element
## Summary
- The `box-shadow` property applies one or more shadows to an element.
    - `offset-x` (how far to push the shadow horizontally from the element),
    - `offset-y` (how far to push the shadow vertically from the element),
    - `blur-radius`,
    - `spread-radius` and
    - `color`, in that order.
- The blur-radius and spread-radius values are optional.


## Final Code

{% highlight HTML %}
<style>
  h4 {
    text-align: center;
    background-color: rgba(45, 45, 45, 0.1);
    padding: 10px;
    font-size: 27px;
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
  #thumbnail {
    box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
  }
</style>
<div class="fullCard" id="thumbnail">
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