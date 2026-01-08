# Accordion Component

A simple **Accordion UI component** built using **HTML, CSS, and JavaScript**. This project is beginner-friendly and suitable for learning DOM manipulation and event handling.

## 📁 Project Structure

project-folder/
│── index.html
│── style.css
│── script.js
│── README.md

## ✨ Features

* Clean and minimal accordion layout
* Only one accordion item opens at a time
* Click again to close the open section
* Built using pure JavaScript (no libraries)
* Easy-to-read and maintainable code

## 🧱 HTML Structure

The accordion is structured as follows:

* `.accordion` → Parent container
* `.accordion-item` → Individual accordion block
* `.accordion-header` → Clickable button (title)
* `.accordion-content` → Hidden content section

Each header controls the visibility of its immediate sibling content.

## 🎨 CSS Overview

* Centers the accordion on the page
* Adds borders for visual separation
* Hides accordion content initially using:

```css
display: none;
```

The visibility is later controlled via JavaScript.

## ⚙️ JavaScript Logic

The JavaScript handles the accordion behavior:

1. Selects all accordion headers
2. Attaches click events to each header
3. Closes all other open accordion sections
4. Toggles the clicked section (open/close)

### Concepts Used

* `querySelectorAll()`
* `forEach()`
* `addEventListener()`
* `nextElementSibling`
* Inline style manipulation


## 🔄 How It Works

1. User clicks on an accordion title
2. Any previously opened section closes
3. The clicked section toggles its visibility

➡️ Ensures only **one section is open at a time**


## 📌 Conclusion

This project is ideal for beginners to understand **DOM traversal**, **event handling**, and **basic UI interactions** using vanilla JavaScript.

