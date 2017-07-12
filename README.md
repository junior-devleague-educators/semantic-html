# Semantically-correct HTML

> Semantic - fancy word for 'meaning'

There are three layers in the web browser:

1. HTML - Structure layer

2. CSS - Style or Presentation layer

3. Javascript - Interaction, Dynamic, and Logic Layer

Keeping these three layers and their code separate from each other keeps code clean. The days of declaring styles and logic in-line are gone*.

Writing meaningful HTML should be your goal but why use all these fancy HTML tags when i can just use `div`? Four reasons:
- Ease of use
- Accessibility
- Search Engine Optimisation

## Ease of use ( you and/or your teammates )
Semantic HTML is **clean** HTML, it's easier to work with and every block of code has clear intent. Clean markup saves time and **time is money**. Clean code usually ends up with the benefit of readability and smaller file sizes and better performance.

## Accessibility ( end-users )
Building your site with accessibility in mind increases useability. Having clean code without the clutter of extra styles or logic allows [screen readers](https://en.wikipedia.org/wiki/Screen_reader) to do their job easier.

## Search Engine Optimisation ( search-engine robots )
Another user type are search engine robots. With semantic HTML, search engine algorithms will parse your web page or application more accurately and will rannk you higher than a site that is harder to parse. This is great for users in that they are able to find your product faster, and your company since you are selling more products, and that keeps you, the developer, happy.

## HTML tags to start considering
`<html>`, `<body>`, `<head>`, `<body>`, `<script>`, `<link>` are all needed to build great apps, always.

### Sections
-`<h1>`, `<h2>`, etc. represent headings for their sections. [ref](http://www.w3.org/wiki/HTML/Elements/h1,_h2,_h3,_h4,_h5,_and_h6)
- `<nav>` represents a section with navigation links. [ref](http://www.w3.org/wiki/HTML/Elements/nav)
- `<header>` represents a group of introductory or navigational aids. [ref](http://www.w3.org/wiki/HTML/Elements/header)
- `<section>` represents a generic section of a document or application. [ref](http://www.w3.org/wiki/HTML/Elements/section)
- `<article>` represents an independent item section of content. [ref](http://www.w3.org/wiki/HTML/Elements/article)
- `<aside>` represents a section of a page that is loosely related to the content around it but can be considered not critical to the overall understanding of the content. [ref](http://www.w3.org/wiki/HTML/Elements/aside)
- `<footer>` represents a footer for its nearest ancestor sectioning content or sectioning root element. [ref](http://www.w3.org/wiki/HTML/Elements/footer)

### Grouping Content
- `<p>` groups content, generic and should not be used when a more specific element is appropriate.
- `<ul>` unordered list
- `<ol>` ordered list
- `<li>` list element
- `<div>` misc grouping, geneeric and should not be used when a moe specific element is appropriate.
- `<blockquote>`

### Text-level semantics
- `<a>` hyperlink
- `<em>` emphasis. Use this instead of `<i>`
- `<q>` a quote
- `<span>` 
- `<time>` specifies date and time section

### Embedded content
- `<img>`
- `<iframe>`
- `<embed>`
- `<video>`
- `<audio>`
- `<canvas>`
- `<frame>`
- `<svg>`

### Tables
- `<table>`
- `<caption>`
- `<colgroup>`
- `<col>`
- `<tbody>`
- `<thead>`
- `<tfoot>`
- `<tr>`
- `<td>`
- `<th>`

### Forms
- `<forms>`
- `<fieldset>`
- `<label>`
- `<input>`
- `<button>`
- `<select>`
- `<optgroup>`
- `<option>`
- `<textarea>`

## References
- [w3wiki](http://www.w3.org/wiki/HTML/Elements)

- [Nice list of Semantic Tags with comments on when/if you should use them](http://webdesignfromscratch.com/html-css/list-of-html-tags-with-semantic-usage/)

## Exercise
[bit.ly/dlphtml](http://bit.ly/dlphtml)

Recreate the HTML in images #1 through #3. Use Semantically-correct HTML structure. You can use your own data.

Once done, style it to look like image #4.
