# Book Inventory – CSS Attribute Selectors

**Completed:** January 2026  
**Platform:** freeCodeCamp  
**Project Type:** HTML & CSS

## Project Overview

This project is a small **Book Inventory table** built as part of a freeCodeCamp CSS challenge.  
The goal was to practice **CSS attribute selectors** (selectors that style elements based on the values of their HTML attributes, such as `class`) by styling table rows, status labels, and rating indicators based only on class values.

No JavaScript was used — all styling logic is handled purely with HTML and CSS.

## What This Project Demonstrates

- **Semantic HTML table structure** (using proper table elements like `<table>`, `<thead>`, `<tbody>`, `<tr>`, and `<td>` for accessibility and clarity)
- **Advanced CSS attribute selectors** (CSS selectors that match elements by attribute value, not just tag or class name):
  - **Exact match selectors** (target elements with an attribute set to an exact value, e.g. `class="read"`)
  - **Starts-with selectors (`^=`)** (target elements whose attribute value begins with specific text)
  - **Contains-word selectors (`~=`)** (target elements whose attribute contains a specific word in a space-separated list)
  - **Descendant selectors** (target elements that appear inside other elements)
- **Conditional styling using only CSS** (changing appearance based on state without JavaScript)
- **Visual status indicators** (Read, To Read, In Progress shown using styled `<span>` elements)
- **Star-style rating system** built with nested `<span>` elements (using CSS to visually represent ratings)
- **Linear gradients** applied via attribute selectors (smooth color transitions used instead of flat colors)

## Live Demo

You can view the project here:

👉 **https://mitchferg2016.github.io/book-inventory-css-attribute-selectors-january-2026/**

## Files Included

- `index.html` – HTML structure for the book inventory table  
- `styles.css` – All styling logic using CSS attribute selectors  

## Notes

This project was completed to reinforce precision with CSS selectors and demonstrate clean, readable markup combined with expressive styling — a strong foundation for front-end development.
