# Senators-Data-Presentation-Web-Application
This project was developed as part of my coursework for COMP30680 - Web Application Development. It is a dynamic webpage that displays information on US Senators, using JSON data sourced from govtrack.us. The project demonstrates my skills in HTML, CSS, and JavaScript for loading, manipulating, and presenting JSON data without relying on external JavaScript frameworks or libraries.

Project Overview
The primary objective of this project was to create an interactive webpage using vanilla JavaScript to handle JSON data. The webpage provides users with the ability to view, filter, and explore detailed information on US senators, enhancing both user experience and data accessibility.

Features
Party Affiliation Count

Displays the total number of senators per party (e.g., Democrats, Republicans) based on the JSON data.
Leadership Roles

Lists senators holding leadership roles, organized by party affiliation. The format displays both the role and the senator’s name, grouped by political party.
Senators List with Filtering Options

Provides a full list of senators, showing details such as:
Party affiliation
State
Gender
Rank (junior/senior)
Includes filtering options:
Party: Allows filtering by specific party (e.g., Democrat, Republican) or viewing all.
State: Filters senators by state.
Rank: Filters by senator rank (junior or senior).
Filters can be combined to refine the results further. For instance, users can filter by both party and state.
Detailed View of Selected Senators

When a senator is selected, additional information is displayed, including:
Office Address
Date of Birth
Start Date in Office
Social Media: Twitter and YouTube IDs if available
Website: A clickable link that opens in a new tab
Technical Requirements
This project was completed with the following technical restrictions:

Languages: HTML, CSS, and JavaScript only (no additional libraries like jQuery were used).
No Page Reloads: All interactions and data manipulations are performed dynamically on a single page, without reloading or navigating to other pages.
No Hardcoded Data: All information, including party lists and leadership roles, is dynamically sourced from the JSON file to avoid hardcoding.

Getting Started
1. Clone this repository:
2. Open senators.html in your development environment (such as VSCode).
3. Use the Live Server extension (or similar) to view the webpage. This will allow you to see changes in real-time and interact with the site.
   In VSCode, right-click senators.html and select "Open with Live Server" if you have the Live Server extension installed.
4. Interact with the filters to explore the senators' data, and click on a senator’s name for more detailed information.


Learning Outcomes
This project helped me deepen my understanding of:

JavaScript Data Handling: Loading and parsing JSON data directly in JavaScript.
DOM Manipulation: Dynamically displaying data and implementing user interactivity without page reloads.
HTML/CSS for Structure and Styling: Structuring data presentations and building a user-friendly interface.
Filter Logic: Creating multi-criteria filtering options to allow users flexible ways to interact with data.
Originality Disclaimer
This project is entirely my own work, created for the COMP30680 Web Application Development course. All code was written by me without the use of any external code snippets or tutorials. Any resemblance to other work is coincidental, as this project was developed independently. Please respect academic integrity if referencing this project.

License
This project is created for educational purposes and is licensed under the MIT License.
