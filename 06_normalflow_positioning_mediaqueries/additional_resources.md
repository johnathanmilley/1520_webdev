# Week 10

## Weekly Tasks
- Complete the next 7 exercises under [Applied Visual Design](https://www.freecodecamp.org/learn/responsive-web-design/#applied-visual-design), up to and including *Center an Element Horizontally Using the margin Property*.
- Complete the 4 tasks on under [Responsive Web Design Principles](https://www.freecodecamp.org/learn/responsive-web-design/#responsive-web-design-principles)

## Normal Flow and Positioning

### What is normal flow?

The pages we have built to this point in the course have all followed what is called *[Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)*. Normal flow refers to the default drawing of HTML elements to the page. There are two types of elements—block and inline. 

Block elements, by default, take up the full-width of the screen. `<p>`, `<div>`, `<li>`, and `<h1>` are some of the block elements we have used so far. These appear one after another.

Inline elements, by default, are as tall and wide as their content. `<button>`, `<span>`, `<strong>`, and `<img>` are examples of inline elements. Inline elements will attempt to fit whereever they can on a line. If there is no room (width) remaining on the line, they will move to the next line.

- [Block elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)
- [Inline elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)

You can change how elements display on the screen by changing the CSS *display* property. More information here: https://www.digitalocean.com/community/tutorials/css-display-inline-vs-inline-block

One of the ways you can alter normal flow is through *positioning*. We'll cover some positioning in a short example, but here is a resources if you would like more detailed information: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning

## Media Queries

You can change the CSS rules on your web page depending on this size of the screen/browser your page is being viewed on.

```
p {
    font-size: 2.6rem;
}

@media (max-width: 600px) {
    /* CSS rules go here */
    p {
        font-size: 2rem;
    }
}
```

The above example, `font-size` of `<p>` elements would change to 2rem on screen sizes that are 600px wid and *less*.


```
body {
    background-color: blue;
}

@media (min-width: 600px) {
    /* CSS rules go here */
    body {
        background-color: red;
    }
}
```

In this example, the `background-color` will be red on screens greater than 600px wide.
