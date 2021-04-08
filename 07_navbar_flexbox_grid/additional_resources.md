# Week 12 (Final Week)

## [Nav bars](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav)

Typically a nav bar is an unordered list of links (`<ul>`) placed inside of a (`<nav>`) element.

```
<nav>
    <ul>
        <li><a href="home.html">Home</li>
        <li><a href="about.html">About</li>
        <li><a href="contact.html">Contact</li>
    </ul>
</nav>
```

Using the `nav` element is not necessary, but it provides semantic meaning to your page, which is useful for screenreaders.

## [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

Flexbox is a useful tool for acheiving flexible (responsive) layouts.

To generate flexible boxes of content on your page, you apply the property `display: flex` to the parent element — this will typically be a `<div>`, `<ul>` or a semantic element such as `<section>`.
