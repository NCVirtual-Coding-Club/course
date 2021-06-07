---
layout: default
title: Avoid Colorblindness Issues by Carefully Choosing Colors that Convey Information
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 18
---
# Avoid Colorblindness Issues by Carefully Choosing Colors that Convey Information
## Summary
- Using colors that are close on the color wheel is not recommended.

## Final Code

{% highlight HTML %}
<head>
  <style>
  button {
    color: #003366;
    background-color: #FFFF33;
    font-size: 14px;
    padding: 10px;
  }
  </style>
</head>
<body>
  <header>
    <h1>Danger!</h1>
  </header>
  <button>Delete Internet</button>
</body>
{% endhighlight %}