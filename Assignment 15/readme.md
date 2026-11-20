Experiment Title Responsive Pages with Media Queries
Aim Create a mobile-first two-card layout, a responsive image, and responsive heading typography.
Software / Tools Required VS Code or text editor, web browser, image file
Theory Responsive design adapts layouts to viewport sizes. The viewport meta tag sets the layout viewport on mobile. Mobile-first CSS defines base styles for small screens and media queries add changes at larger widths. max-width:100% and height:auto keep images within their containers.
Algorithm / Procedure
Create mobile-first.html with viewport metadata and vertically stacked cards.
Add a min-width:600px media query to display cards side by side.
Create responsive-image.html with an image styled max-width:100% and height:auto; provide the image in images/.
Create responsive-text.html with 1rem body, 1.5rem h1, and 2.5rem h1 at 600px and above.
Program / Queries / Commands mobile-first.html
<title>Mobile First Cards</title> <style> .cards { display: flex; flex-direction: column; gap: 16px; } .card { padding: 20px; border: 1px solid #777; border-radius: 8px; } @media (min-width: 600px) { .cards { flex-direction: row; } .card { flex: 1; } } </style>
Card One
This card stacks on small screens.

Card Two
This card sits beside the first on wider screens.

responsive-image.html

<title>Responsive Image</title> <style>img { max-width: 100%; height: auto; }</style>
Responsive Image
A sample portfolio photograph

responsive-text.html

<title>Responsive Text</title> <style> body { font-size: 1rem; } h1 { font-size: 1.5rem; } @media (min-width: 600px) { h1 { font-size: 2.5rem; } } </style>
Responsive Heading
The heading grows on screens that are at least 600 pixels wide.

Input Viewport width and a local image file for the image task.
Output Cards stack on narrow screens and sit side by side at 600px+; image scales to its container; heading grows at the breakpoint. Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
Result The experiment 'Responsive Pages with Media Queries' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
Viva-Voce Questions • What is mobile-first design? • What does a media query test? • Why use max-width:100% with height:auto?
