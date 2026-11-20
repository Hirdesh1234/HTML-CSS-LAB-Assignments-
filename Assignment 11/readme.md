linke1. Experiment Title Units and CSS Variables 2. Aim Use pixel, percentage, and rem units and define reusable CSS custom properties. 3. Software / Tools Required VS Code or text editor, web browser 4. Theory CSS units specify dimensions and typography. px is an absolute CSS pixel, % is relative to a containing dimension, and rem is relative to the root font size. Custom properties declared with --name are accessed using var(). 5. Algorithm / Procedure 42. Create units.html with 200px and 50% wide boxes, both 40px high, and 1.5rem paragraph. 43. Create variables.html with main, accent, and padding custom properties in :root. 44. Create tokens.css with primary, accent, heading-size, and spacing variables and apply them. 6. Program / Queries / Commands units.html

<title>CSS Units</title> <style> .box-px { width: 200px; height: 40px; background: steelblue; margin-bottom: 10px; } .box-percent { width: 50%; height: 40px; background: seagreen; } p { font-size: 1.5rem; } </style>
This paragraph uses a font size of 1.5rem.

variables.html

<title>CSS Variables</title> <style> :root { --main-color: #1d3557; --accent-color: #e63946; --page-padding: 20px; } body { color: var(--main-color); padding: var(--page-padding); } h1 { color: var(--accent-color); } </style>
CSS Variables
This page uses reusable custom properties for colours and spacing.

tokens.css :root { --primary-color: #1d3557; --accent-color: #e63946; --heading-size: 2rem; --spacing: 16px; } body { color: var(--primary-color); padding: var(--spacing); } h1 { color: var(--accent-color); font-size: var(--heading-size); }

Input The specified CSS values are the input.
Output Boxes show their specified widths and heights; paragraph text is enlarged; variables consistently apply colors, padding, and heading size. Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
Result The experiment 'Units and CSS Variables' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
Viva-Voce Questions • What does rem depend on? • What does percentage width depend on? • How do you define and use a CSS custom property?
