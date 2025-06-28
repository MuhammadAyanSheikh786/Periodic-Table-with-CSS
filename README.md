# Periodic Table HTML Project

This project is a visual representation of the **Periodic Table of Elements** using HTML and CSS. Each element is placed in a `<td>` (table cell) to match its position in the table. Different element types (like metals, nonmetals, noble gases, etc.) are given different `id`s or `class`es for styling purposes.

## 📁 Project Structure

- `index.html` - Contains the HTML code for the periodic table layout.
- `style.css` - (Linked externally) Used to style the table, colors for groups, spacing, etc.

## 🧪 Features

- Table structure matches the periodic table layout
- Elements are grouped by color using `id` (like `green`, `darkm`, `brown`, etc.)
- Semantic use of `<br>` inside `<p>` tags for atomic number, symbol, and name

## ✅ Example Element Format

```html
<td id="green">
  <p>3 <br> Li <br> Lithium</p>
</td>
