# 📚 Book Inventory

A simple **Book Inventory Table** built using **HTML and CSS**.
This project displays books along with their **title, author, category, reading status, and rating** using styled table rows, gradients, and CSS attribute selectors.

## Features

* 📖 Display books in a structured table layout
* 🎨 Different gradient backgrounds based on reading status:

  * **Read** → Pink gradient
  * **To Read** → Blue gradient
  * **In Progress** → Purple gradient
* ⭐ Visual rating system using circles
* 🏷 Styled status badges
* 🧩 Uses **CSS attribute selectors**
* 📱 Centered and clean layout

## Technologies Used

* HTML5
* CSS3

## Project Structure

```plaintext
book-inventory/
│
├── index.html
├── styles.css
└── README.md
```

## CSS Concepts Practiced

* Attribute selectors:

  ```css
  span[class="status"]
  span[class^="rate"]
  ```
* Gradient backgrounds:

  ```css
  linear-gradient()
  ```
* Pseudo-class selectors:

  ```css
  :nth-child()
  ```
* Table styling
* Inline-block layout
* Borders and shadows

## Status Color Guide

| Status      | Style               |
| ----------- | ------------------- |
| Read        | Pink gradient       |
| To Read     | Light blue gradient |
| In Progress | Plum gradient       |

## Rating System

The rating uses nested `<span>` elements:

```html
<span class="rate two">
  <span></span>
  <span></span>
  <span></span>
</span>
```

Examples:

* `rate one` → ⭐
* `rate two` → ⭐⭐
* `rate three` → ⭐⭐⭐

## Learning Outcomes

By building this project, you practice:

* Creating tables in HTML
* Applying CSS selectors effectively
* Using attribute selectors for targeted styling
* Designing simple UI components
* Working with gradients and shadows

## Preview

A colorful book inventory table showing reading progress and ratings visually.
Created as html css practice project.
