---
layout: default
title: Create a Media Query
parent: Responsive Web Design Principles
grand_parent: Responsive Web Design
has_children: false
nav_order: 1
---
# Create a Media Query
## Summary
- Media Queries are used to change the presentation of content based on a device's viewport size.
    - The viewport is a user's visible area of a web page.

## Final Code

{% highlight HTML %}
<style>
  p {
    font-size: 20px;
  }

  /* Only change code below this line */
  @media (max-height: 800px){ 
    p {
    font-size: 10px;
      }
  }
  /* Only change code above this line */
</style>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus massa. Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet lectus. Sed sit amet quam nibh. Suspendisse quis tincidunt nulla. In hac habitasse platea dictumst. Ut sit amet pretium nisl. Vivamus vel mi sem. Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida consequat, nunc ligula ultricies diam, at aliquet velit libero a dui.</p>
{% endhighlight %}