Budget Tracker
Project Description

This is a Budget Tracker website built using HTML and CSS.

The project allows users to view sample expenses and provides a form for entering new expenses.

Features
Expense Table

The project contains an HTML table with:

Name

Amount

Category

Date

The table contains five sample expenses.

It uses:

<table>

<thead>

<tbody>

<tr>

<th>

<td>

The table also has borders, padding, a colored header, alternating row colors, and a hover effect.

Add Expense Form

The form contains:

Expense Name

Amount

Category

Date

Add Expense button

The category dropdown contains:

Food

Transport

Rent

Entertainment

Other

Every form control has a unique ID.

Multimedia

A budget tracker icon has been added using an <img> element.

A budgeting video has been embedded using an <iframe>.

Interactive Elements

The project contains a collapsible "How to use this tracker" section using:

<details>

<summary>

The table rows also change color when the mouse moves over them.

The Add Expense button uses cursor: pointer.

Advanced CSS Selectors

The project uses several advanced CSS selectors:

.expenses-section td — descendant selector

tr:nth-child(even) — position-based pseudo-class

input:not([type="submit"]) — negation pseudo-class

input:focus — focus pseudo-class

Technologies

HTML5

CSS3

How to Run

Open the index.html file in a web browser.

Future Improvements

JavaScript can later be added to make the Add Expense button functional and allow users to add and manage expenses dynamically.