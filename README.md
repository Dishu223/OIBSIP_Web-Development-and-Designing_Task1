Neumorphic Calculator
A stylish, fully functional calculator web application built with a modern Neumorphic design. 
This project goes beyond basic calculations to include multiple themes, a history log, and full keyboard support, 
demonstrating a strong focus on both UI aesthetics and user experience.

Live Demo: [https://www.linkedin.com/posts/divyanshu-sharma-9807202b4_oasisinfobyte-oasisinfobytefamily-internship-activity-7361713200729325568-DyLC?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEuRu3AB75E8t7m6nJeN7xTh5wVY6L_KmSI]

Objective
The goal of this project was to build an interactive calculator that was not only functional but also visually unique. 
The primary challenge was to implement a clean Neumorphic UI and pack it with advanced features like theme switching and a persistent history log, all using vanilla HTML, CSS, and JavaScript.

Steps Performed
----------------
Core Logic: The calculator's brain was built using an object-oriented approach in JavaScript, with a Calculator class managing all states and computations (current operand, previous operand, operation).

Neumorphic Design: The distinct "soft UI" look was achieved entirely with CSS, using complex box-shadow properties to create the illusion of extruded and inset elements.

Theme Switching: Three distinct visual themes (Light, Dark, and Cyberpunk) were created. JavaScript is used to toggle a class on the body element, which then applies a different set of CSS variables to change the entire color scheme and button styles.

Feature Implementation:

A History Log was added to display previous calculations, with the data being managed within the Calculator class.

Keyboard Support was implemented by adding a global keydown event listener that maps keyboard inputs (0-9, +, -, *, /, Enter, Backspace) to the corresponding calculator functions.

Dynamic Animations were added for button presses and number updates on the display to make the interface feel more responsive and tactile.

Tools Used
HTML5: For the structure of the calculator grid and display.

CSS3:

CSS Grid: For the precise layout of the calculator buttons.

CSS Custom Properties (Variables): To manage theme colors and make theme switching efficient.

Advanced box-shadow: To create the Neumorphic visual style.

JavaScript (ES6+):

Object-Oriented Programming (Classes): To organize and manage the calculator's state and logic cleanly.

DOM Manipulation: To update the display and handle user interactions.

Outcome
The result is a beautiful, feature-rich calculator that stands out from standard designs. This project was a deep dive into creating a complex, stateful UI with vanilla JavaScript and advanced CSS. It successfully demonstrates skills in object-oriented programming, dynamic styling, and building a user-friendly, interactive web application from scratch.
