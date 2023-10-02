# Fincra clone

This is a task autocredit's interns are to work on.. to show how far we've inproved on our skills

## Directory structure

```sh
|-- components
|-- css
|-- js
|-- node_modules
|-- assets
    |-- images
```

## STYLE GUIDE

The project would be following BEM **Block Element Modifier** styling conventions in CSS.

```css
/* For class names */
.camelCaseClassName {
}
/* Block component: Standalone entity that is meaningful on its own */
.card {
}

/* Element: An entity that depends upon the block */
.card__image {
}
.card__item {
}
.card__button {
}

/* Modifier that changes the style of the block or block element*/
.card__item--active {
}
.card__button--active {
}

When the class names has more than a word?? .card__imageGalley {
}
```

And the markup will look like this:

```html
<div class="card">
  <span class="card__image"></span>
  <div class="card__content">
    <ul class="card__list">
      <li class="card__item card__item--active">Item 1</li>
      <li class="card__item">Item 2</li>
    </ul>
    <p class="card__description">Lorem Ipsum excet tera ..</p>
    <a class="card__button" href="/">Click Here</a>
  </div>
</div>
```

## Code Formatting

It'd be nice codes you're commiting are already formatted; using prettier.
