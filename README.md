# 🌐 Web Development Basics: HTML, CSS & JavaScript

📅 **Learning Duration:** June 2025 – Present  
🎯 **Goal:** Completed HTML & CSS | Currently Learning JavaScript Basics

---

## ✅ Completed

### 🔹 HTML (June 2025)
- Structure of web pages
- Elements, tags, attributes
- Forms, tables, semantic HTML

### 🔹 CSS (July 2025)
- Styling HTML elements
- Inline, internal, and external stylesheets
- Box model, positioning, margins/padding, fonts, and colors

---

## 🚀 Currently Learning: JavaScript Basics (August 2025)

### 📘 Topics Covered:
- JavaScript Declaration & Syntax
- DOM (Document Object Model) Introduction
- DOM Manipulation
- Control Statements: `if`, `else`, `switch`
- Looping Statements: `for`, `while`, `do...while`
- Jumping Statements: `break`, `continue`
- Alert Boxes
- Functions in JS (Named & Arrow Functions)
- Event Handling
- DOM Access Methods: `getElementById()`, `getElementsByTagName()`

---

## 🧪 Demo Code: All-in-One HTML + JS

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>JavaScript Basics Demo</title>
  <style>
    body { font-family: Arial; padding: 20px; background-color: #f0f0f0; }
    #result { color: green; font-weight: bold; }
  </style>
</head>
<body>

  <h2>JavaScript Basics Demo</h2>

  <button onclick="showAlert()">Click Me (Alert)</button>
  <p id="result"></p>

  <script>
    // Alert Box
    function showAlert() {
      alert("Welcome to JavaScript!");
      updateContent();
    }

    // DOM Manipulation
    function updateContent() {
      document.getElementById("result").innerText = "You clicked the button!";
    }

    // Control Statement Example
    let age = 18;
    if (age >= 18) {
      console.log("You are an adult.");
    } else {
      console.log("You are a minor.");
    }

    // Looping Example
    for (let i = 1; i <= 3; i++) {
      console.log("Loop index: " + i);
    }

    // Function Example
    function greet(name) {
      return "Hello, " + name;
    }
    console.log(greet("Harikrishna"));

    // Arrow Function
    const add = (a, b) => a + b;
    console.log("Addition: " + add(5, 3));
  </script>

</body>
</html>
