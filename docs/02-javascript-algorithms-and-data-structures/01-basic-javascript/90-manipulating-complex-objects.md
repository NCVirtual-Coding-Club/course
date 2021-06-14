---
layout: default
title: Manipulating Complex Objects
parent: Basic JavaScript
grand_parent: JavaScript Algorithms and Data Structures
has_children: false
nav_order: 90
---
# Manipulating Complex Objects
## Summary
- Arrays and objects can be nested in one another. 

## Final Code

{% highlight JavaScript %}
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  }, {
    "artist": "Andrew Prahlow",
    "title": "14.3 Billion Years",
    "release_year": 2019,
    "formats": [
      "streaming",
      "download",
      "record"
    ]
  }
];
{% endhighlight %}