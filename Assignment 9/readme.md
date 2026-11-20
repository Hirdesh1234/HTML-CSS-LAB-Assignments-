Experiment Title Tables with Headers and Footers
Aim Create marks tables with captions, header/body/footer sections, averages, and scope attributes.
Software / Tools Required VS Code or text editor, web browser
Theory HTML tables organize tabular data using table, caption, thead, tbody, tfoot, tr, th, and td. scope=col and scope=row help assistive technology associate cells with headers. Average is the sum divided by the number of values.
Algorithm / Procedure
Create marks.html with caption, header, and three student rows.
Create marks-average.html with Asha and Rohan and calculate each subject average.
Create marks-accessible.html with scope=col on column headers and scope=row on name headers.
Program / Queries / Commands marks.html
<title>Marks of Class A</title> Marks of Class A
Name	Maths	Science
Asha	78	85
Rohan	64	70
Neha	91	88
marks-average.html

<title>Marks Average</title> Marks of Class A
Name	Maths	Science
Asha	78	85
Rohan	64	70
Class average	71	77.5
marks-accessible.html

<title>Accessible Marks</title> Marks of Class A
Name	Maths	Science
Asha	78	85
Rohan	64	70
Input Marks: Asha 78/85, Rohan 64/70, Neha 91/88. Averages for Asha and Rohan: Maths 71, Science 77.5.
Output Tables show the specified rows; average footer shows 71 and 77.5; accessible table headers carry scope attributes. Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
Result The experiment 'Tables with Headers and Footers' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
Viva-Voce Questions • What is the purpose of caption? • Why use thead and tbody? • What do scope=col and scope=row mean?
