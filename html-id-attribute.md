# HTML `id` Attribute

The HTML `id` attribute is used to specify a **unique id** for an HTML element.

> ⚠️ You cannot have more than one element with the same id in an HTML document.

---

## What is the `id` Attribute?

The `id` attribute specifies a unique identifier for an HTML element.

- The value must be **unique** within the HTML document.
- It can be used by:
  - **CSS** to apply styles
  - **JavaScript** to access/manipulate the element

### Syntax

```css
#myId {
  /* CSS styles */
}
```

---

## Example

```html
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```

> 🔹 The id name is **case sensitive**  
> 🔹 Must contain at least one character  
> 🔹 Cannot start with a number or include whitespace

---

## Difference Between Class and ID

| Attribute | Usage                     |
|----------|---------------------------|
| `id`     | Unique — used once        |
| `class`  | Reusable — used many times |

### Example

```html
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
}
</style>

<h1 id="myHeader">My Cities</h1>

<h2 class="city">London</h2>
<p>London is the capital of England.</p>

<h2 class="city">Paris</h2>
<p>Paris is the capital of France.</p>

<h2 class="city">Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>
```

---

## HTML Bookmarks with ID and Links

Bookmarks allow users to jump to a specific section of a page.

### Create the Bookmark

```html
<h2 id="C4">Chapter 4</h2>
```

### Link to the Bookmark (same page)

```html
<a href="#C4">Jump to Chapter 4</a>
```

### Link to Bookmark (from another page)

```html
<a href="html_demo.html#C4">Jump to Chapter 4</a>
```

---

## JavaScript with the `id` Attribute

JavaScript can access elements by ID using `getElementById()`.

### Example

```html
<script>
function displayResult() {
  document.getElementById("myHeader").innerHTML = "Have a nice day!";
}
</script>
```

---

## Chapter Summary

- `id` specifies a **unique identifier** for an HTML element.
- It is used by **CSS** and **JavaScript**.
- It is **case-sensitive** and must be **unique**.
- Also useful for **bookmarks** and **JavaScript manipulation**.
