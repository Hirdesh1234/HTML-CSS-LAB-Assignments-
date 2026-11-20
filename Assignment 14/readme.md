Experiment Title CSS Grid Layouts
Aim Create equal-column grids, a responsive gallery, and a named-area dashboard.
Software / Tools Required VS Code or text editor, web browser
Theory CSS Grid is a two-dimensional layout system. grid-template-columns defines columns; fr distributes available space; repeat() repeats track definitions; minmax() sets responsive bounds; grid-template-areas assigns named layout regions.
Algorithm / Procedure
Create grid-first.html with six numbered boxes, three equal columns, and 12px gap.
Create gallery.html with six labels and repeat(auto-fill, minmax(150px, 1fr)) plus 10px gap.
Create dashboard-areas.html with 200px and 1fr columns and named header/sidebar/main/footer areas.
Program / Queries / Commands grid-first.html
<title>Grid First</title> <style> .grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; } .grid div { background: #dbeafe; padding: 24px; text-align: center; } </style>
1
2
3
4
5
6
gallery.html

<title>Club Photo Gallery</title> <style> .gallery { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 10px; } .gallery div { min-height: 120px; display: grid; place-items: center; background: #e5e7eb; } </style>
Club Photo Gallery
Photo 1
Photo 2
Photo 3
Photo 4
Photo 5
Photo 6
dashboard-areas.html

<title>Dashboard Areas</title> <style> .dashboard { display: grid; grid-template-columns: 200px 1fr; grid-template-areas: "header header" "sidebar main" "footer footer"; gap: 10px; } header { grid-area: header; background: #1d3557; color: white; padding: 20px; } aside { grid-area: sidebar; background: #e5e7eb; padding: 20px; } main { grid-area: main; background: #f3f4f6; padding: 20px; min-height: 180px; } footer { grid-area: footer; background: #1d3557; color: white; padding: 20px; } </style>
Dashboard Header Sidebar Main content Dashboard Footer
Input Six box numbers, six gallery labels, and dashboard region labels.
Output Six boxes appear in two rows of three; gallery columns adapt to viewport; dashboard areas occupy the requested positions. Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
Result The experiment 'CSS Grid Layouts' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
Viva-Voce Questions • How is Grid different from Flexbox? • What does fr represent? • What is grid-template-areas?
