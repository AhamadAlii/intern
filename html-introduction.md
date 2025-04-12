# HTML Introduction

HTML is the standard markup language for creating web pages.

## What is HTML?

- HTML stands for **Hyper Text Markup Language**
- HTML is the standard markup language for creating Web pages
- HTML describes the **structure** of a web page
- HTML consists of a series of **elements**
- HTML elements tell the browser how to **display** the content
- HTML elements label pieces of content such as:
  - "this is a heading"
  - "this is a paragraph"
  - "this is a link", etc.

## A Simple HTML Document

### Example

```html
<!DOCTYPE html> <!-- Declares the document type -->
<html> <!-- Root element -->
<head> 
  <title>Page Title</title> <!-- Sets the browser tab title -->
</head>
<body> <!-- Visible content -->
  <h1>My First Heading</h1> <!-- Main heading -->
  <p>My first paragraph.</p> <!-- A paragraph -->
</body>
</html>
```

### Example Explained

- `<!DOCTYPE html>` declaration defines that this document is an **HTML5 document**
- `<html>` is the **root element** of an HTML page
- `<head>` contains **meta information** about the HTML page
- `<title>` specifies a **title** for the HTML page *(shown in the browser’s tab)*
- `<body>` defines the **body of the document** — the container for visible content like headings, paragraphs, images, links, etc.
- `<h1>` defines a **large heading**
- `<p>` defines a **paragraph**

### Empty HTML Elements

Some HTML elements have no content and do not require a closing tag.

```html
<br> <!-- Line break -->
<hr> <!-- Horizontal rule -->
<img src="image.jpg" alt="Description"> <!-- Image tag -->
```

## What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:

```html
<tagname> Content goes here... </tagname>
```

The HTML element is everything from the start tag to the end tag:

```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

## Tags vs. Elements

- **Tags** are just the opening `<tag>` and closing `</tag>`
- **Elements** include the tags *and* the content inside

## Nesting HTML Elements

HTML elements can be placed inside one another, but must be properly closed:

```html
<p>This is a <strong>bold</strong> word in a paragraph.</p>
```

## Common HTML Tags

- `<a>` – Defines a hyperlink
- `<ul>`, `<ol>`, `<li>` – Create lists
- `<div>` – Block-level container
- `<span>` – Inline container
- `<form>`, `<input>` – For user input and forms
- `<meta>` – Metadata (inside `<head>`)

## Semantic HTML

HTML5 introduced semantic tags that describe the purpose of content:

- `<header>` – Introductory content
- `<nav>` – Navigation links
- `<main>` – Main content area
- `<section>` – A standalone section
- `<article>` – Independent content
- `<footer>` – Footer information

> These improve accessibility, SEO, and code readability.

## HTML5 – The Latest Version

- HTML5 is the latest version of HTML
- It introduced semantic tags, media support, better forms, and APIs
- It is the current standard for modern web development

## Why Learn HTML?

- HTML is the foundation of all web pages.
- Every website you visit uses HTML.
- Learning HTML is the first step to becoming a web developer.
