
# HTML Style Guide

Consistent, clean, and tidy HTML code makes it easier for others to read and understand your code.

Here are some guidelines and tips for creating good HTML code.

## Always Declare Document Type

Always declare the document type as the first line in your document.

The correct document type for HTML is:

```html
<!DOCTYPE html>
```

## Use Lowercase Element Names

HTML allows mixing uppercase and lowercase letters in element names.

However, we recommend using lowercase element names, because:

- Mixing uppercase and lowercase names looks bad
- Developers normally use lowercase names
- Lowercase looks cleaner
- Lowercase is easier to type

**Good:**
```html
<body>
<p>This is a paragraph.</p>
</body>
```

**Bad:**
```html
<BODY>
<P>This is a paragraph.</P>
</BODY>
```

## Close All HTML Elements

In HTML, you do not have to close all elements (for example the `<p>` element).

However, we strongly recommend closing all HTML elements, like this:

**Good:**
```html
<section>
  <p>This is a paragraph.</p>
  <p>This is a paragraph.</p>
</section>
```

**Bad:**
```html
<section>
  <p>This is a paragraph.
  <p>This is a paragraph.
</section>
```

## Use Lowercase Attribute Names

HTML allows mixing uppercase and lowercase letters in attribute names.

However, we recommend using lowercase attribute names, because:

- Mixing uppercase and lowercase names looks bad
- Developers normally use lowercase names
- Lowercase looks cleaner
- Lowercase is easier to type

**Good:**
```html
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
```

**Bad:**
```html
<a HREF="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
```

## Always Quote Attribute Values

HTML allows attribute values without quotes.

However, we recommend quoting attribute values, because:

- Developers normally quote attribute values
- Quoted values are easier to read
- You **must** use quotes if the value contains spaces

**Good:**
```html
<table class="striped">
```

**Bad:**
```html
<table class=striped>
```

**Very bad (will not work):**
```html
<table class=table striped>
```

## Always Specify `alt`, `width`, and `height` for Images

Always specify the `alt` attribute for images. This attribute is important if the image cannot be displayed.

Also, always define the width and height of images. This reduces flickering, because the browser can reserve space for the image before loading.

**Good:**
```html
<img src="html5.gif" alt="HTML5" style="width:128px;height:128px">
```

**Bad:**
```html
<img src="html5.gif">
```

## Spaces and Equal Signs

HTML allows spaces around equal signs. But space-less is easier to read and groups entities better together.

**Good:**
```html
<link rel="stylesheet" href="styles.css">
```

**Bad:**
```html
<link rel = "stylesheet" href = "styles.css">
```

## Avoid Long Code Lines

Avoid code lines that are too long. This makes code easier to read and edit.

## Blank Lines and Indentation

Do not add blank lines, spaces, or indentations without a reason.

For readability:
- Add blank lines to separate large or logical code blocks
- Use two spaces for indentation. **Do not use the tab key**

**Good:**
```html
<body>

<h1>Famous Cities</h1>

<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>

<h2>London</h2>
<p>London is the capital city of England. It is the most populous city in the United Kingdom.</p>

<h2>Paris</h2>
<p>Paris is the capital of France. The Paris area is one of the largest population centers in Europe.</p>

</body>
```

**Bad:**
```html
<body>
<h1>Famous Cities</h1>
<h2>Tokyo</h2><p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
<h2>London</h2><p>London is the capital city of England. It is the most populous city in the United Kingdom.</p>
<h2>Paris</h2><p>Paris is the capital of France. The Paris area is one of the largest population centers in Europe.</p>
</body>
```

## Good Table Example:
```html
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>A</td>
    <td>Description of A</td>
  </tr>
  <tr>
    <td>B</td>
    <td>Description of B</td>
  </tr>
</table>
```

## Good List Example:
```html
<ul>
  <li>London</li>
  <li>Paris</li>
  <li>Tokyo</li>
</ul>
```

## Never Skip the `<title>` Element

The `<title>` element is required in HTML and is very important for SEO.

It:
- Defines a title in the browser toolbar
- Provides a title for the page when it is added to favorites
- Displays a title for the page in search-engine results

**Example:**
```html
<title>HTML Style Guide and Coding Conventions</title>
```

## Omitting `<html>` and `<body>`?

An HTML page will validate without the `<html>` and `<body>` tags, but we recommend including them.

**Example (not recommended):**
```html
<!DOCTYPE html>
<head>
  <title>Page Title</title>
</head>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>
```

**Why include them?**
- Older browsers may produce errors
- Can crash DOM and XML software

## Omitting `<head>`?

Browsers will add all elements before `<body>` to a default `<head>` element.

**Example (not recommended):**
```html
<!DOCTYPE html>
<html>
<title>Page Title</title>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

However, we recommend using the `<head>` tag.

## Close Empty HTML Elements?

In HTML, it is optional to close empty elements.

**Allowed:**
```html
<meta charset="utf-8">
```

**Also Allowed (for XML/XHTML compatibility):**
```html
<meta charset="utf-8" />
```

## Add the `lang` Attribute

Always include the `lang` attribute in the `<html>` tag to declare the language of the page.

**Example:**
```html
<!DOCTYPE html>
<html lang="en-us">
<head>
  <title>Page Title</title>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
