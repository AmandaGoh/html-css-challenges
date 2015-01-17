## Background & Objectives

Use advanced selectors (id, class, grouping, descendant selectors) to fine-tune your page with a more subtle design.

## Specs

Here is [your objective](http://lewagon.github.io/html-css-challenges/04-advanced-selectors/). Any time you want to name an element of your page, ask yourself:

- Should I use a `class` or an `id`?
- What name should I pick for my class?

Try to use **generic class names** as much as you can. Think **modularity** & **re-usability**. Try to step back from the page you're coding when choosing class names. Consider each CSS class as nice re-usable design that is not only linked to your current page but that will be re-used everywhere on your website. This mindset is the main difficulty for CSS beginners.

## Tips & Resources

To design your lists of icons, you should change the `block` behavior of list items by inlining them. The problem with pure `inline` elements is that their width depends only on its content. To keep hands on list item width, make them `inline-blocks` elements. These kind of element have inline behavior but you can still play on their box model, yeah! Here are the corresponding CSS rules.

```css
ul > li{
  display: inline-block;
  width: 90px;
}
```