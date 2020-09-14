# Getting started with Bootstrap

Bootstrap consists of 2 parts - CSS and JavaScript. For now, we will include only the CSS part in our project.

1. Include via CDN (Content Delivery Network): [https://getbootstrap.com/docs/4.5/getting-started/introduction/#css](https://getbootstrap.com/docs/4.5/getting-started/introduction/#css)

2. Include in your project, after downloading: [https://getbootstrap.com/docs/4.5/getting-started/download/#compiled-css-and-js](https://getbootstrap.com/docs/4.5/getting-started/download/#compiled-css-and-js)

It is a good idea to keep all external libraries in a folder called `lib`, `library` or `vendor`.

## Reboot

Bootstrap comes with its [own CSS](https://getbootstrap.com/docs/4.5/content/reboot/) that normalizes appearance of elements across browsers, so no need to add `normalize.css` or `reset.css`.

## Grid

Bootstrap uses flexbox to implement a design grid. What we know about flexbox can be applied to the grid utility classes that Bootstrap is offering.

In short, what we need is a `.container` wrapping element with the `.row` class. Inside each `.row`, we can add elements with the class `.col`.
If we dont specify explicitly a size, each column will have equal width.
Columns can also be applied only at a certain breakpoint.

Read more about [Bootstrap grid](https://getbootstrap.com/docs/4.5/layout/grid/).

## Flex utility classes

Bootstrap comes with a set of flexbox related utility classes, that follow the naming of the CSS flex properties and values.

Read more about [flexbox utility classes](https://getbootstrap.com/docs/4.5/utilities/flex/).

## Resources

- [Official Bootstrap Documentation](https://getbootstrap.com)
Keep an eye on the version, when looking at the docs.