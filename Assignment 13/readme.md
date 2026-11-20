Experiment Title Flexbox Layouts
Aim Use Flexbox for a navigation bar, centered cards, and wrapping product cards.
Software / Tools Required VS Code or text editor, web browser
Theory Flexbox is a one-dimensional layout system. display:flex creates a flex container. justify-content aligns items along the main axis, align-items along the cross axis, gap sets spacing, and flex-wrap allows items to wrap onto multiple lines.
Algorithm / Procedure
Create nav-flex.html with four links in a horizontal dark navigation bar.
Create centred-cards.html with Starter, Standard, and Premium cards centered in one row.
Create wrapping-cards.html with four stationery cards and flex-wrap:wrap.
Resize the browser to observe wrapping.
Program / Queries / Commands nav-flex.html
<title>Flex Navigation</title> <style> nav { display: flex; gap: 24px; background: #222; padding: 16px; } nav a { color: white; text-decoration: none; } </style> HomeAboutEventsContact
centred-cards.html

<title>Centred Cards</title> <style> .row { display: flex; justify-content: center; align-items: center; gap: 20px; min-height: 240px; } .card { padding: 20px; border: 1px solid #777; border-radius: 8px; text-align: center; min-width: 120px; } </style>
Starter
199

Standard
349

Premium
499

wrapping-cards.html

<title>Stationery Shop</title> <style> .cards { display: flex; flex-wrap: wrap; gap: 16px; } .card { flex: 1 1 180px; border: 1px solid #777; padding: 18px; border-radius: 8px; } </style>
Stationery Shop
Notebook
Price: 60

Pen
Price: 15

Bag
Price: 350

