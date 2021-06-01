---
layout: default
title: Declare the Doctype of an HTML Document
parent: Basic HTML and HTML5
grand_parent: Responsive Web Design
has_children: false
nav_order: 27
---
# Nest Many Elements within a Single div Element
## Summary
- Any markup with information about your page would go into the `head` tag (what the user does not see).
- Any markup with the content of the page would go into the `body` tag (what the user does see).
Metadata elements, such as `link`, `meta`, `title`, and `style`, typically go inside the `head` element.
## Final Code

{% highlight HTML %}
<!DOCTYPE html>
<html>
  <head>
    <title>The best page ever</title>
  </head>

<body>
  <h1>The best page ever</h1>
  <p>Cat ipsum dolor sit amet...</p>
</body>
</html>
{% endhighlight %}