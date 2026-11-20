Experiment Title Box Model, Cards and Scrolling
Aim Compare box-sizing, style a card, and create a scrollable fixed-height container.
Software / Tools Required VS Code or text editor, web browser
Theory The CSS box model includes content, padding, border, and margin. content-box adds padding and border outside the declared width; border-box includes them within the declared width. overflow:auto enables scrolling when content exceeds the container.
Algorithm / Procedure
Create box-model.html with two 200px boxes, 20px padding, and 5px border; apply content-box and border-box.
Create card.html with background, 2px border, 12px radius, and 16px padding.
Create scroll.html with a 120px-high box, overflow:auto, and five paragraphs.
Program / Queries / Commands box-model.html
<title>Box Model</title> <style> .box { width: 200px; padding: 20px; border: 5px solid navy; margin: 12px; } .content-box { box-sizing: content-box; background: lightblue; } .border-box { box-sizing: border-box; background: lightgreen; } </style>
content-box
border-box
card.html

<title>Card</title> <style> .card { background: #eef6ff; border: 2px solid #1d3557; border-radius: 12px; padding: 16px; max-width: 360px; } </style>
Learning HTML & CSS
This card demonstrates a background, border, rounded corners, and padding.

scroll.html

<title>Scrollable Box</title> <style> .scroll-box { height: 120px; overflow: auto; border: 1px solid #333; width: 260px; } </style>
Line 1

Line 2

Line 3

Line 4

Line 5

Input CSS dimensions and five lines of text.
Output Content-box renders wider than border-box; card shows rounded bordered styling; scroll box allows scrolling through five lines. Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
Result The experiment 'Box Model, Cards and Scrolling' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
Viva-Voce Questions • What are the four parts of the box model? • How does border-box change width calculation? • What does overflow:auto do?
