---
layout: default
title: Lock an Element to its Parent with Absolute Positioning
parent: Applied Visual Design
grand_parent: Responsive Web Design
has_children: false
nav_order: 21
---
# Lock an Element to its Parent with Absolute Positioning
## Summary
- The `absolute` `position` property locks an element in place relative to its parent container.
- Removes the element from the normal flow of the document.

## Final Code

{% highlight HTML %}
<style>
  #searchbar {
    position: absolute;
    top: 50px;
    right: 50px;
  }
  section {
    position: relative;
  }
</style>
<body>
  <h1>Welcome!</h1>
  <section>
    <form id="searchbar">
      <label for="search">Search:</label>
      <input type="search" id="search" name="search">
      <input type="submit" name="submit" value="Go!">
    </form>
  </section>
</body>
{% endhighlight %}