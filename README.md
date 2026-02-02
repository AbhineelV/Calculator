# Calculator

🧮 Simple Web Calculator
A sleek, responsive calculator built using HTML5, CSS3 (Neumorphism-inspired), and Vanilla JavaScript. This project demonstrates how to handle user input and perform mathematical evaluations directly in the browser.

✨ Features
Basic Arithmetic: Supports addition, subtraction, multiplication, and division.
Neumorphic Design: Modern UI with soft shadows and a dark aesthetic.
Responsive Layout: Centered using Flexbox for a clean look on all screen sizes.
Real-time Evaluation: Uses JavaScript's eval() function for quick calculations.
Special Keys: Includes AC (All Clear) and DEL (Delete last character) functionality.

🛠️ Built With
HTML5: Structure and semantics.
CSS3: Custom styling, Flexbox, and CSS Transitions.
JavaScript: Logic and DOM manipulation.

📝 Code Highlights
The calculator uses a clever one-liner approach for the logic within the HTML onclick attributes:
Equals: onclick="display.value = eval(display.value)"
Delete: onclick="display.value = display.value.toString().slice(0,-1)"
