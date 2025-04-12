
# HTML Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing.

## Example

**First name:** John  
**Last name:** Doe

## The `<form>` Element

The HTML `<form>` element is used to create an HTML form for user input:

```html
<form>
  .
  form elements
  .
</form>
```

The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

## The `<input>` Element

The HTML `<input>` element is the most used form element. It can be displayed in many ways, depending on the `type` attribute.

### Input Types

| Type | Description |
|------|-------------|
| `<input type="text">` | Displays a single-line text input field |
| `<input type="radio">` | Displays a radio button |
| `<input type="checkbox">` | Displays a checkbox |
| `<input type="submit">` | Displays a submit button |
| `<input type="button">` | Displays a clickable button |

## Text Fields

Defines a single-line input field for text:

```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

## The `<label>` Element

Defines a label for form elements. It improves accessibility and allows easier interaction.

## Radio Buttons

Allows the user to select ONE of a limited number of choices.

```html
<p>Choose your favorite Web language:</p>
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
```

## Checkboxes

Allows the user to select ZERO or MORE options:

```html
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
```

## The Submit Button

Used to submit form data to a server.

```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

## The `name` Attribute

Each input field must have a `name` attribute to be submitted.

```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" value="John"><br><br>
  <input type="submit" value="Submit">
</form>
```
