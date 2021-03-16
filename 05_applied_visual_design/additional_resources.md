# Week 9: Applied Visual Design

Complete [freeCodeCamp's Applied Visual Design](https://www.freecodecamp.org/learn/responsive-web-design/#applied-visual-design) (up to and including Adjust the Hover State of an Anchor Tag)

## Review of previous exercises

### Overriding styles
- CSS are read and applied top --> bottom.
- id selectors have [higher specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity) than class and element selectors.
  - inline styles trump id, class, and element selectors

### CSS Color
- Color (HEX and RGB)

### CSS Variables
- declare the variable: `--variable-name`
- using the variable: `var(--variable-name)`
- Using the `:root` pseudo-class selector

## New topics

### Styling Text
- Using HTML
  - emphasis/italics: `<em>`
  - bold: `<strong>`
  - underline: `<u>`
  - stikethrough: `<s>`
  - horizontal line: `<hr>`
- Using CSS
  - `text-align` - [Examples](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
  - `text-transform` - [Examples](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)
  - `line-height`

### Color
- alpha value/transparency: `rgba(r, g, b, a)` where alpha is between 0-1

### Shadow
- `box-shadow: offset-x offset-y blur-radius spread-radius color;` - [Examples](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

### Width
- We have used the width property on images, but the `width` property can be used on any element.
- [Examples](https://developer.mozilla.org/en-US/docs/Web/CSS/width)

### Opacity
- All elements can have their opacity/transparency changed.
- [Examples](https://developer.mozilla.org/en-US/docs/Web/CSS/opacity)

### Link Pseudo-classes
- [Examples](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)