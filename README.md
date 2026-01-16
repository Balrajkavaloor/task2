# Project Style Guide – HTML & CSS Website

## Overview

This project is a simple, clean, and professional static website built using **semantic HTML5** and **external CSS styling**.  
It demonstrates best practices in web development such as:

- Proper HTML structure  
- Use of semantic elements  
- CSS Box Model  
- Class-based styling  
- Responsive design  
- Clean and maintainable code  

The project is designed as a learning exercise to understand how HTML and CSS work together to create structured and visually appealing web pages.

---

## Project Structure

The project contains the following files:

project-folder/
│
├── index.html
├── style.css
└── README.md

### File Descriptions

- **index.html** – Contains the complete semantic structure of the webpage.
- **style.css** – Contains all the styling rules applied to the HTML page.
- **README.md** – Documentation file explaining the project.

---

## Features Implemented

### 1. Semantic HTML Structure

The webpage uses proper HTML5 semantic elements such as:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<footer>`

This improves:

- Readability  
- Accessibility  
- SEO  
- Maintainability  

---

### 2. External CSS File

All styling is written in a separate `style.css` file and properly linked inside the `<head>` section of `index.html` using:

```html
<link rel="stylesheet" href="style.css">
