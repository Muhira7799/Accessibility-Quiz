# ♿ Accessibility Quiz

A responsive **HTML/CSS Accessibility Quiz** built to practice accessible web design, semantic HTML, forms, navigation, and responsive layouts.

The project contains student information fields, HTML and CSS quiz questions, and a simple submission form.

## 📌 Features

* Accessible quiz page layout
* Student information form
* HTML multiple-choice questions
* CSS questions with dropdown and textarea
* Semantic HTML elements
* Accessible labels for form controls
* Keyboard-friendly navigation
* Responsive navigation bar
* Screen-reader-only content
* Reduced-motion support
* Responsive logo and heading
* Footer with contact information

## 🛠️ Technologies Used

* **HTML5** – For semantic structure, forms, questions, and navigation
* **CSS3** – For layout, styling, responsiveness, and accessibility features
* **Flexbox** – For navigation, header, footer, and form layouts


## 🚀 How to Run

1. Clone the repository:

```bash id="4h2v7c"
git clone https://github.com/your-username/Accessibility-Quiz.git
```

2. Open the project folder.

3. Open `index.html` in your web browser.

No additional dependencies or installations are required.

## ♿ Accessibility Features

The project demonstrates several accessibility practices.

### Semantic HTML

Elements such as:

* `<header>`
* `<main>`
* `<nav>`
* `<section>`
* `<form>`
* `<fieldset>`
* `<legend>`
* `<footer>`
* `<address>`

are used to provide meaningful page structure.

### Form Labels

Each form input is associated with a label using matching `for` and `id` attributes:

```html
<label for="student-name">Name:</label>
<input type="text" id="student-name">
```

### Screen Reader Content

The `.sr-only` class hides text visually while keeping it available to screen readers:

```css
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
```

### Reduced Motion

The page respects users who prefer reduced motion:

```css
@media (prefers-reduced-motion: no-preference) {
  * {
    scroll-behavior: smooth;
  }
}
```

## 🎨 CSS Concepts Used

This project demonstrates:

* Flexbox
* Responsive design
* CSS media queries
* `max-width` and responsive sizing
* `display: flex`
* `justify-content`
* `align-items`
* CSS pseudo-elements
* CSS selectors
* Form styling
* Accessible hidden content
* Smooth scrolling

## 🎯 Learning Objectives

This project helps practice:

* Building accessible web pages
* Creating accessible forms
* Using semantic HTML
* Connecting labels with form controls
* Organizing content with sections
* Using ARIA attributes
* Creating responsive navigation
* Understanding screen-reader accessibility
* Using CSS Flexbox for page layouts



This project was created for educational and learning purposes.
