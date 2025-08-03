# 🎨 Color Switching Scheme Boxes

A simple and interactive mini web project that demonstrates dynamic color switching functionality using **HTML**, **CSS**, and **JavaScript**.

---

## 📁 Project Description

This mini project showcases a creative way to switch colors in different boxes on a webpage. The boxes are built using `<span>` elements and styled with CSS to look visually appealing. JavaScript adds interactivity, allowing each box to change its color when clicked or triggered.

---

## 🛠️ Technologies Used

- **HTML** - For creating the structure and elements of the webpage.
- **CSS** - Used to style the boxes and layout to enhance visual design.
- **JavaScript** - Implements functionality to change the color of boxes dynamically.

---

## 📌 Features

- Colorful layout using `<span>` elements.
- Smooth and responsive color-switching effects.
- Clean and minimalistic UI.
- Lightweight and beginner-friendly codebase.

---

## 📂 File Structure
## 🧠 JavaScript: Color Switching Logic

This script selects all elements with the class `.button` and adds a `click` event listener to each. Based on the `id` of the clicked button, it changes the `background-color` of the document body.

---

### ✅ Code:

```js
// Select all elements with the class 'button'
const buttons = document.querySelectorAll('.button');

// Select the body element
const body = document.querySelector('body');

// Iterate over each button
buttons.forEach(function (button) {
  console.log(button); // Log the current button element

  // Add a click event listener to the button
  button.addEventListener('click', function (e) {
    console.log(e); // Log the full event object
    console.log(e.target); // Log the clicked element

    // Check the ID of the clicked element and change body background accordingly
    if (e.target.id === 'grey') {
      body.style.background = e.target.id;
    }
    if (e.target.id === 'white') {
      body.style.background = e.target.id;
    }
    if (e.target.id === 'blue') {
      body.style.background = e.target.id;
    }
    if (e.target.id === 'yellow') {
      body.style.background = e.target.id;
    }
    if (e.target.id === 'purple') {
      body.style.background = e.target.id;
    }
  });
});


