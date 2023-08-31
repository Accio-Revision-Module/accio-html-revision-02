# HTML Revision Notes

## Table of Contents

1. [Marking up headings, paragraphs, and text](#marking-up-headings-paragraphs-and-text)
2. [Marking up lists, figures, and quotes](#marking-up-lists-figures-and-quotes)
3. [Marking up addresses, dates, and abbreviations](#marking-up-addresses-dates-and-abbreviations)
4. [Using semantic elements for better accessibility and SEO](#using-semantic-elements-for-better-accessibility-and-seo)
5. [Web Storage API (localStorage, sessionStorage)](#web-storage-api-localstorage-sessionstorage)
6. [Semantic markup for accessibility](#semantic-markup-for-accessibility)
7. [ARIA attributes and roles](#aria-attributes-and-roles)
8. [Keyboard accessibility](#keyboard-accessibility)
9. [Linking CSS and JavaScript files](#linking-css-and-javascript-files)
10. [Different input types](#different-input-types)
11. [Embedding videos](#embedding-videos)

---

## Marking up headings, paragraphs, and text

Headings use the `<h1>` to `<h6>` tags, while paragraphs use the `<p>` tag.

```html
<h1>Main heading</h1>
<h2>Subheading</h2>
<p>This is a paragraph.</p>
```

## Marking up lists, figures, and quotes

Lists use `<ul>` or `<ol>` and `<li>` tags. Figures use `<figure>` and `<figcaption>`. Quotes use `<blockquote>`.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<figure>
  <img src="image.jpg" alt="Description" />
  <figcaption>Caption goes here.</figcaption>
</figure>
<blockquote>
  <p>This is a quote.</p>
</blockquote>
```

## Marking up addresses, dates, and abbreviations

Addresses can use the `<address>` tag, dates can use the `<time>` tag, and abbreviations use `<abbr>`.

```html
<address>123 Main St, City, Country</address>
<time datetime="2021-12-25">Christmas Day</time>
<abbr title="Hypertext Markup Language">HTML</abbr>
```

## Using semantic elements for better accessibility and SEO

Semantic elements provide meaning to the structure of the web page, improving both SEO and accessibility.

```html
<header>Header content here</header>
<main>Main content here</main>
<footer>Footer content here</footer>
```

## Web Storage API (localStorage, sessionStorage)

These APIs allow you to store key-value pairs in the web browser.

```javascript
localStorage.setItem("key", "value");
const value = localStorage.getItem("key");
```

## Semantic markup for accessibility

Use roles and semantic elements to improve screen reader compatibility.

```html
<nav role="navigation">...</nav>
```

## ARIA attributes and roles

ARIA attributes improve accessibility by providing additional information.

```html
<button aria-label="Close">X</button>
```

## Keyboard accessibility

Make sure all functionality is available using the keyboard.

```html
<a href="#" tabindex="0">Clickable by keyboard</a>
```

## Linking CSS and JavaScript files

Use `<link>` for CSS and `<script>` for JavaScript.

```html
<link rel="stylesheet" type="text/css" href="styles.css" />
<script src="script.js"></script>
```

## Different input types

HTML5 introduced various input types like `email`, `date`, `range`, etc.

```html
<input type="email" placeholder="Enter email" />
```

## Embedding videos

Use the `<iframe>` tag for embedding videos from platforms like YouTube.

```html
<iframe src="https://www.youtube.com/embed/videoID"></iframe>
```

---
