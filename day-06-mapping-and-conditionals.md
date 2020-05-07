# Day 6 - Mapping and Conditionals

<img src="https://raw.githubusercontent.com/adion81/mern-lectures/master/assets/React-icon.svg" width="256px" alt="React" />

## Iterating in React

We're probably familiar with using `for loops` to iterate through lists in our Views

#### SomeView.html
```html
<ul>
  {% for book in books %}
    <li>{{ book.title }} ({{ book.author }})</li>
  {% endfor %}
</ul>
```

But how should we do this in our React Components?