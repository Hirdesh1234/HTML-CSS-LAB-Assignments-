Experiment Title CSS Fundamentals
Aim Apply inline, internal, and external CSS using element, class, and ID selectors.
Software / Tools Required VS Code or text editor, web browser
Theory CSS styles HTML elements through selectors and declarations. Inline CSS uses style attributes; internal CSS uses a style element; external CSS uses a linked stylesheet. Element selectors target tags, class selectors target class values, and ID selectors target a unique id.
Algorithm / Procedure
Create inline-internal.html with navy h1, yellow highlight class, and red inline paragraph.
Create style.css with h1, .note, #title, and p rules.
Link style.css from linked.html and add the required elements.
Open linked.html to verify the external stylesheet.
Program / Queries / Commands inline-internal.html
<title>CSS Fundamentals</title> <style> h1 { color: navy; } .highlight { background-color: yellow; } </style>
CSS Fundamentals
This paragraph uses inline CSS to make its text red.

This paragraph has a yellow background.

style.css h1 { color: navy; } .note { font-style: italic; } #title { text-decoration: underline; } p { font-size: 18px; color: grey; }

linked.html

<title>Linked CSS</title>
Linked Stylesheet
This is the first note paragraph.

This is the second note paragraph.

Input HTML content is the input; CSS rules specify colors, font style, underline, and font size.
Output Heading appears navy, inline paragraph red, highlighted paragraph yellow, and linked page uses external styles. Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
Result The experiment 'CSS Fundamentals' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
Viva-Voce Questions • What is CSS? • How do class and ID selectors differ? • What are the three ways to apply CSS?
