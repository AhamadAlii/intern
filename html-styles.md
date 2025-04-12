# HTML Styles

HTML styles are used to add styling to HTML elements using the `style` attribute.

## The HTML Style Attribute

The `style` attribute is used to add styles to an element, such as color, font, size, and more.

### Example

```html
<p style="color:blue;">This is a blue paragraph.</p>
```

## Style Syntax

```html
<tagname style="property:value;">
```

- The `property` is a CSS property.
- The `value` is a CSS value.

## Common CSS Properties Used in HTML

| Property     | Description                          |
|--------------|--------------------------------------|
| `color`      | Sets the text color                  |
| `background-color` | Sets the background color     |
| `font-family`| Sets the font of the text            |
| `font-size`  | Sets the size of the text            |
| `text-align` | Aligns the text (left, center, right)|

## Example: Text Color

```html
<h1 style="color:red;">This is a red heading</h1>
<p style="color:green;">This is a green paragraph.</p>
```

## Example: Background Color

```html
<p style="background-color:lightgray;">This is a paragraph with a background color.</p>
```

## Example: Font Family

```html
<p style="font-family:verdana;">This is a paragraph in Verdana font.</p>
```

## Example: Font Size

```html
<p style="font-size:30px;">This is a paragraph with a large font size.</p>
```

## Example: Text Alignment

```html
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:right;">Right-aligned paragraph.</p>
```

> Note: Inline styles are useful for quick changes, but it's better to use CSS in a `<style>` tag or an external stylesheet for larger projects.

## HTML Style Best Practices

- Use inline styles only for quick, specific changes
- Prefer using `<style>` tags or external CSS files for maintainability
- Separate content (HTML) from presentation (CSS) for cleaner code
