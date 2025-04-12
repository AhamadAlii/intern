# HTML Tables

HTML tables allow web developers to arrange data into rows and columns.

## Basic HTML Table

A basic HTML table is defined using the `<table>` tag.

### Example

```html
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>30</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Smith</td>
    <td>25</td>
  </tr>
</table>
```

## Table Tags

| Tag       | Description                          |
|-----------|--------------------------------------|
| `<table>` | Defines the table                    |
| `<tr>`    | Defines a table row                  |
| `<th>`    | Defines a table header               |
| `<td>`    | Defines a table cell                 |

## Table Borders

To add borders to a table, use the `border` attribute:

```html
<table border="1">
  <tr>
    <th>Item</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>Pen</td>
    <td>$1</td>
  </tr>
</table>
```

## Table Styling with CSS

### Example

```html
<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }

  th, td {
    border: 1px solid black;
    padding: 8px;
    text-align: left;
  }

  th {
    background-color: #f2f2f2;
  }
</style>
```

## Colspan and Rowspan

- `colspan` allows a cell to span multiple columns.
- `rowspan` allows a cell to span multiple rows.

### Example

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th colspan="2">Contact</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Email</td>
    <td>Phone</td>
  </tr>
</table>
```

## Summary

- Use `<table>` to create a table.
- Use `<tr>` to define rows.
- Use `<th>` for headers and `<td>` for data cells.
- Use `border`, `colspan`, and `rowspan` for layout control.
- Style tables using CSS for better design and responsiveness.
