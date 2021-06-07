---
layout: default
title: Add an Accessible Date Picker
parent: Applied Accessibility
grand_parent: Responsive Web Design
has_children: false
nav_order: 13
---
# Add an Accessible Date Picker
## Summary
- The `date` field can be used to show a date picker in the input field.

## Final Code

{% highlight HTML %}
<body>
  <header>
    <h1>Tournaments</h1>
  </header>
  <main>
    <section>
      <h2>Mortal Kombat Tournament Survey</h2>
      <form>
        <p>Tell us the best date for the competition</p>
        <label for="pickdate">Preferred Date:</label>

        <!-- Only change code below this line -->
        <input type="date" id="pickdate" name="date">


        <!-- Only change code above this line -->

        <input type="submit" name="submit" value="Submit">
      </form>
    </section>
  </main>
  <footer>&copy; 2018 Camper Cat</footer>
</body>
{% endhighlight %}