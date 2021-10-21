# kickers
A portfolio website built with vanilla HTML, CSS, and a sprinkle of JavaScript.

Studied and adapted from [Kevin Powell / freeCodeCamp](https://youtu.be/_xkSvufmjEs)

## Learning Notes

- Used BEM (Block, Element, Modifier) methodology to clarify parent-child relationships, as well as modifier relationships. 
    - Example: .footer__link to target the link within the footer.
    - Example: section__title--about to qualify this as the section title of the "about" section
    - Benefits: When making a new style of a component we can see which modifiers and children already exist.
    - Benefits: Readability. Scanning the CSS we can see which elements depend on each other
    - Benefits: Choosing a naming convention that others can easily reference. 
    - Benefits: Feel confident that when you change something you know it won't break everything else.
    - Reference: [BEM 101 by Robin Rendle](https://css-tricks.com/bem-101/)

- Import dependencies using CDN

- Properly implement Open Graph Tags.
    - Used the Sharing Debugger Tool to test tags
    - Referenced the OG documentation for which tags to include.

- CSS Grid for portfolio items for responsive movement without media queries.
```
.portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}
```

